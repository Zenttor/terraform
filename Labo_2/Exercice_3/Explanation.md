# Sentinel rules creation
After activating Sentinel, we created a Workspace (https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Workspace%20created.png). 

We then created a data collection rule (https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Data%20collection%20rule.png).

We've created a rule to check that no syslog log reports an ssh connection from a public IP address.(https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Sentinel%20rule%20query.png)|(https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Rule%20created.png)

To obtain more information about the attacker, we retrieve the ip of the machine initiating the connection, as well as the user on which the machine is trying to connect.(https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Query%20result.png)

The query is configured to run every 5 minutes (the shortest time allowed by Azure) in order to determine as regularly as possible whether a remote machine is trying to connect to the VM.(https://github.com/Zenttor/terraform/blob/master/Labo_2/Exercice_3/Query%20schedule.png)