## Everything related to Jenkins as code that I need in my projects
Theme, pipelines, deploying to kubernetes cluster etc…
___
* **Helm chart** used to deploy Jenkins on k8s cluster with simple script to execute two commands
    ```
    $ kubectl create ns jenkins

    $ helm install jenkins jenkins/jenkins -n jenkins -f jenkins-values.yaml 
    ```
* **CASC** configuration as code for pipelines and simple theme plugin

* **Kustomize** with helm chart of jenkins but in kustomize way
