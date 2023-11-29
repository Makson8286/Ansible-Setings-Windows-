# Ansible-Setings-Windows-
Run the powershell as administrator

Write Set-ExecutionPolicy Unrestricted

Select "Yes" or "Yes and all"

Go to the folder where you have the "ConfigureRemotingForAnsible" file and write ./ConfigureRemotingForAnsible

Select R

--------------------------------------------------------------------
ITS COMMAND IN File "hosts" FOR INSTALL PROGRAM 

[windows]

192.168.0.0

[windows:vars]

ansible_user=User
ansible_password=password

ansible_port=5986

ansible_connection=winrm

ansible_winrm_server_cert_validation=ignor
