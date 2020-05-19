Creating a frontend app using serverless and react.

#### Prerequisites:
1. Node.js: https://nodejs.org/en/download/package-manager/
1. Serverless: `npm i -g serverless`
4. Parcel: `npm install -g parcel-bundler`

In the process I executed the following commands:

#### Setup
1. `serverless create --template-url https://github.com/serverless/components/tree/master/templates/website`

2. Updated `.env` as per my aws configs

3. `npm run start` -> visit http://localhost:1234/

#### Development & deployment
`$ serverless`



Ref: https://www.serverless.com/learn/tutorial/deploying-react-website-on-aws/