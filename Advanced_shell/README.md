# API Request Automation
### Objective: Automate the process of making API requests to the Pokémon API and saving the results to a file
## Task 0
## filepath: Advanced_shell/apiAutomation-0x00

### <code>curl</code> - command is used to make the HTTP request
### <code>-sf</code> -  flag runs curl in silent mode to suppress progress meters and status messages, while <code>-f</code> flag makes curl exit with a non-zero status code if the HTTP server returns an error (400 or higher), which is crucial for our error handling.

# Extract Pokémon Data
### Objective: Use advanced text manipulation tools (jq, awk, sed) to extract specific data from the API response.
## Task 1 
## filepath: Advanced_shell/data_extraction_automation-0x01
### <code>jq --raw-output</code> This flag ensures that jq prints the final output without any extra quotes, making it a clean string.