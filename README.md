Docker Management — Interactive Bash Menu

A polished, user-friendly Bash script to manage Docker from the terminal using a simple numbered menu. Quickly run, inspect, control and clean up containers and images, manage networks and volumes, and access Docker Compose — all without memorizing long docker CLI commands.
Features

    Start, stop, restart, pause, kill containers
    List containers (running & all), view logs, exec into containers
    Rename containers
    Search, list and remove images
    Docker info & version, system cleanup
    Manage networks and volumes
    Login / Logout for registries
    Optional Docker Compose access
    Clear, interactive numbered menu for fast workflows

Screenshots
<img width="341" height="458" alt="image" src="https://github.com/user-attachments/assets/53c36c72-7ce5-4e61-8576-3c1fd7bf573b" />
Main menu — quick overview of available categories and actions.
<img width="498" height="203" alt="image" src="https://github.com/user-attachments/assets/9354ba16-954a-41a3-ad32-0c8e8bd2590b" />

<img width="335" height="151" alt="image" src="https://github.com/user-attachments/assets/955e75a4-3490-49ad-ba99-925bd619d1ff" />

<img width="1214" height="364" alt="image" src="https://github.com/user-attachments/assets/fca40f29-0536-4345-ab7c-a374a49f8651" />
Installation

Open a terminal and run:
bash

git clone https://github.com/Jdhdx/docker-management.gitcd docker-managementls# you should see docker.shchmod +x docker.sh./docker.sh

Requirements:

    Docker installed and running
    Bash (Linux / macOS). On Windows, use WSL or Git Bash.

Usage

    Run the script: ./docker.sh
    Enter the number shown in the menu to choose an action.
    Follow on-screen prompts (e.g., container name/ID, image name).
    Press the menu number for submenus (Containers, Images, Network & Volume, Advanced, etc.).

Example:

    Start a container — choose "Run container", provide image & options when prompted.
    View logs — choose "Logs of container" and select a container to tail logs.

