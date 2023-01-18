Link: [Here](https://www.linkedin.com/learning/learning-google-cloud-developer-and-devops-tools/state-of-google-cloud-tools?autoplay=true&contextUrn=urn%3Ali%3AlyndaLearningPath%3A57fbd40f3dd5594c8cb04601&resume=false&u=35519164)
# 1. Tools for Application Users
* Goole Console for learners
* User authentication and authorization
* GCP services and menus
* Key Google Cloud services: Comepute 
    - gcloud compute instances list --> check all virtual machine on GCP
* Key Google Cloud services: Files and Data
    - search "Bucket" to the Files and Data. 
* Key Google Cloud services: IAM and more
* Quiz
    * Question 1 of 5: What feature can you use to quickly locate particular cloud services?
        * Tree
        * Pin
        * Search  (Correct Answer)
        * Button
    * Question 2 of 5: What method should you use with the Google Cloud Console?
        * Menu
        * API
        * Search  (Correct Answer)
        * script
    * Question 3 of 5: You can quickly connect to Compute Engine Linux instances using the built-in _____ tool.
        * terminal
        * SSH (Correct Answer)
        * Remote Desktop
        * gcloud sdk
    * Question 4 of 5: How can you display storage bucket labels in the console?
        * with Help
        * with Search
        * with Filter
        * with Custom Display (Correct Answer)
    * Question 5 of 5: You use the _____ section to check, set, or verify object permissions.
        * Security
        * IAM (Correct Answer)
        * SCC
        * Permissions
# 2. Tools for Data Scientists
  * Enable APIs for DLVMs
  * Using Google Cloud or SDK with terminal
  * Using Google Colab notebooks
  * Using Google-managed notebooks
  * Using Big Query ML
  * Quiz:
    * Question 1 of 5: What URL will allow you to access a Colab Notebook?
      * www.kaggle.com
      * cloud.google.com
      * www.colab.com
      * colab.research.google.com (Correct Answer)
    * Question 2 of 5: You want to shutdown the DLVM. Which command should you run?
      * gcloud compute instances stop $INSTANCE_NAME (Correct Answer)
      * gcloud compute instance pause $INSTANCE_NAME
      * gcloud compute instances pause $INSTANCE_NAME
      * gcloud compute instance stop $INSTANCE_NAME
    * Question 3 of 5: Which interface allows you to execute machine learning model queries in BigQuery?
      * Jupyter
      * MQL
      * Jupyter Lab
      * SQL (Correct Answer)
    * Question 4 of 5: You can use the _____ interface to access notebook features in a Vertex AI Notebook.
      * Remote Desktop
      * Jupyter
      * SSH
      * Jupyter Lab (Correct Answer)
    * Question 5 of 5: You want to create a DLVM. What do you need to enable first?
      * Vertex AI API (Correct Answer)
      * GCS API
      * GCE API
      * API
# 3. Tools for DevOps
* Using Google Cloud scripts with Cloud Shell for storage
* Deploying a VM with Google Cloud script
* Running GCP Deployments (Terraform)
* Monitoring GCP with Cloud Logging
* Monitoring GCP Security with SCC
* Designing GCP Solutions with Architecture Diagramming (../architecture)
* Quiz:
  * Question 1 of 4: What would you use to quickly create a script to deploy a VM?
    * the console (Correct Answer)  
    * the terminal
    * the SDK
    * the notebook
  * Question 2 of 4: You can use the _____ tool to interact with Cloud Storage.
    * gstorage
    * gcloud bucket
    * gsutil (Correct Answer)  
    * bq
  * Question 3 of 4: The GCP SCC tools read from the Google Cloud _____ service.
    * monitoring
    * management
    * logging (Correct Answer) 
    * observability
  * Question 4 of 4: Google Cloud references architectures can be drawn using _____ tools.
    * Integrated
    * Premium
    * Free (Correct Answer) 
    * Enterprise
# 4. Tools for Developers
* Coding with the GCP local Google Cloud SDK
* Coding with the GCP add-in for VSCode
  * 1. install google cloud sdk
  * 2. intrall add-in "Cloud Code"
* Storing code in Cloud Source Repositories
* Storing artifacts in GCR or Artifact Registry
* Storing secrets in Secrets Manager
* Implementing CI/CD with Cloud Build
* Quiz
  * Question 1 of 6: Google Cloud Source Repositories are designed to store _____.
    * application code (Correct Answer) 
    * docker container images
    * key-value pairs
    * secrets
  * Question 2 of 6: You want to use the Google Cloud add-in for VSCode. What do you need to install locally?
    * Google Drive
    * Google Colabs
    * Google Authenticator
    * Google Cloud SDK (Correct Answer)
  * Question 3 of 6: Stored secrets as _______
    * named sets
    * named keyrings
    * named secrets  (Correct Answer)
    * named images
  * Question 4 of 6: What can you store in the Artifact Registry?
    * application code
    * jar files (Correct Answer)
    * dockerfiles
    * certificates
  * Question 5 of 6: Where are CloudBuild outputs pushed to?
    * Cloud Source Repositories
    * Container Registry
    * Artifact Registry  (Correct Answer)
    * Secrets Manager
  * Question 6 of 6: What command would you use to authenticate to the local GCP SDK?
    * gcloud login
    * gcloud int
    * gcloud auth login  (Correct Answer)
    * gcloud info