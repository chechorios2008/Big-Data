# Para conectarme al shell de Mongo desde un contenedor de Docker. 
'''
docker-compose exec mongodb bash
'''

# Conectar con mongoSH
'''sh
mongosh "mongodb://chechorios2008:ZTOxIVKaos3w9n9T@localhost:27017/?tls=false"
'''

'''sh
show dbs
show collections
'''

'''sh
user("Agaval")
db.productos.find()
'''