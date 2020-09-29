# saml_automation
SAML SP configuration deployment using Ansible

Instructions:

Note: this playbook uses scp tocopy file to BIG-IP, ssh key exchange between Ansible controller and BIG-IP is needed.
1- copy IDP certificate, SP certificate and SP key in the working root directory. Name for the file must match {{app_domain_name}} variable as {{app_domain_name}}_idp_conn.crt, {{app_domain_name}}.crt, {{app_domain_name}}.key
2- Modify ansible playbook with your username/password, and management_ip
3- Modify hosts file with your details.
4- Run ansible playbook
