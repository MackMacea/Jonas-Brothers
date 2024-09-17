# REQUISITOS DO SISTEMA 1 ( referente ao atendimento ao cliente)

## Requisitos Funcionais:
### Consumidor
-> Area de login e senha/cadastro pro usuario<br>
-> receber o endereço do usuario <br>
-> oferecer uma area de compras ao cliente <br>
-> o aplicativo deve enviar a solicitação para o sistema de fabrica e receber a resposta do mesmo <br>
-> o aplicativo deve informar o tempo medio de entrega<br>
-> se o pedido for confirmado pelo cliente o app deve oferecer opção de pagamento via o app /ou quando o pedido chegar <br>
-> ao app deve mostrar um menu atualizado em tempo real com o status de seu pedido <br>
-> ao pedido sair para entrega o app devera mostrar a rota do entregador para o cliente junto a uma previsão de chegada<br>
-> o app ira gerar um token de 4 numeros para o cliente assegurar o pedido com o entregador.<br>
-> o app deve enviar a confirmação de do codigo de entrega para o sistema.<br>
-> o app deve ter uma area de contato para suporte<br>
### Pizzaria
-> o app deve permitir a pizzaria alterar o cardapio<br>
-> o app deve permitir a pizzaria fechar e abrir lojas<br>
-> o sistema deve enviar a loja escolhida o endereço, pedido e metodo de pagamento<br>
### Entregador
-> o app deve possuir um sistema de gps para o entregador<br>
-> o app na area do entregador deve receber o codigo para conseguir finalizar o pedido.<br>

## Requisitos não Funcionais:
-> o sistema deve garantir a criptografia dos dados do cliente<br>
-> de acordo com a LGPD<br>
-> tempo de resposta moderado<br>
->deve ser capaz de atender a demanda da area de cobertura das pizzarias.<br>


# Requisitos do sistema 2 (referente as fabricas)

## Requisitos funcionais:
-> o sistema deve receber as fabricas da franquia <br>
-> o sistema deve receber a solicitação de pedido do app<br>
-> o sistema vai avaliar qual fabrica cadstrada possui o menor tempo de entrega possivel <br>
-> o sistema vai devolver a solicitação para o app<br>
-> o sistema vai enviar a demanda para a fabrcia designada<br>
-> o sistema só encerra o pedido após receber a confirmação do codigo de entrega<br>

## Requisitos não funcionais:
-> o sistema deve ser capaz de atender a demanda de todas as fabricas cadastradas<br>
-> o sistema deve garantir um tempo de resposta baixo<br>
-> o sistema deve possuir alta disponibilidade<br>
-> o sistema deve garantir sua segurança <br>
-> legislação(LGPD e leis correlatas) <br>

