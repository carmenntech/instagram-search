Uso de la api no oficial de instagram para realizar busquedas de post, perfiles... Para la documentación de la misma -> https://github.com/subzeroid/instagrapi
 
# Instalación 

Python >= 3.9 required

Para instalar la libreria linkedin_api, usa el siguiente comando:

``pip install instagrapi``


# Primeros pasos

```
from instagrapi import Client

cl = Client()
cl.login(ACCOUNT_USERNAME, ACCOUNT_PASSWORD)

user_id = cl.user_id_from_username(ACCOUNT_USERNAME)
medias = cl.user_medias(user_id, 20)
```
