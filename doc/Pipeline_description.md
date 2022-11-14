# Pipeline description

Firstly: Push the updated code to Github  
Merge the code to main branch

CircleCI grab the code and run following process to deploy it to AWS

Then Install node.js 14.15  

Then Install Front-End Dependencies  
By `npm run install` on FE directory  

Then Install Back-End Dependencies  
By `npm run install` on BE directory  

Then Linting Front-End project  
By `ng lint` on FE directory  

Then Build Front-End project  
By `npm run build` on FE directory  

Then Build Back-End project  
By `npm run build` on BE directory  

On hold to wait a manual approve to deploy

Then Deploy App  
By `npm run deploy` on BE directory  
By `npm run deploy` on FE directory  