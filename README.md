# FinSavior

FinSavior é uma aplicação de organização financeira com insights e assistente de inteligência artifical (AI) powered by OpenAI, vai ser seu conselheiro no mundo financeiro, se aprimorando continuamente pra te ajudar com suas finanças. Desenvolvida com Angular, Spring Boot, Grpc, Protobuf, Kafka, Schema Registry, etc. Ela permite aos usuários registrar suas receitas, despesas e metas financeiras, fornecendo uma visão clara e detalhada de suas finanças pessoais.

O projeto está dividido em várias partes:

- [Frontend](https://github.com/Hachibitz/finsavior-front): Contém o código-fonte do frontend da aplicação, desenvolvido com Angular 16 e Node 18. Consulte o README do frontend para obter instruções sobre como configurar e executar o frontend localmente.

- [Backend](https://github.com/Hachibitz/finsavior-back): Contém o código-fonte do backend da aplicação, desenvolvido com Spring Boot. Consulte o README do backend para obter instruções sobre como configurar e executar o backend localmente.

- [GrpcServices](https://github.com/Hachibitz/grpc-finsavior-services): Contém o código-fonte de serviços acessíveis ao backend, desenvolvido com Spring Boot/Grpc/protobuf. Consulte o README do GrpcServices para obter instruções sobre como configurar e executar o serviço localmente.

- [EventsProcessor](https://github.com/Hachibitz/finsavior-events-processor): Contém o código-fonte do consumidor da fila kafka de serviços que utilizam o recurso, desenvolvido com Spring Boot/Schema Registry/Kafka. Consulte o README do EventsProcessor para obter instruções sobre como configurar e executar localmente.

- [ConfigServer](https://github.com/Hachibitz/finsavior-config-server): Responsável pela busca de properties do servidor de cada ambiente na cloud.

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Autor: [Hachibitz]
- E-mail: [felipealmeida.ns@outlook.com]
- GitHub: [Hachibitz](https://github.com/Hachibitz)

Espero que este README seja útil e forneça informações claras sobre o projeto FinSavior. Se você tiver mais perguntas, sinta-se à vontade para perguntar.
