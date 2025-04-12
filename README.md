# Human AI Project

This repository contains the Human AI project.

## Description
A project exploring the intersection of human and artificial intelligence.

## Getting Started
Instructions for setting up and running the project will be added here. 

# backend dev setup
- cd backend
- pip install uv 
- python -m venv open-webui-venv
- source open-webui-venv/bin/activate
- pip install -r requirements.txt -U
- ./dev.sh

# frontend dev setup
- brew install nvm   
- nano ~/.zshrc
- Then add these lines at the bottom (or make sure they’re there):
export NVM_DIR="$HOME/.nvm"
[ -s "$(brew --prefix nvm)/nvm.sh" ] && \. "$(brew --prefix nvm)/nvm.sh"
- mkdir -p ~/.nvm
- source ~/.zshrc
- nvm install v22
- nvm use v22       
- npm install
- npm run dev