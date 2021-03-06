.. The contents of this file may be included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


This configuration file has the following settings for the |service redis| service:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``redis['appendfsync']``
     - |appendfsync| Default value: ``"everysec"``. For example:

       .. code-block:: ruby

          redis['appendfsync'] = "everysec"
   * - ``redis['appendonly']``
     - |appendonly| Set to ``yes`` to dump data to an append-only log file. Default value: ``"no"``. For example:

       .. code-block:: ruby

          redis['appendonly'] = "no"

   * - ``redis['bind']``
     - |bind redis| Default value: ``"127.0.0.1"``. For example:

       .. code-block:: ruby

          redis['bind'] = "127.0.0.1"

   * - ``redis['databases']``
     - |database_quantity| Default value: ``"16"``. For example:

       .. code-block:: ruby

          redis['databases'] = "16"

   * - ``redis['dir']``
     - |directory redis| Default value: ``"/var/opt/opscode/redis"``. For example:

       .. code-block:: ruby

          redis['dir'] = "/var/opt/opscode/redis"

   * - ``redis['enable']``
     - |enable service| Default value: ``true``. For example:

       .. code-block:: ruby

          redis['enable'] = true

   * - ``redis['ha']``
     - |use ha| Default value: ``false``. For example:

       .. code-block:: ruby

          redis['ha'] = false

   * - ``redis['log_directory']``
     - |directory logs| The default value is the recommended value. Default value: ``"/var/log/opscode/redis"``. For example:

       .. code-block:: ruby

          redis['log_directory'] = "/var/log/opscode/redis"

   * - ``redis['loglevel']``
     - Default value: ``"notice"``. For example:

       .. code-block:: ruby

          redis['loglevel'] = "notice"

   * - ``redis['maxmemory']``
     - |memory maximum_redis| Default value: ``"1g"``. For example:

       .. code-block:: ruby

          redis['maxmemory'] = "1g"

   * - ``redis['maxmemory_policy']``
     - |memory maximum_policy_redis| Default value: ``"volatile-lru"``. For example:

       .. code-block:: ruby

          redis['maxmemory_policy'] = "volatile-lru"

   * - ``redis['port']``
     - |port redis| Default value: ``"6379"``. For example:

       .. code-block:: ruby

          redis['port'] = "6379"

   * - ``redis['root']``
     - |root redis| Default value: ``"/var/opt/opscode/redis"``. For example:

       .. code-block:: ruby

          redis['root'] = "/var/opt/opscode/redis"

   * - ``redis['svlogd_num']``
     - |svlogd_num| Default value: ``10``. For example:

       .. code-block:: ruby

          redis['svlogd_num'] = 10

   * - ``redis['svlogd_size']``
     - |svlogd_size| Default value: ``1000000``. For example:

       .. code-block:: ruby

          redis['svlogd_size'] = 1000000

   * - ``redis['timeout']``
     - |timeout redis| Default value: ``"300"``. For example:

       .. code-block:: ruby

          redis['timeout'] = "300"

   * - ``redis['vip']``
     - |ip_address virtual| Default value: ``"127.0.0.1"``. For example:

       .. code-block:: ruby

          redis['vip'] = "127.0.0.1"

   * - ``redis['vm']``
     - Default value:

       .. code-block:: ruby

          {"enabled"=>"no",
           "max_memory"=>"0",
           "page_size"=>"32",
           "pages"=>"134217728",
           "max_threads"=>"4"}

       For example:

       .. code-block:: ruby

          redis['vm'] = {"enabled"=>"no",
                         "max_memory"=>"0",
                         "page_size"=>"32",
                         "pages"=>"134217728",
                         "max_threads"=>"4"}

