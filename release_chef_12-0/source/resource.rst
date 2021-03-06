.. THIS PAGE DOCUMENTS chef-client version 12.0

=====================================================
About Resources and Providers
=====================================================

.. note:: |note all_resources|

.. include:: ../../includes_resources_common/includes_resources_common.rst

.. include:: ../../includes_resources_common/includes_resources_common_provider.rst

.. include:: ../../includes_resources_common/includes_resources_common_provider_platform.rst

Resources Syntax
-----------------------------------------------------
.. include:: ../../includes_resources_common/includes_resources_common_syntax.rst

Common Functionality
-----------------------------------------------------
All resources share a set of common actions, attributes, conditional executions, notifications, and relative path options.

.. list-table::
   :widths: 160 440
   :header-rows: 1

   * - Common Item
     - Description
   * - `Actions <http://docs.getchef.com/release/12/resource_common.html#actions>`_
     - |resource short_actions|
   * - `Attributes <http://docs.getchef.com/release/12/resource_common.html#attributes>`_
     - |resource short_attributes|
   * - `Guards <http://docs.getchef.com/release/12/resource_common.html#conditionals>`_
     - |resource short_conditions|
   * - `Notifications <http://docs.getchef.com/release/12/resource_common.html#notifications>`_
     - |resource short_notifications|
   * - `Relative Paths <http://docs.getchef.com/release/12/resource_common.html#relative-paths>`_
     - |resource short_relative_paths|
   * - `Windows File Security <http://docs.getchef.com/release/12/resource_common.html#windows-file-security>`_
     - |resource short_windows_file_security|
   * - `Run a Resource during Resource Compilation <http://docs.opscode.com/release/12/resource_common.html#run-from-resource-collection>`_
     - |resource short_run_during_compile|

