# python-simple-google-maps
##### v0.0.2

### Installation :
`pip install python-simple-google-maps==0.0.2`  

### Requirements :
```
python3
urllib3
```

### Usage / Example :

```python
from simple_google_maps import get_google_map_url

data = {
  'address': 'Auckland',
  'sizes': (1200, 800),
  'GOOGLE_MAPS_API_KEY': 'AIzaSyAofozPey7CK3iThCxs0-1bdTdVly1QBGw',
  'GOOGLE_MAPS_SECRET_KEY': '76XgR6vY7puGmmytCWb-t6uC18E='
}

get_google_map_url(**data)

# 'https://maps.googleapis.com/maps/api/staticmap?center=Auckland&markers=color:red|Auckland&size=1200x800&key=AIzaSyAofozPey7CK3iThCxs0-1bdTdVly1QBGw&signature=29Sb4lQDjByRSIaAmkqYp4njHWk='


```  

Enjoy :)  

###### Support / Contact : remaudcorentin.dev@gmail.com

