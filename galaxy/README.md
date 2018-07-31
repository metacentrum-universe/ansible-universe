Install and configure Galaxy. This role expect a setup with remote Pulsar via MQ.

## Variables:
* **galaxy_version** - Verison of the Galaxy to install (Git tag/branch)
* **galaxy_directory** - Directory where to install Galaxy
* **galaxy_ip** - Galaxy IP address
* **galaxy_port** - Galaxy port
* **galaxy_admins** - Comma separated list of Galaxy admin users
* **galaxy_amqp_url** - AMQP URL for Pulsar queue
* **galaxy_jobs_directory** - Pulsar's staging directory
* **galaxy_submit_user** - User under which Galaxy is submitting jobs to Pulsar
