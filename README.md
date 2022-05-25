

## ANSIBLE REFACTORING AND STATIC ASSIGNMENTS (IMPORTS AND ROLES)

Project 12 builds on what we learnt in [project 11](https://github.com/uzukwujp/ansible-config-mgt). Here we learn about Ansibles feature to help better organise our playbook and make them reuseable.


### ROLES

Roles is a feature of Ansible that makes our playbook reuseable. If you are a developer see them as packages you import into your code. Just like in programming you can author your roles and store them in a public repository known as *GALAXY*.
 
You can also make use of publicly available roles in galaxy as well


To download a publicly available role run the command below:


 `ansible-galaxy <name of the role>`
 
 
### IMPORTS

Imports helps you add playbooks into master playbook file. This feature helps in organisation of your. You get to keep related playbooks in one file and import it into a master playbook when needed.


Refer to the code to Learn more:


The screenshots below proves the work:





![project-12](https://user-images.githubusercontent.com/52359007/170302594-74bd0e73-8661-4d0e-b5c5-f69517e5a109.PNG)





![project-12-roles-success](https://user-images.githubusercontent.com/52359007/170302663-14a54796-697e-43fe-860e-e998cb76b7bb.PNG)





![project-12a](https://user-images.githubusercontent.com/52359007/170302719-8ba39fb0-a57f-4527-8117-2f396ec68901.PNG)






