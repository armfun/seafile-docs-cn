# Summary

* [概览](overview/README.md)
   * [Seafile 组件](overview/components.md)
   * [研发路线图](roadmap.md)
   * [常见问题解答](faq.md)
   * [修改日志](changelog.md)
   * [我要参与](contribution.md)
* [Linux 下部署 Seafile 服务器](deploy/README.md)
   * [部署 Seafile 服务器（使用 SQLite）](deploy/using_sqlite.md)
   * [部署 Seafile 服务器（使用 MySQL）](deploy/using_mysql.md)
   * [Nginx 下配置 Seahub](deploy/deploy_with_nginx.md)
   * [Nginx 下启用 Https](deploy/https_with_nginx.md)
   * [Apache 下配置 Seahub](deploy/deploy_with_apache.md)
   * [Apache 下启用 Https](deploy/https_with_apache.md)
   * [Seafile LDAP 配置](deploy/using_ldap.md)
   * [开机启动 Seafile](deploy/start_Seafile_at_system_bootup.md)
   * [防火墙设置](deploy/using_firewall.md)
   * [Logrotate 管理系统日志](deploy/using_logrotate.md)
   * 其他部署说明
       * [使用 Memcached](deploy/add_memcached.md)
       * [使用 NAT](deploy/deploy_Seafile_behind_NAT.md)
       * [非根域名下部署 Seahub](deploy/deploy_Seahub_at_Non-root_domain.md)
       * [从 SQLite 迁移至 MySQL](deploy/migrate_from_sqlite_to_mysql.md)
   * [安装常见问题](deploy/common_problems_for_setting_up_server.md)
   * [升级](deploy/upgrade.md)
* [Windows 下部署 Seafile 服务器](deploy_windows/deploy_with_windows.md)
   * [下载安装 Windows 版 Seafile 服务器](deploy_windows/download_and_setup_seafile_windows_server.md)
   * [安装 Seafile 为 Windows 服务](deploy_windows/install_seafile_server_as_a_windows_service.md)
   * [所用端口说明](deploy_windows/ports_used_by_seafile_windows_server.md)
   * [升级](deploy_windows/upgrading_seafile_windows_server.md)
* [部署 Seafile 专业版服务器](deploy_pro/README.md)
   * [下载安装 Seafile 专业版服务器](deploy_pro/下载与安装 Seafile 专业版服务器.md)
   * [从社区版迁移至专业版](deploy_pro/从 Seafile 社区版服务器迁移到专业版服务器.md)
   * [升级](deploy_pro/升级 Seafile 专业版服务器.md)
   * [Amazon S3 下安装](deploy_pro/安装 Seafile 专业版服务器并使用亚马逊 S3.md)
   * [OpenStackSwift 下安装](deploy_pro/seafile__openstackswif.md)
   * [Ceph 下安装](deploy_pro/安装 Seafile 专业版服务器并使用 Ceph.md)
   * [配置选项](seafile.md)
   * 其他部署说明
       * [使用 ElasticSearch 服务器](deploy_pro/使用已经存在的 ElasticSearch 服务器.md)
       * [文件搜索说明](deploy_pro/关于文件搜索的一些细节.md)
       * [集群部署](deploy_pro/deploy_in_a_cluster.md)
       * [集群中启用搜索和后台服务](deploy_pro/enable_search_and_background_tasks_in_a_cluster.md)
   * [常见问题解答](deploy_pro/Seafile 专业版服务器的 FAQ.md)
   * [软件许可协议](deploy_pro/license-pro-edition.md)
* [服务器个性化配置](config/README.md
   * [Config and customize Email notifications](config/email.md
   * [ccnet.conf](config/ccnet-conf.md)
   * [seafile.conf](config/seafile-conf.md)
   * [seahub_settings.py](config/seahub_settings_py.md)
   * [个性化 Seahub](config/seahub_customization.md
   * [个性化邮件提醒](config/customize_email_notifications.md
* [管理员手册](maintain/README.md)
   * [账户管理](maintain/account.md)
   * [日志](maintain/logs.md)
   * [备份与恢复](maintain/backup_recovery.md)
   * [Seafile FSCK](maintain/seafile_fsck.md)
   * [Seafile GC](maintain/seafile_gc.md)
* [WebDAV 和 FUSE 扩展](extension/README.md)
   * [WebDAV 扩展](extension/webdav.md)
   * [FUSE 扩展](extension/fuse.md)
* [安全选项](security/README.md)
* [开发文档](develop/README.md)
   * [编译 Seafile](build_seafile/README.md)
       * [Linux](build_seafile/linux.md)
       * [Windows](build_seafile/windows.md)
       * [Max OS X](build_seafile/osx.md)
       * [Server](build_seafile/server.md)
   * [开发环境](develop/env.md)
   * [编程规范](develop/code_standard.md)
   * [Web API](develop/web_api.md)
   * [Python API](develop/python_api.md)
   * [数据模型](develop/data_model.md)
   * [服务器组件](develop/server-components.md)
   * [同步算法](develop/sync_algorithm.md)
