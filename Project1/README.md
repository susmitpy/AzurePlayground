# Project 1

### Setup

1. Create a function app in the Azure portal
2. Be sure to select East US if on free trial as many other regions are not available for free trial
3. Test the code locally using the Azure Functions Core Tools
`func start` and then hit the api endpoint using curl or Postman (auth is not required)
4. Deploy the code to Azure using the Azure Functions Core Tools (As VS Code extension experiences sync issues sometimes)
`func azure functionapp publish <functionAppName>`
5. Open the function app in the Azure portal and navigate to the app keys. Copy the default key which is the function key. Pass the key in the header with the key as `x-functions-key`. 