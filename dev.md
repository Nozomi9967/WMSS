goctl api go -api product/api/product.api -dir product/api/
goctl api plugin -plugin goctl-swagger="swagger -filename product.json -host localhost:8888 -basepath /" -api product.api -dir .
