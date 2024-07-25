# My Node.js Application

This is a Node.js application designed to be deployed on an AWS EC2 instance.

## Features

- Express.js for handling HTTP requests
- Basic routing setup
- Ready for deployment on AWS EC2

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed (version 14.x or higher)
- npm (Node Package Manager)
- Git

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/gvjkumar2004/AWS_Deploy_Firstapp.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd AWS_Deploy_Firstapp
    ```

3. **Install the dependencies:**

    ```sh
    npm install
    ```

## Usage

1. **Run the application:**

    ```sh
    node server.js
    ```

2. **Open your browser and visit:**

    ```
    http://localhost:3000
    ```

## Deployment

### Deploying on AWS EC2

1. **Launch an EC2 instance:**

    - Choose an Amazon Machine Image (AMI), e.g., Ubuntu.
    - Choose an instance type, e.g., t2.micro.
    - Configure instance details and security groups (allow 
