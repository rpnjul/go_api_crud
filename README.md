# First GO Project API CRUD

## GET ALL PRODUCT 
```url
GET http://127.0.0.1:9999/api/products
```

## CREATE NEW PRODUCT 
```url
http://127.0.0.1:9999/api/products
```
JSON DATA
```json
{
	"code" : "product_code",
	"name" : "product_name",
	"price"	: product_price,
	"deskripsi" : "product_description"
}
```
## FIND PRODUCT BY ID
```url
http://127.0.0.1:9999/api/products/2
```
## UPDATE PRODUCT
```url
http://127.0.0.1:9999/api/products/{id}
```
JSON DATA
```json
{
	"code" : "product_code",
	"name" : "product_name",
	"price"	: product_price,
	"deskripsi" : "product_description"
}
```
## DELETE PRODUCT BY ID
```url
http://127.0.0.1:9999/api/products/2
```

