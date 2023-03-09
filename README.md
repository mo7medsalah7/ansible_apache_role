# Ansible Role For Apache

An Ansible Role that installs Apache on RHEL/CentOS, Debian/Ubuntu.

## Role Variables

Default values for variables are listed in (`defaults/main.yml`).
Here is a list of available variables.

###[for RHEL/CentOS]
   
  `apache_service_name: httpd`

###[for Debian]
   
   `apache_service_name: apache2`

### Default values:- 

`apache_port: 80/tcp`

`html_page_src: index.html`
`html_page_dest: /var/www/html/index.html`

`service_start_state: started`

`service_restart_state: restarted`
`service_reload_state: reloaded`




