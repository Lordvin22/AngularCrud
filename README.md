AngularCrud

para consultar
https://angularphpcrud.000webhostapp.com/api/controllers/get_list.php
{
    "data": [
        {
            "id": "47",
            "name": "xiaomi",
            "description": "redmi note 8",
            "stock": "10000",
            "price": "10"
        },
        {
            "id": "48",
            "name": "Nokia",
            "description": "8",
            "stock": "4997",
            "price": "10"
        },
    ],
    "query": "SELECT * FROM product",
    "message": "Product saved succesfully",
    "message_type": "success"
}
Para insertar
https://angularphpcrud.000webhostapp.com/api/controllers/save_product.php

para borrar
https://angularphpcrud.000webhostapp.com/api/controllers/delete_product.php

{
    "query": "DELETE FROM product WHERE id = '58'",
    "message": "Product deleted succesfully",
    "message_type": "success"
}

para obtener la lista de productos comprados
https://angularphpcrud.000webhostapp.com/api/controllers/get_list_purchase.php

para actualizar
https://angularphpcrud.000webhostapp.com/api/controllers/update_product.php
{
    "data": {
        "id": 0,
        "name": "apple",
        "description": "gre",
        "stock": "10",
        "price": "10"
    },
    "query": "UPDATE product set name = 'apple' , description = 'gre', stock = '10', price = '10' WHERE id = '9' ",
    "message": "Product update succesfully",
    "message_type": "success"
}


