# semana18mobile.


aula 1

1. Qual a importância de autenticar uma API corretamente em uma integração com serviços externos? 

R: É importante para deixar os dados seguros e permitir que somente pessoas ou aplicativos autorizados usem a API.

2. Por que é essencial compreender o formato de resposta de uma API antes de consumi-la?

R: Porque precisamos saber como os dados estão organizados para conseguir usar as informações no aplicativo. Um formato muito usado é o JSON.

3. Quais estratégias podem ser usadas para tratar erros ao consumir dados de API?

R: Podemos verificar a conexão, conferir se a chave da API está correta e mostrar uma mensagem quando acontecer algum erro.

4. Como vocês aplicariam o conceito de “tratamento de erros” no cenário apresentado?

R: Se a API do clima não funcionar ou a chave estiver errada, o aplicativo pode mostrar uma mensagem dizendo que não foi possível carregar a previsão do tempo.

fonte: MDN Web Docs – Mozilla

aula 2

1. Qual é o principal benefício de usar BaaS em um aplicativo como o Foodly?

R: O principal benefício é facilitar o desenvolvimento do aplicativo, pois o BaaS já oferece recursos prontos como login, banco de dados e notificações. Assim, a equipe economiza tempo.

2. Como o Firebase ajuda na implementação de notificações em tempo real?

R: O Firebase permite enviar notificações para os usuários em tempo real. Com o Firebase Cloud Messaging é possível avisar sobre pedidos, promoções ou outras informações do aplicativo.

3. Quais riscos podem estar associados ao uso de um BaaS?

R: Alguns riscos são depender do serviço de outra empresa, ter problemas de segurança ou privacidade dos dados e também ficar limitado aos recursos oferecidos pela plataforma.

4. Como a Foodly poderia lidar com esses desafios?

R: A Foodly pode proteger bem os dados dos usuários, usar senhas e permissões de acesso seguras e fazer backups. Também é importante conhecer as regras e limitações do Firebase para evitar problemas.

aula 3

1. Qual a principal vantagem de usar serviços de mensageria em aplicativos mobile?

R: A principal vantagem é conseguir enviar informações para o usuário de forma rápida, como avisos, atualizações e notificações sobre o aplicativo.

2. Por que o gerenciamento de filas é importante em serviços como RabbitMQ?

R: Porque as filas organizam as mensagens e evitam que elas sejam perdidas ou processadas todas de uma vez. Assim, os serviços conseguem trabalhar de forma mais organizada.

3. Quais tipos de mensagens o ShopTrack poderia enviar para melhorar a experiência do cliente?

R: Poderia enviar mensagens sobre confirmação do pedido, pagamento aprovado, pedido enviado, previsão de entrega e promoções.

4. Como lidar com falhas na entrega de mensagens em serviços de mensageria?

R: É possível tentar enviar a mensagem novamente, guardar as mensagens que deram erro e verificar o motivo da falha. Assim, diminui a chance de perder informações importantes.
