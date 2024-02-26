# coursera_rust_fundamentals
A place to work with while taking the Rust Fundamentals course on Coursera



# Codespaces Configuration
Config for Codespaces is contained within the `.devcontainer` directory. In here is the required `devcontainer.json` main file as well as a `Dockerfile` that's used to allow extra configuration of the container that should be loaded when starting up Codespaces. This was kept simple and essentially to what was shown in the course's video on the subject.

### .devcontainer
Standard GitHub CoPilot configuration file. Allows configuring many things about the container created, it's network, as well as any adjustments to VS Code once it's loaded in the container.
- Specifies that `Dockerfile` should be used to control the container
- enables the GitHub.copilot extension in VS Code

### Dockerfile
Standard docker configuration file. Simply describes which container we should be starting from, then has it run the command `apt-get update` in the container once it's fully operational. This is directly out of the video from the course.


# Editing via Codespaces
You can edit the repository via Codespaces in a way roughly equivalent to a local VS Code instance. It has the advantage that since it works in your browser you can do things the same way from many different platforms or machines without having to set up each one individually. You must be aware of how much time and resources you're using however as there's monthly limits... Some are included with a GitHub Pro account.

1. Sign into GitHub
2. Click on the "Code" button (in blue) that's shown below
![Screenshot](./Coursera-%20Rust%20Fundamentals-%20Codespaces%20start.png)
3. Click on the name of the Codespace to start. In this case "laughing space fishstick". See Screenshot:
![Screenshot](./Coursera-%20Rust%20Fundamentals-%20Codespaces%20link.png)
4. Wait for Visual Studio Code to load the Codespace.
5. Edit the files in this repository just like you would locally.
6. Make certain to shut down the Codespace since you pay for its time used!
    1. Open the "Code" area again.
	2. Click on the "..." next to the Codespace's name
	3. Choose "Stop codespace" from the list of options. (See below)
	![Screenshot](Coursera-%20Rust%20Fundamentals-%20Codespaces%20shutdown.png)