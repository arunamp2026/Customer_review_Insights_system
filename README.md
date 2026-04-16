Follow the steps below to start a self-hosted N8N instance on GitHub Codespaces: 
● Go to GitHub and login: https://github.com/  
● Access GitHub Codespaces by going to this page: https://github.com/codespaces  
● create a code repository and Start a codespace from the github Repository
https://github.com/arunamp2026/Customer_review_Insights_system
Your Codespace should be created. 
1.To install n8n globally, use the below command in the Terminal: 
`npm install n8n -g`
2.Go to the Ports tab, showing beside the Terminal tab, then forward the port number 
5678.  
3. Change the Port Visibility to Public by doing right click >> Port Visibility >> Public  
4. Create source .env file and Copy the Forwarded Address to be provided in the .env file.  
5. After that, load the environment variables and start n8n by running the below 2 
commands in the Terminal: 
`source .env`
6. start the n8n environment
`n8n start`
7.https://psychic-memory-69jr6qvp77vqfr4vp-5678.app.github.dev/



