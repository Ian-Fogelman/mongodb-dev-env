# mongodb-dev-env

This repo shows you how to use the Docker Dev Environment Extension to open a VSCode instance connected to a development environment (in this case MongoDB).

## Before you Begin
- Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) 
- Install [VSCode](https://code.visualstudio.com/).
- Install the [Dev Environments browser extension](https://github.com/docker/dev-envs-extension) for [Chrome](https://chrome.google.com/webstore/detail/docker-dev-environments/gnagpachnalcofcblcgdbofnfakdbeka) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/docker-dev-environments/).

## Task

1. Click the **Open in Dev Environments** button on the top-right of the repo:
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/4daa7e76-6314-4ae6-9c7e-11d00f477a02)
2. Click **Get Started**.
3. Click **Continue**. \
  The environment Will Begin provisioning.
4. Click **Continue**.
5. Click the **OPEN IN VSCODE** button. \
   Your now in a VSCode instance connected to an environment running a MongoDB in a container!
6. Prompt the terminal with the keyboard shortcut: ``` CTRL``` + ``` SHIFT``` + ``` ` ```.
7. In the terminal run the command `Mongosh --port 27017`, to connect to MongoDB.
8. You can run the following commands to in the `mongoSH` terminal, \
To validate the instance is up run `db.hello()`. \
To Insert data run `db.test.insert({'a':1})`. \
To query data run `db.test.findOne({})`.
9. To stop the containerized development environment: open the Docker desktop UI and click the stop icon. Stopped containers remain on your system as images and can be restarted as containers using the **Dev Environments** tab in Docker Desktop.\
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/b0752821-1fa4-4a7f-8ccc-db7b5ce5c9d8)
10. To delete the containerized development environment, return to the Docker desktop UI and click the delete icon.\
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/8b188aff-938c-43e2-91f4-394f0bbe6779)
