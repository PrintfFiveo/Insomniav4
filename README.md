# Insomniav4 SIMULADO-AULA-AOS
cria usuarios para a api 
aqui criei um usuario com meu nome e email,isto é um post

base url :`https://api.pagar.me/core/v5/`

endpoint : `customers`

body: 
{ 

     "name": "vitor",


    "email": "vitor.tavares.leite@gmail.com",
	
	"birthdate": "11/09/2001",
	
	
     "phone": {}
 
}



## end point =  `"/orders"`
## baseurl = `"https://api.pagar.me/core/v5/"`
este endpoint lista todos os pedidos


##
`Este Get pede para listar os usuarios castrados`


endpoint : `customers`este endpoint ve os usuários/clientes

Baseurl :`
https://api.pagar.me/core/v5/`
alguns parametros podem ser o tamanho da pagina/paginas

url `   --request GET \
       --url 'https://api.pagar.me/core/v5/customers' \
       --header 'accept: application/json'` 

