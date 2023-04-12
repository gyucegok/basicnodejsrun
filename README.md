# Basic Node.js Web Hello App

This is a Node.js Web Hello App , using Google Cloud Build and Google Cloud Deploy for Continuous Integration/Continuous Delivery

To deploy the pipeline use;

gcloud deploy apply --file clouddeploygke.yaml --region=us-east1 --project=gyucegok-alto

gcloud deploy apply --file clouddeployrun.yaml --region=us-east1 --project=gyucegok-alto
