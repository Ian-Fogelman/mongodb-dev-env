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
   Your now in a VSCode instance connected to an environment running MongoDB in a container!
8. Prompt the terminal with the keyboard shortcut: `CTRL + SHIFT + "`"`.
9. In the terminal run the command `Mongosh --port 27017`, to connect to MongoDB.
10. In the mongoSH terminal, run `db.hello()`.
