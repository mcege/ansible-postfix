TCP authentication is not automated. Before running this role, execute the following command in the destined server:

saslpasswd2 -c -u {{ postfix_domain }} {{ postfix_user }}