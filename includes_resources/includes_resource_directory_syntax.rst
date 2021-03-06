.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The syntax for using the |resource directory| resource in a recipe is as follows:

.. code-block:: ruby

   directory "name" do
     attribute "value" # see attributes section below
     ...
     action :action # see actions section below
   end

where 

* ``directory`` tells the |chef client| to use the ``Chef::Provider::Directory`` provider during the |chef client| run
* ``name`` is the name of the resource block; when the ``path`` attribute is not specified as part of a recipe, ``name`` is also the path to the directory, from the root
* ``attribute`` is zero (or more) of the attributes that are available for this resource
* ``:action`` identifies which steps the |chef client| will take to bring the node into the desired state

For example:

.. code-block:: ruby

   directory "/var/lib/foo" do
     owner 'root'
     group 'root'
     mode '0644'
     action :create
   end

A variable may be used to define a directory, and then again within the recipe itself:

.. code-block:: ruby

   node.default['apache']['dir'] = '/etc/apache2'
   
   directory node['apache']['dir'] do
     owner 'apache'
     group 'apache'
     action :create
   end
