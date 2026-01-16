# Neovim Development Containers

## What?
These are premade container images for developing with Neovim in isolated environments. This allows you to use the best code editor in an nevironment without worrying about dependencies for your different projects.

For example, if you want to develop in Python, simply pull and run the ´nvim-python` container. Use a compose file to extend the configured image, or fork this repo and create your own custom python image. 

## Why?
VSCode has devcontainers; an extension of normal containers that lets VSCode connect to the container and run commands there.

Unlike VSCode, however, Neovim runs in the terminal. Thus you don't need a fancy connection to the container, just run Neovim in the container from the beginning!

## How?
The base image is Ubuntu:24.04. Onto it Neovim is installed and a ´dev´user is set up. This image is then used as the base for specific images. 
