# Ecommerce-deployment

**Script that _automatic_ deploy LAMP Project** 

## Functions

- Function: function package_manager_type
- Description: return the OS package manager type like [APT,DNF, and YUM]
- `Usage: package_manager_type`
---

- Function: update_package_manager
- Description: Verify if the system need to be updated or not
- `Usage: update_package_manager "package_type"`
---

- Function: check_service_status
- Description: Verify if the service is active or not
- `Usage: check_service_status "service_name"`
---

- Function: try_start_service
- Description: Know if there's a service can be started and enabled or not
- `Usage: try_start_service "app_name"`
---

- Function: install_application
- Description: Install All packages needed by the Application through file known as requriment.txt
- `Usage: install_application "package_manager_type" "requriment.txt or package"`
---

- Function: check_port
- Description: Verify that a given port is configured in the public zone firewall
- `Usage: check_port "port_number"`
---

- Function: function database_configuration
- Description: Configurate Right Port, and Mariadb/Mysql with setting up Database name and more..
- `Usage: database_configuration "port_number" "db_name"`
---


- Function: function configurate_applicaion
- Description: Configurate Right Port, Apache settings, and clone the git repo
- `Usage: configurate_applicaion "port_number" "git clone repo_url"`
---
