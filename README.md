# lambda-template

- new folder
- open in cmd
- serverless create -t aws-nodejs
- rename service

- configure function and events
- configure .yaml with DB info
- give access to serverless with credentials (IAM user) if not already set ->
- serverless config credentials --provider aws --key KEYHERE --secret SECRETHERE
- cat ~/.aws/credentials will show them if needed
- serverless deploy
- copy endpoint and bookmark if you want
- if you try to deplay and get error for path then delete some part of path, deploy and add new path then deploy again
