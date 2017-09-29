Eric Chong 
ver 2.0
2017-09-28


Deploy web servers and setup ELB.

deploy_web_servers_and_lb.yml
This playbook deploy 2 RHEL instances and install Apache web server.  A ELB is created and registered with Route 53.
Instances are tagged with Project:ANSIBLE-DEMO

Instance Name:
demo-accounting-web-001
demo-accounting-web-002

ELB Name:
demo-accounting-web-lb

DNS Name
eric-aws-demo.testlab.space


terminate_web_servers_and_lb.yml
This plabook terminated all instances with tag Project:ANSIBLE-DEMO.  It will also remove demo-accounting-web-lb.

