# API Request Automation
### Objective: Automate the process of making API requests to the Pokémon API and saving the results to a file
## Task filepath: Advanced_shell/apiAutomation-0x00

## Explaining Keywords Used  
### <code>curl</code> - command is used to make the HTTP request
### <code>-sf</code> -  flag runs curl in silent mode to suppress progress meters and status messages, while <code>-f</code> flag makes curl exit with a non-zero status code if the HTTP server returns an error (400 or higher), which is crucial for our error handling.

