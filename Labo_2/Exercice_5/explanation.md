# Explaination of the remediation

We figured that a simple alert would be enough to let us know that an attack was underway.

Since Microsoft Azure is accessible at all times, we can shut down the machine or block the attacker's IP or target port immediately after receiving the message. 

By simply issuing an alert, we allow ourselves to make an ssh connection in an emergency without having to disable the rule, whereas if we had set up an automatic response system, we would have had to disable it for every ssh connection.
