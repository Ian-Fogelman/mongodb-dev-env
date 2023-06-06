# mongodb-dev-env

This repo shows you how to use the Docker Dev Environment Extension to open a VSCode instance connected to a development environment (in this case MongoDB).

## Task

1. Install Docker Desktop / VSCode.
2. Install the [Dev Environments browser extension](https://github.com/docker/dev-envs-extension) for [Chrome](https://chrome.google.com/webstore/detail/docker-dev-environments/gnagpachnalcofcblcgdbofnfakdbeka) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/docker-dev-environments/).
3. Click the **Open in Dev Environments** button on the top-right of the repo:
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/4daa7e76-6314-4ae6-9c7e-11d00f477a02)
4. Click **Get Started**.
5. Click **Continue**. \
  The environment Will Begin provisioning.
6. Click **Continue**.
7. Click the **OPEN IN VSCODE** button. \
   Your now in a VSCode instance connected to an environment running a MongoDB in a container!
8. Prompt the terminal with the keyboard shortcut: ``` CTRL``` + ``` SHIFT``` + ``` ` ```.
9. In the terminal run the command `Mongosh --port 27017`, to connect to MongoDB.
10. You can run the following commands to in the `mongoSH` terminal, \
To validate the instance is up run `db.hello()`. \
To Insert data run `db.test.insert({'a':1})`. \
To query data run `db.test.findOne({})`.
11. To stop the containerized development environment, return to the Docker desktop UI and click the stop icon.\
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/b0752821-1fa4-4a7f-8ccc-db7b5ce5c9d8)
12. To delete the containerized development environment, return to the Docker desktop UI and click the delete icon.\
![image](https://github.com/Ian-Fogelman/mongodb-dev-env/assets/8229464/8b188aff-938c-43e2-91f4-394f0bbe6779)
