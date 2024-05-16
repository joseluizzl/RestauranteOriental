# Avaliação individual

Criei uma classe model chamada Pedido com os seguintes atributos: private Long id; private String pratos; private String clientes; private Double valor;
Criei uma classe PedidoController com o endpoint 

    1- Para obter todos basta apenas adicionar endpoint -> /pedidos
    2- Para obter pedido por id -> /pedidos/id
    3- Para salvar pedido -> /pedidos
    
          {
            "propriedade": "valor",
            "propriedade": "valor",
            "propriedade": valor
          }

    4- Para atualizar pedido -> /pedidos/id mais o corpo da requisição
    
          {
            "propriedade": "valor",
            "propriedade": "valor",
            "propriedade": valor
          }
          
    5- Para deletar um pedido -> /pedidos/id
    6- Para obter prato por início -> /pedidos/pratos
    7- Para obter Cliente pelo final -> /pedidos/clientes
