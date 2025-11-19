# Day 1: Create a Logical Diagram.
The following diagram shows all the components and connections built for this project to achieve the objectives in Table 1.


<img width="602" height="649" alt="Diagram" src="https://github.com/user-attachments/assets/f96fb6bb-c975-43be-9142-0019da8c53dd" />
In the previous diagram, we designed a private network 172.31.0.0 with six servers in a Virtual Private Cloud (VPC). The provider chosen to make each machine was Vultr, a cloud computing company that provides cloud infrastructure services. Below a brief description of each server:
Windows Server:
Ubuntu Server:
Fleet Server is a component that connects Elastic Agents to Fleet, serving as a control plane for updating and managing many Elastic Agent connections. It is part of the Elastic stack and requires an Elasticsearch instance to run.
Elastic & Kibana: 
os Ticket Server:
c2 Server Mythic:
Kali Linux:
