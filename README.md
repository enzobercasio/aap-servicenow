
1. Request for ServiceNow PDI: https://developer.servicenow.com/dev.do#!/learn/learning-plans/washingtondc/new_to_servicenow/app_store_learnv2_buildmyfirstapp_washingtondc_personal_developer_instances
2. In Service Now Developer, change user role from 'App Engine Studio Creator' to 'Admin'
3. Install ansible servicenow.itsm collection
     ansible-galaxy collection install servicenow.itsm

#sample run
ansible-playbook playbooks/create_incident.yml -i inventory.ini

