<p align="center"><img align="center" width="280" src=".github/Howest-logo-wit.svg#gh-dark-mode-only"/></p>
<p align="center"><img align="center" width="280" src=".github/Howest-logo-zwart.svg#gh-light-mode-only"/></p>

<h3 align="center">One-liner about your project goes here</h3>

<hr>

Put a description of the project here.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Table of contents :page_facing_up:

- [Project setup](#project-setup-hammer_and_wrench)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Deployment](#deployment-rocket)
  - [Prerequisites](#prerequisites-1)
  - [Deployment](#deployment)
- [Future improvements](#future-improvements-bulb)
- [Possible issues](#possible-issues-x)

## Project setup :hammer_and_wrench:

### Prerequisites

To run this project you will need **Python 3.10** or higher.

Optionally, create a virtual environment:

```sh
python -m venv .venv

source .venv/bin/activate   # <-- Linux/MacOS
.venv\Scripts\activate      # <-- Windows
```

### Installation

1. Install the required dependencies

   ```sh
   pip install -r requirements.txt
   ```

2. Create a `.env` file in the root of the project

   ```env
   SECRET_KEY=your_secret_key
   ```

3. Run the project locally

   ```sh
   python main.py
   ```

4. Open your browser and go to [http://localhost:5000](http://localhost:5000)

## Deployment :rocket:

### Prerequisites

To deploy this project you will need a working **Docker** installation with **Docker Compose**.

### Deployment

1. Create a new repository on Docker Hub

2. Execute the following commands in the terminal

   ```sh
   docker login
   docker build -t project_name:version .
   docker tag project_name:version your_docker_username/your_repository_name:version
   docker push your_docker_username/your_repository_name:version
   ```

## Future improvements :bulb:

- [ ] Improve the design
- [ ] Add more features
- [ ] Add more tests
- [ ] Add more documentation

## Possible issues :x:

| Issue   | Solution                                                 |
| :------ | :------------------------------------------------------- |
| Issue 1 | Lorem ipsum dolor sit amet, consectetur adipiscing elit. |
| Issue 2 | Lorem ipsum dolor sit amet, consectetur adipiscing elit. |
