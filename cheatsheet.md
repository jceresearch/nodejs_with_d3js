
Tooling and build processes

Bundler: Parcel
    npm i -D parcel
    alternatively webpack

Linter: 
    ESLint extension, comes with VSCode but needs to make it active
    npm install -D eslint eslint-plugin-import eslint-config-prettier

Prettier
    npm i -D prettier
    Also install the extension in VSCode but needs to configure
    require configuration file
    
Editorconfig
    Create .editorconfig and install the extension in VScode
    Then put there a few recommended cross editor values

D3
    npm i -D d3
    D3 is a library for data visualization
    https://d3js.org/
    
Nodemon
    npm i -D nodemon
    Nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
    https://nodemon.io/
  
REST API dependencies:
  npm i -D  body-parser cors express helmet morgan
  https://hevodata.com/learn/building-a-secure-node-js-rest-api/



GPT
    npm i openai

dotenv
    npm i dotenv
    to inject environment variables into process.env
    needs a .env file in the root of the project with simple 
    KEY=VALUE pairs
    in particular for the openai key you need to create a .env file with
    OPENAI_API_KEY=sk-xxxxx
    and then in the code you can access it with
    process.env.OPENAI_API_KEY, though openai will do it for you
    if you have the key in the environment variable OPENAI_API_KEY
    
