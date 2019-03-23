
packages
npm install --save-dev @babel/core @babel/preset-env
npm install --save-dev webpack webpack-cli webpack-dev-server
npm install --save-dev babel-loader vue-loader vue-template-compiler
npm install --save-dev html-webpack-plugin
npm install --save vue

To verify the current configuration
npm install @babel/cli --no-save
To transpile test code
npx babel src/index.js --out-file dist/main.js
node dist/main.js

npm run build
npm run dev
