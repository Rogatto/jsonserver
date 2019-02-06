# jsonserver

Precisamos instalar em nossa máquina:

Node: https://nodejs.org/en/download/
NPM: https://www.npmjs.com/
json-server: npm install -g json-server


para executar o json server via terminal e no diretorio do arquivo db.json:

json-server --watch db.json


para efetuar GET no endpoint do jsonserver ou qualquer outro método http:

Efetuar get no host que está no seu terminal (ex http://localhost:3000/suaapi)

Efetuar put exemplo:

curl -X PUT \
  http://localhost:3000/suaapi/1 \
  -H 'Content-Type: application/json' \
  -H 'Postman-Token: 344453fd-f0a2-4eed-b9b0-6ce668ce9ed7' \
  -H 'cache-control: no-cache' \
  -d '{
    "id": "1",
    "cpfusuario": "18262826051",    
    "issuercode": "855247",
}

