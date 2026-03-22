# Getting Started with Bitcoin P2P Mutation Lab

This guide provides the necessary steps to set up, deploy, and troubleshoot the Bitcoin P2P Mutation Lab.

## Prerequisites
- Ensure you have the following software installed:
  - [Node.js](https://nodejs.org/) (v14 or higher)
  - [Git](https://git-scm.com/)
  - [Docker](https://www.docker.com/) (optional for containerized setups)

## Installation Steps
1. **Clone the Repository**:  
   Open your terminal or command prompt and run:
   ```bash
   git clone https://github.com/ViniMF13/bitcoin-p2p-mutation-lab.git
   cd bitcoin-p2p-mutation-lab
   ```

2. **Install Dependencies**:  
   If you're using Node.js, run:
   ```bash
   npm install
   ```

   If you are using Docker, you can build the image with:
   ```bash
   docker build -t bitcoin-p2p-lab .
   ```

## Deployment
To deploy the application, simply run:
```bash
npm start
```
This will start the server and you should see output indicating the server is running.

## Running Scenarios
1. **Testing the Setup**:
   Open your browser and navigate to `http://localhost:3000` to see the application in action.

2. **Simulating P2P Transactions**:
   Follow the steps in the `/scenarios` directory to run various transaction scenarios.

## Troubleshooting
- **If the server fails to start**: Ensure all dependencies are installed correctly and your Node.js version is compatible.
- **Connection Issues**: Check your firewall and ensure necessary ports are open.
- **Logs**: Check the log output for any errors and consult the documentation for further guidance.