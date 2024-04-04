# Function Frontend Task

## Overview

A simple fullstack dapp that shows how a frontend interacts with a smart contract.

## Prequisite

1. Install [Node.js](https://nodejs.org)

   Download and install from the official site.

## Local Setup & Initialization

1. Clone Repository into your local terminal

   ```bash
   git clone https://github.com/PhantomOz/FFT.git
   cd FFT
   ```

2. install the node libraries

   ```bash
   npm install
   ```

3. Open two additional terminals in your VS code
4. In the second terminal type:

   ```bash
   npx hardhat node
   ```

5. In the third terminal, type:

   ```bash
   npx hardhat run --network localhost scripts/deploy.js
   ```

6. Back in the first terminal, type:
   ```bash
   npm run dev to launch the front-end.
   ```

After this, the project will be running on your localhost.
Typically at http://localhost:3000/
