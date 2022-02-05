This is an ansible playbook that could be used to send email notifcations to receipiants pertaining to the result or output of tasks being executed on the servers.
The receipiant name, sender email and receiver email have been variableised with default values being added.
These values could be overwritten as deemed nececcery.

To execute the playbook, run the following:

**ansible-playbook -i inventory playbook.yml**

To override one of the variables, you could use extra-vars as shown below.

**ansible-playbook -i inventory playbook.yml --extra-vars 'receipiant=James'**

This overrides the receipiant name.


Given below is a demo image of how the resulting email will look like in Outlook

![alt text](https://github.com/sahilsuri008/email_notify_setup/blob/master/demo_image.jpg?raw=true)