Resources
-----------------------------------------------------
.. include:: ../../includes_resources_common/includes_resources_common_platform_resources_intro.rst

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Resource
     - Description
   * - `apt_package <http://docs.getchef.com/release/12/resource_apt_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_apt.rst
   * - `bash <http://docs.getchef.com/release/12/resource_bash.html>`_
     - .. include:: ../../includes_resources/includes_resource_script_bash.rst
   * - `batch <http://docs.getchef.com/release/12/resource_batch.html>`_
     - .. include:: ../../includes_resources/includes_resource_batch.rst
   * - `bff_package <http://docs.getchef.com/release/12/resource_bff_package.html>`_
     - .. include:: ../../release_chef_12-0/includes_resource_package_bff.rst
   * - `breakpoint <http://docs.getchef.com/release/12/resource_breakpoint.html>`_
     - .. include:: ../../includes_resources/includes_resource_breakpoint.rst
   * - `chef_gem <http://docs.getchef.com/release/12/resource_chef_gem.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_chef_gem.rst
   * - `cookbook_file <http://docs.getchef.com/release/12/resource_cookbook_file.html>`_
     - .. include:: ../../includes_resources/includes_resource_cookbook_file.rst
   * - `cron <http://docs.getchef.com/release/12/resource_cron.html>`_
     - .. include:: ../../includes_resources/includes_resource_cron.rst
   * - `csh <http://docs.getchef.com/release/12/resource_csh.html>`_
     - .. include:: ../../includes_resources/includes_resource_script_csh.rst
   * - `deploy <http://docs.getchef.com/release/12/resource_deploy.html>`_
     - .. include:: ../../includes_resources/includes_resource_deploy.rst
   * - `directory <http://docs.getchef.com/release/12/resource_directory.html>`_
     - .. include:: ../../includes_resources/includes_resource_directory.rst
   * - `dpkg_package <http://docs.getchef.com/release/12/resource_dpkg_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_dpkg.rst
   * - `dsc_script <http://docs.getchef.com/release/12/resource_dsc_script.html>`_
     - .. include:: ../../includes_resources/includes_resource_dsc_script.rst
   * - `easy_install_package <http://docs.getchef.com/release/12/resource_easy_install_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_easy_install.rst
   * - `env <http://docs.getchef.com/release/12/resource_env.html>`_
     - .. include:: ../../includes_resources/includes_resource_env.rst
   * - `erl_call <http://docs.getchef.com/release/12/resource_erlang_call.html>`_
     - .. include:: ../../includes_resources/includes_resource_erlang_call.rst
   * - `execute <http://docs.getchef.com/release/12/resource_execute.html>`_
     - .. include:: ../../includes_resources/includes_resource_execute.rst
   * - `file <http://docs.getchef.com/release/12/resource_file.html>`_
     - .. include:: ../../includes_resources/includes_resource_file.rst
   * - `freebsd_package <http://docs.getchef.com/release/12/resource_freebsd_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_freebsd.rst
   * - `gem_package <http://docs.getchef.com/release/12/resource_gem_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_gem.rst
   * - `git <http://docs.getchef.com/release/12/resource_git.html>`_
     - .. include:: ../../includes_resources/includes_resource_scm_git.rst
   * - `group <http://docs.getchef.com/release/12/resource_group.html>`_
     - .. include:: ../../includes_resources/includes_resource_group.rst
   * - `homebrew_package <http://docs.getchef.com/release/12/resource_homebrew_package.html>`_
     - .. include:: ../../release_chef_12-0/includes_resource_package_homebrew.rst
   * - `http_request <http://docs.getchef.com/release/12/resource_http_request.html>`_
     - .. include:: ../../includes_resources/includes_resource_http_request.rst
   * - `ifconfig <http://docs.getchef.com/release/12/resource_ifconfig.html>`_
     - .. include:: ../../includes_resources/includes_resource_ifconfig.rst
   * - `ips_package <http://docs.getchef.com/release/12/resource_ips_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_ips.rst
   * - `link <http://docs.getchef.com/release/12/resource_link.html>`_
     - .. include:: ../../includes_resources/includes_resource_link.rst
   * - `log <http://docs.getchef.com/release/12/resource_log.html>`_
     - .. include:: ../../includes_resources/includes_resource_log.rst
   * - `macports_package <http://docs.getchef.com/release/12/resource_macports_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_macports.rst
   * - `mdadm <http://docs.getchef.com/release/12/resource_mdadm.html>`_
     - .. include:: ../../includes_resources/includes_resource_mdadm.rst
   * - `mount <http://docs.getchef.com/release/12/resource_mount.html>`_
     - .. include:: ../../includes_resources/includes_resource_mount.rst
   * - `ohai <http://docs.getchef.com/release/12/resource_ohai.html>`_
     - .. include:: ../../includes_resources/includes_resource_ohai.rst
   * - `package <http://docs.getchef.com/release/12/resource_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package.rst
   * - `pacman_package <http://docs.getchef.com/release/12/resource_pacman_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_pacman.rst
   * - `perl <http://docs.getchef.com/release/12/resource_perl.html>`_
     - .. include:: ../../includes_resources/includes_resource_script_perl.rst
   * - `portage_package <http://docs.getchef.com/release/12/resource_portage_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_portage.rst
   * - `powershell_script <http://docs.getchef.com/release/12/resource_powershell_script.html>`_
     - .. include:: ../../includes_resources/includes_resource_powershell_script.rst
   * - `python <http://docs.getchef.com/release/12/resource_python.html>`_
     - .. include:: ../../includes_resources/includes_resource_script_python.rst
   * - `registry_key <http://docs.getchef.com/release/12/resource_registry_key.html>`_
     - .. include:: ../../includes_resources/includes_resource_registry_key.rst
   * - `remote_directory <http://docs.getchef.com/release/12/resource_remote_directory.html>`_
     - .. include:: ../../includes_resources/includes_resource_remote_directory.rst
   * - `remote_file <http://docs.getchef.com/release/12/resource_remote_file.html>`_
     - .. include:: ../../includes_resources/includes_resource_remote_file.rst
   * - `route <http://docs.getchef.com/release/12/resource_route.html>`_
     - .. include:: ../../includes_resources/includes_resource_route.rst
   * - `rpm_package <http://docs.getchef.com/release/12/resource_rpm_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_rpm.rst
   * - `ruby <http://docs.getchef.com/release/12/resource_ruby.html>`_
     - .. include:: ../../includes_resources/includes_resource_script_ruby.rst
   * - `ruby_block <http://docs.getchef.com/release/12/resource_ruby_block.html>`_
     - .. include:: ../../includes_resources/includes_resource_ruby_block.rst
   * - `script <http://docs.getchef.com/release/12/resource_script.html>`_
     - .. include:: ../../includes_resources/includes_resource_script.rst
   * - `service <http://docs.getchef.com/release/12/resource_service.html>`_
     - .. include:: ../../includes_resources/includes_resource_service.rst
   * - `smart_o_s_package <http://docs.getchef.com/release/12/resource_smartos_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_smartos.rst
   * - `solaris_package <http://docs.getchef.com/release/12/resource_solaris_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_solaris.rst
   * - `subversion <http://docs.getchef.com/release/12/resource_subversion.html>`_
     - .. include:: ../../includes_resources/includes_resource_scm_subversion.rst
   * - `template <http://docs.getchef.com/release/12/resource_template.html>`_
     - .. include:: ../../includes_resources/includes_resource_template.rst
   * - `user <http://docs.getchef.com/release/12/resource_user.html>`_
     - .. include:: ../../includes_resources/includes_resource_user.rst
   * - `windows_package <http://docs.getchef.com/release/12/resource_windows_package.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_windows.rst
   * - `yum_package <http://docs.getchef.com/release/12/resource_yum.html>`_
     - .. include:: ../../includes_resources/includes_resource_package_yum.rst

In addition, the `chef_handler <http://docs.getchef.com/release/12/resource_chef_handler.html>`_ resource is configured and run using the |cookbook chef_handler| cookbook, which is the location in which custom handlers are defined and maintained. Despite being defined in a cookbook (and as a "lightweight resource"), the |lwrp chef handler| resource should otherwise be considered a "platform resource".


