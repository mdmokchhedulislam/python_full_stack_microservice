
In this project, Kubernetes Secrets are used to store sensitive data, while ConfigMaps are used for environment variables.

After deploying the project, you can run the following command inside the pod to apply database migrations:

python manage.py migrate

Once the migrations are complete, the project will be ready to run.
