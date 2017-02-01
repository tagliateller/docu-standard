---
title:  'This is the title: it contains a colon'
author:
- Author One
- Author Two
tags: [nothing, nothingness]
abstract: |
  This is the abstract.

  It consists of two paragraphs.
...

# Anbindung Monitoring

# Compute Node hinzufügen / entfernen

# Validierung des Deployment-Lifecycle
The playbook will perform the following steps:
Environment Validation
* Validate the public OpenShift ELB address from the installation system
* Validate the public OpenShift ELB address from the master nodes
* Validate the internal OpenShift ELB address from the master nodes
* Validate the master local master address
* Validate the health of the ETCD cluster to ensure all ETCD nodes are healthy
* Create a project in OpenShift called validate
* Create an OpenShift Application
* Add a route for the Application
* Validate the URL returns a status code of 200 or healthy
* Delete the validation project
* Ensure the URLs below and the tag variables match the variables used during deployment.
* persistent Storage nicht vergessen
