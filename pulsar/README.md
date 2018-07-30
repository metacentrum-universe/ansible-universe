Install and configure Pulsar

## Variables
* **pulsar_manager** - Job manager used by Pulsar, available options are `htcondor` and `pbs`
* **pulsar_staging_directory** - Directory to stage files to
* **pulsar_tool_dependency_directory** - The default directory used by tool dependency resolves to find dependency scripts
* **pulsar_message_queue_url** - URL of the message queue Pulsar uses for communication with Galaxy
* **pulsar_require_certificate** - Whether or not to require a secure connection with message queue
* **pulsar_pbs_job_destination** - PBS job destination (queue)
* **pulsar_bind_ip** - Pulsar server IP
* **pulsar_bind_port** - Pulsar server port
* **pulsar_directory** - Directory where to install Pulsar
* **pulsar_user** - User under which is Pulsar run
* **pulsar_group** - Group for Pulsar files
