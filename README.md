# Lab Assignment: Configuring a Web Application with HAProxy Load Balancing and MySQL Database on CentOS 7 using Ansible

## Objective
In this lab assignment, you will configure a CentOS 7 environment for deploying a web application with load balancing using HAProxy and a MySQL database backend. You will utilize Ansible to automate the configuration process, focusing on system configurations such as user management, permissions, ulimits, and DNS records. This assignment will help you understand the practical usage of Ansible roles, variables, templates, handlers, and modules.

## Assignment Overview

1. **Set Up Inventory and Configuration**:
    - Define the inventory of your servers.
    - Set up configuration variables for your web servers, HAProxy, and MySQL database.

2. **System Configuration**:
    - Set up users, permissions, and ulimits.
    - Configure DNS records.

3. **Web Server Deployment**:
    - Install and configure a web server (Apache) on multiple nodes.
    - Install Git and clone a repository into the web application directory.

4. **MySQL Database Deployment**:
    - Install and configure MySQL on a dedicated database server.
    - Create a database and a user for your web application.

5. **HAProxy Load Balancer Deployment** (Optional):
    - Install and configure HAProxy on a dedicated load balancer node.
    - Set up HAProxy to distribute traffic to the web servers.

6. **Ansible Playbook**:
    - Create Ansible role to automate the entire configuration and deployment process.
    - Use variables, templates, handlers, and modules in your playbook.

## Conditions of Satisfaction

### Deliverables

1. **Ansible Roles**:
    - All playbooks must be refactored into sharable roles.

2. **Web Servers**:
    - Web servers should have the web application installed from the Git repository.
    - The Git repository URL must be moved to the variables section and assigned to a variable instead of being hardcoded.

3. **Corrections**:
    - Correct any mistakes in the playbooks.

4. **HAProxy Load Balancing** (Optional):
    - Implement HAProxy load balancing as an additional feature, if desired.

### Grading Criteria

- **Correctness and Completeness**:
    - The roles must correctly and completely configure and deploy the required components.
    - The system configurations should include user management, permissions, ulimits, and DNS settings.

- **Proper Use of Ansible Features**:
    - Utilize Ansible variables, templates, handlers, and modules appropriately and effectively.
    - Ensure the Git repository URL is parameterized in the variables section.

- **Accuracy and Security**:
    - Ensure the accuracy and security of system configurations, including users, permissions, ulimits, and DNS records.

- **Documentation**:
    - The README file should clearly document the configuration and deployment process and include any assumptions made.

- **Functionality**:
    - The deployed web application should function correctly, and the optional HAProxy load balancing should distribute traffic to the web servers effectively.
