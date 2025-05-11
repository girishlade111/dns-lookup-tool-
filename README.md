# dns-lookup-tool-
dns-lookup-tool
How It Works:
When you enter a domain and click "Lookup":

The app validates the domain format
Makes a request to Google's DNS API
Processes the response to extract DNS records
Displays them in a formatted table
The API endpoint:

Is publicly available (no API key needed)
Supports all standard DNS record types
Returns JSON data that's easy to parse
The UI:

Shows loading state during API calls
Displays errors if they occur
Formats the DNS records clearly
This version should work without any dependency issues while providing real DNS lookup functionality.
