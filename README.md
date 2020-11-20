# Devops HSE

Apache configuration 
In this task, I need to configure an Apache server instance. 
Features to support in the configuration: 
  - the configuration should allow access only via HTTPS, 
  - all HTTP requests should be redirected to the HTTPS; 
  - there should be several (at least two) name-based virtual hosts. The first host should return any static page (e.g. just “Hello world”), the second one should run a small Python back-end, which returns a page with the current date and browser fingerprint. 
  - the configured Apache server should be wrapped into the Vagrant box.
  - apache hosts should be accessible from the local machine (from outside the Vagrant box).
