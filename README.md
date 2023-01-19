# Cisco Compliance Remediation Demo

## controller.yml
This playbook can be modified to configure your Ansible Automation Platform Controller "Tower" for the demo. After reserving a RHPDS cisco only network workshop/demo you can run this playbook from your laptop to configure your AAP2.x as code.

~~~
 git clone https://gitlab.com/redhatautomation/cisco-compliance-remediation-validation.git
~~~
 Please update vars/vars.yml toyour local workspace to include your RHPDS info prior to running the playbook "controller.yml" 

## job-template
Run the Cisco-Prepare-Env first to set the base configs of the router.

## workflow
The Cisco-STIG-Remediation-Workflow can be run in checkmode or for real with auto-remediation form the workflow survey

## single source of truth 
Don't forget to open the second gitlab repo during the demo: https://gitlab.com/tdubiel1/network-stig-demo.git
~~~
ssot/stig.yml
~~~
This is the file used to illustrate how the compliance check works. ctrl-f ntp to quickly locate 


