# Ansible Tower Use Netbox as Inventory Collection

### Using Inventory Plugin Within AWX/Tower
This will cover the basic usage of the NetBox inventory plugin within this collection.

1. Define `collections/requirements.yml` within a Git project.
1. AWX/Tower will download the collection on each run. This can be handled differently or excluded if storing Ansible Collections on the AWX/Tower box.
1. Define `inventory.yml` in Git project that adheres to inventory plugin structure.
1. Add Git project to AWX/Tower as a project.
1. Create inventory and select source from project.
1. Select the AWX/Tower project from Step 2
1. Select the inventory.yml file in the project from Step 3
1. Make sure your Tower installation uses Python 3 or select the proper ANSIBLE ENVIRONMENT
1. Click Save and sync source.
