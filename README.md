# Blog API

- Front:
    - Obtener todas las publicaciones
    - Obtener una en especifico
    - Obtener todas las categorias
    - Obtener una categoria 
    - Obtener las publicaciones filtradas por categoria
    - Obtener todas mis publicaciones
    - Obtener todos las publicaciones de un usuario en especifico
    - Paginar los post
    - Acciones de CRUD sobre la publicacion
    - Crear CRUD sobre las categorias

```json
    {
        "total": 68,
        "prev": "localhost:9000/api/v1/posts?start=51&limit=60",
        "next": "localhost:9000/api/v1/posts?start=61&limit=68",
        "data": [
            {
             "id": "45fbjh-nej-5293-wjndedw00213",
             "title": "ejemplo",
             "content" : "lorem ipsum",
             "createdBy" : {
                "id": "27",
                "name": "Alejandro",
                "email": "Hola@gmail.com"
             },
             "category": {
                "id": "4",
                "name": "Tecnología"
             }  
            }
        ]
    }
```

