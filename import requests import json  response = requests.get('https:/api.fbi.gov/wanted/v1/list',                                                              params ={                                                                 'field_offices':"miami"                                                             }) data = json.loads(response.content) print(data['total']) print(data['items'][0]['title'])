import requests
import json

response = requests.get('https://api.fbi.gov/wanted/v1/list',

                                                            params ={
                                                                'field_offices':"miami"
                                                            })
data = json.loads(response.content)
print(data['total'])
print(data['items'][0]['title'])
