### This is a project to build a deployable ML model, stolen from Medium post.
Sources:
https://medium.com/@nutanbhogendrasharma/deploy-machine-learning-model-in-google-cloud-platform-using-flask-part-1-6b37d946ad4
https://medium.com/@nutanbhogendrasharma/deploy-machine-learning-model-in-google-cloud-platform-using-flask-part-2-8b8cc816e1af
https://medium.com/@nutanbhogendrasharma/deploy-machine-learning-model-in-google-cloud-platform-using-flask-part-3-20db0037bdf8

mkdir sales-app
cd sales-app
pip install virtualenv
virtualenv sales-app-venv
source sales-app-venv/bin/activate



in Part 3, have to add venv folder to .gcloudignore, see https://cloud.google.com/sdk/gcloud/reference/topic/gcloudignore



gcloud storage cp gs://pmykola-projectsgcp-artifacts/sales-budget/lr_model.pkl lr_model.pkl




At the end of Part 2, I cannot make prediction work, keep getting error 'no sklearn module'


... Part 2 is probably working, but cannot say for sure, since I have not found a way to do webpreview in jupyter.
I could verify it while doing evth within project-level CLI, but it is kind of inconvenient...
... Part 3 is partially working, but predict endpoint does not.












aside: to set up  and open webpage from jupyterlab, see this: https://github.com/jupyterlab/jupyterlab/issues/6235
