# ansible-demo-oraclejdk
Ansible demo playbook to show possible ways of deploying Oracle JDK to various machines.

## Prerequisities
- The necessary Oracle files must be downloaded and provided on a local http server. Please note that this server is currently hard coded with the IP '192.168.123.191'.
- The playbooks expect various inventory groups: windows, solaris, suse, rhel.
