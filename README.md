# lampstack

## Steps to deploy the Lampstack

* Take clone of the repository with the command
    ```
    git clone git clone https://github.com/harshapatel-tudip/lampstack.git
    ```
* Move into the lampstack directory
    ```
    cd lampstack
    ```
* Now create the deployment manager using command
    ```
    gcloud deployment-manager deployments create lampsatck --config=config.yaml
    ```
