# express-ts-setup-bash
# Express with TypeScript Server Generator

This repository contains a Bash script that generates a basic Express server with TypeScript, along with all the necessary libraries installed.

## Prerequisites

To use this script, ensure that you have the following prerequisites installed on your system:

- Node.js (version >= 14.x)
- npm (Node Package Manager)

## Getting Started

1. Create your project directory ( if not done so ) and move inside it:
   ```bash
   mkdir your_project_folder
   cd your_project_folder

2. Run the below script to generate the Express server:

   ```bash
   curl -fsSL https://abhishek-k-s.github.io/express-ts-setup-bash/setup.sh | sh
   ```
   Wait for the packages to download.

3. Voila!! Now the server is ready to start and code. To start the server, run the following code

   ```bash
   npm run dev

##Note
1. If the working directory already has a tscofig.json file, then it will be deleted and a new one is created.
2. If package.json, package-lock.json, .env or index.ts file/files already exists inside the project directory, then those files are overwritten and previous data will be lost.
3. "dist" folder contains all transpiled files aka JS files. Do not modify them.