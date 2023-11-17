# serverless-cd

15 Nov 2023: This repository is for  3.12 exercise.

1. Make the readme.
```
  git clone
  git add .
  git commit -m "commit message"
  git push

  ```

  2. To initialize node application.
  ```
  npm init (package.json)
  npm install serverless (package.json >> dependencies)
  npm install serverless-offline -- save-dev (package.json >> devDependencies)
  ```

  3. Add the following files.
  ```
  index.js
  serverless.yml
  .gitignore
  ```
  
  4. To start localhost:
  ```
  serverless offline start
  ```

  5. To deploy in AWS
  ```
  serverless deploy
  -> at AWS console>cloudformation>find the infrastructure
  -> at AWS lambda>functions>application name>configuration> triggers> api endpoint (can also refer to .code endpoint GET)
  ```

  6. serverless remove

  7. add github/workflows/main.yml

  
