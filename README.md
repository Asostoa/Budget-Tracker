
# **Budget-Tracker**
![Badge](https://img.shields.io/github/license/asostoa/Budget-Tracker)
![BadgeGithub](https://img.shields.io/github/followers/asostoa?style=social)
![BadgeSize](https://img.shields.io/github/repo-size/asostoa/Budget-Tracker)
![BadgeSize](https://img.shields.io/github/v/release/asostoa/Budget-Tracker)
## Description 
This application allows users to keep track of how much money they are wasting. And how much they have comming in, giving you a total result of you'r current budget

## Table of contents
- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [License](#License)
- [Repository Link](#Repository)
- [GitHub Info](#GitHub) 
## Installation

  - Clone the reposatory into a local file in you're computer.
  - Run "npm i" inside of the terminal.
  - Create a mongodb database named "budget"
  - Run "node server" for the application to start.

  ## Usage

- This application uses a sevice worker file that keeps track of all of the files that need to be downloaded into our application for this one to work like a native application.
- Using Robo 3T for our database.
- We can add new transactions and these will be saved even when offline.
## Directory
```
Budget-Tracker
│  │  ├─ LICENSE
│  │  ├─ models
│  │  │  └─ transaction.js
│  │  ├─ package-lock.json
│  │  ├─ package.json
│  │  ├─ public
│  │  │  ├─ assets
│  │  │  │  ├─ css
│  │  │  │  │  └─ styles.css
│  │  │  │  ├─ images
│  │  │  │  │  └─ icons
│  │  │  │  │     ├─ icon-192x192.png
│  │  │  │  │     └─ icon-512x512.png
│  │  │  │  └─ js
│  │  │  │     ├─ db.js
│  │  │  │     └─ index.js
│  │  │  ├─ index.html
│  │  │  ├─ manifest.webmanifest
│  │  │  └─ service-worker.js
│  │  ├─ README.md
│  │  ├─ routes
│  │  │  └─ api.js
│  │  └─ server.js
│  └─ package-lock.json
```

## License
![Badge](https://img.shields.io/github/license/asostoa/Budget-Tracker)
## Repository
- [Project Repo](https://asostoa.github.io/Budget-Tracker)
## GitHub 
- [GitHub Profile](https://github.com/Asostoa)


