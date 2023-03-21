#### PURGE ####

import requests

url = "https://api.gumlet.com/v1/purge/$PUT_DOMAIN_HERE"

headers = {
    "accept": "application/json",
    "content-type": "application/json",
    "Authorization": "Bearer $PUT_TOKEN_HERE"
}

response = requests.post(url, headers=headers)

print(response.text)