# DEDUCE Starter

## Description
DEDUCE Starter is a tool designed to help non-developers get started with the DEDUCE project. The repository contains a Docker Compose file and a Jupyter notebook that leverages the DEDUCE de-identification method for Dutch medical text. This setup simplifies the process of running and exploring the DEDUCE tool in a local environment.

## Instructions

1. **Install Docker**  
   Download and install Docker Desktop from [Docker's official website](https://www.docker.com/products/docker-desktop/).

2. **Clone or Download the Repository**  
   Clone this repository or [download](https://github.com/putssander/deduce-starter/archive/refs/heads/main.zip) it to your local machine.

3. **Start the Application**  
   Open your terminal, navigate to the directory containing the repository, and start the application by running the command:
   ```sh
   docker-compose up
   ```

4. **Access the Application**  
   Open your web browser and go to [http://localhost:10000](http://localhost:10000).

5. **Retrieve the Token**  
   Find the access token in your terminal output. This token is needed to access the notebook.

6. **Open the Notebook**  
   Locate the notebook by navigating to [deduce-xlsx.ipynb](http://localhost:10000/lab/tree/work/deduce-xlsx.ipynb) in your web browser and continue your work there.

This setup will guide you through setting up and accessing a DEDUCE notebook environment.