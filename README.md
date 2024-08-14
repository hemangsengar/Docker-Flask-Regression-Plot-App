

# Docker Flask Regression Plot App

![regress](https://github.com/user-attachments/assets/d5f543e3-1a02-4ce6-843b-028662ef1902)




## Overview

This project is a Flask web application that generates a regression plot using data from a CSV file. The application is containerized using Docker, making it easy to deploy and run in any environment.

## Features

- Interactive regression plot generated using Seaborn.
- Dockerized for easy deployment.
- Simple REST API to retrieve the plot.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **Seaborn**: A Python data visualization library based on Matplotlib.
- **Pandas**: A data manipulation and analysis library.
- **Docker**: A platform for developing, shipping, and running applications in containers.

## Installation

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.
- Basic knowledge of Python and Flask.

### Clone the Repository

```bash
  git clone https://github.com/hemangsengar/Docker-Flask-Regression-Plot-App.git
  cd Docker-Flask-Regression-Plot-App
```


```Build the Docker Image
docker build -t flask-regression-plot .
```
```Run the Docker Container
docker run -p 5000:5000 flask-regression-plot
```

