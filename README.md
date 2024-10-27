# ansible-demo
Quick demo of installing Security Content Automation Protocol (SCAP) Compliance Checker (https://www.niwcatlantic.navy.mil/Technology/SCAP/) and running a scan on RHEL 8 using ansible.

Assumes internet connectivity and downloads content from DISA (https://public.cyber.mil/stigs/scap/)

Installs the scanner and benchmark on the target system ( not a remote scan set up)

Clone the repo and execute using "ansible-playbook -i hosts scan-rhel8.yml" after establishing an ansible controller and target system, associated credentials, and updating the ansible inventory per your environment
