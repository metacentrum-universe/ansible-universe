Installs CVMFS client tools and stratum1

## Variables:
* **cvmfs_type** - Node type, either `client` or `stratum1`
* **cvmfs_server_urls** - List of CVMFS Stratum1 URLs
* **cvmfs_repositories** - List of CVMFS repositories
* **cvmfs_http_proxies** - List of CVMFS HTTP proxies
* **cvmfs_stratum1_servers** - List of CVMFS Stratum1 servers
* **cvmfs_apache_port** - CVMFS Stratum1 Apache port
* **cvmfs_squid_cache_mem** - CVMFS Squid cache size
* **cvmfs_squid_inventory_hostname** - CVMFS Squid inventory hostname
* **cvmfs_stratum1_ip** - CVMFS Stratum1 IP for client to connect to
* **cvmfs_spool_dir** - Directory where to link /var/spool/cvmfs/
* **cvmfs_data_dir** - Directory where to link /srv/cvmfs/
* **cvmfs_apache_user** - User under which Apache server is run
* **cvmfs_already_exists** - Whether CVMFS Stratum1 data is already available (skips some chown and ln commands)
