# cds--gcp-cd
Basic Continuous Delivery on GCP

## Requirements
Every continuous delivery pipeline in GCP needs at least the following files
* an application file, e.g. **app.py**
* a .yaml for the environment configs, e.g. **app.yaml**
* a **cloudbuild.yaml** file for deployment configs
* a **requirements.txt** for specifying app requirements
