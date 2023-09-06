
import requests

# Make a request to the AviationStack API to get airline data
api_key = 'your_api_key_here'
url = 'http://api.aviationstack.com/v1/airlines'
params = {'access_key': api_key}

response = requests.get(url, params=params)
data = response.json()

# Process the data as needed
