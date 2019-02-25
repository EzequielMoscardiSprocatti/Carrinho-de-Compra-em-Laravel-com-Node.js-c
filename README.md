# Carrinho-de-Compra-em-Laravel-com-Node.js

Descompactar o arquivo carrinhoDeCompras.rar em sua maquina e conectar ao banco de dados!

1- Após decompactado copie os arquvios do código e cole dentro do projeto.

2- Com os arquivos baixado no seu PC abra o arquivo do Banco de dados e informe o local onde se encontra seu banco:

3 - Neste arquivo ( Carrinho-de-Compra-Com-API-Node.js\config\database.php ) você informará os dados de sua conexão

# Make:Migrations

Neste ponto vamos criar as tabelas do banco de dados com a conexão feita só temos que efetuar o comando de make migrations dentro da pasta
do nosso projetos, abra o pront de comando, (Windows + R), use o comando cd.. e cd, para chegar até o diretório do arquivos exemplo : cd c:\user\projetos\carrinhodecompra

1 - Antes iniciar o projeto veja se o composer se encontra instalado em sua maquina. caso não esteja acesse esse link aqui:
https://getcomposer.org/download/ Instale em sua maquina de deixe como global caso sua maquina seja Ubunto!

2 - Agora no CMD digite a seguinte informação, abaixo:
 php artisan make:migrations create_users_table
 php artisan make:migrations create_password_resets_table
 php artisan make:migrations create_cupom_descontos_table
 php artisan make:migrations create_pedidos_table
 php artisan make:migrations create_pedido_produtos_table

3 - Pronto nossa tabelas estão prontas, mas isso foi feito simples, dentro do projeto já temos as tabelas mapeadas: 
Carrinho-de-Compra-Com-API-Node.js\app\CupomDesconto
Carrinho-de-Compra-Com-API-Node.js\app\Pedido
Carrinho-de-Compra-Com-API-Node.js\app\PedidoProduto
Carrinho-de-Compra-Com-API-Node.js\app\Produto
Carrinho-de-Compra-Com-API-Node.js\app\User



      

