# 📝 Reflection

During this laboratory activity, I learned how important it is to protect a server from unwanted connections. Before this activity, I thought that running a web application was mostly about making sure it worked properly. Now, I understand that keeping it safe is just as important as making it available to users.

A host based firewall helps protect a server by controlling the connections that are allowed to reach it. Even if someone gets past the main network security, the firewall on the server can still block connections that are not allowed. In this activity, I used UFW to block incoming connections by default while allowing SSH and port 8080. This showed me how a server can have another layer of protection instead of depending on only one security measure.

Managing open ports is also important because every unnecessary open port can give attackers another way to access a server. If a service is not needed, there is no good reason to leave its port open. By allowing only the ports required for the application and remote administration, I learned how to limit unnecessary access and make the server safer.

In a real company, leaving a database port such as 3306 for MySQL open to the public internet can be dangerous. Attackers could try to guess passwords, take advantage of security weaknesses, or attempt to access private information. A database often stores important details, so access should be limited to trusted systems and authorized users rather than allowing anyone on the internet to connect.

This activity also changed how I see server security. I realized that a server can become an easy target if its settings are not checked and protected properly. Even a small mistake, such as forgetting to configure the firewall, can create a security risk. I also learned that testing the application and checking the firewall rules are both necessary to make sure the server works as expected without leaving unnecessary access open.

Finally, having eight completed missions in my GitHub portfolio makes me feel that I am improving my cloud computing skills step by step. Each activity gives me a chance to practice what I learn instead of only reading about it. I can also use this portfolio to show my progress and the skills I have developed. Overall, this mission taught me that server security requires careful setup, regular checking, and responsible management.
