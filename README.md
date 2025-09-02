## Java Maven Project


Tools:

+ Kubernetes
+ Docker
+ Maven
+ ArgoCD
+ GitLab


Summary:
+ The source code convert into .war file.
+ Then build the docker image.
+ Test the application.
+ The application image push to the docker registory.
+ Finally deploy the application.


### Source Code:

+ The developer build the source code by using Java language.
+ Source code is jave, so we using the Maven for create the .war file.


### Docker Image:

+ The .war file convert into the Docker Image.
+ First we need the docker file, the developer write that file depence on the requirement.
+ Now build the docker image.


### Test Image:

+ Pull the image from the docker registry.
+ Run the docker container and check the application.


### Push Image:

+ The application work perfectly.
+ Push the image to the docker registry, private or public.


### Deploy:

+ Finally stage is deploy the application in the cluster like, local cluster or EKS.


### CI/CD:

+ The above steps are write in the `.gitlab-ci.yaml` file.
+ Every instruction write in the ci yaml file.


### ArgoCD:

+ The argocd used to deploy the application.
+ It's connect gitlab to kubernetes cluster.
+ It's sync to gitlab.
