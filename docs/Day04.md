# Day 4: Set up Kibana 
# Generated an Elasticsearch enrollment token for Kibana

Go to the Ubuntu machine and set the firewall rule to allow port 5601

ufw allow 5601

Open a new tab in the browser and type http://155.138.156.17:5601

<img width="1200" height="609" alt="WelcomeELK" src="https://github.com/user-attachments/assets/c546a5cc-dba4-4b41-89ee-11cd53c9725d" />

systemctl restart kibana.service

Go to the browser, sign in, and see access to dashboards and options

![Alerts](https://github.com/user-attachments/assets/1250bb8e-d878-406d-af47-65673162fc6c)
