# FinSavior

FinSavior é uma aplicação de organização financeira desenvolvida com Angular, Spring Boot, Grpc, Protobuf, Kafka, Schema Registry, etc. Ela permite aos usuários registrar suas receitas, despesas e metas financeiras, fornecendo uma visão clara e detalhada de suas finanças pessoais.

O projeto está dividido em duas partes:

- [Frontend](https://github.com/Hachibitz/finsavior-front): Contém o código-fonte do frontend da aplicação, desenvolvido com Angular 16 e Node 18. Consulte o README do frontend para obter instruções sobre como configurar e executar o frontend localmente.

- [Backend](https://github.com/Hachibitz/finsavior-back): Contém o código-fonte do backend da aplicação, desenvolvido com Spring Boot. Consulte o README do backend para obter instruções sobre como configurar e executar o backend localmente.

- [GrpcServices](https://github.com/Hachibitz/grpc-finsavior-services): Contém o código-fonte de serviços acessíveis ao backend, desenvolvido com Spring Boot/Grpc/protobuf. Consulte o README do GrpcServices para obter instruções sobre como configurar e executar o serviço localmente.

- [EventsProcessor](https://github.com/Hachibitz/finsavior-events-processor): Contém o código-fonte do consumidor da fila kafka de serviços que utilizam o recurso, desenvolvido com Spring Boot/Schema Registry/Kafka. Consulte o README do EventsProcessor para obter instruções sobre como configurar e executar localmente.

## Funcionalidades/Metas a atingir

- Registro de receitas e despesas
- Categorização de transações financeiras
- Acompanhamento do saldo atual
- Definição de metas financeiras
- Geração de relatórios e gráficos
- Autenticação e autorização de usuários

## Pré-requisitos

Certifique-se de ter os seguintes requisitos antes de começar:

- Node.js 18 ou superior
- Java JDK 8 ou superior
- Maven
- Banco de dados SQL
- Kafka/SchemaRegistry

## Instalação e Execução

Siga as instruções abaixo para configurar e executar o projeto FinSavior:

1. Clone este repositório:

shell
git clone https://github.com/Hachibitz/FinSavior.git

2. Configuração do Backend

Consulte o [README do backend](https://github.com/Hachibitz/finsavior-back#readme) para obter instruções sobre como configurar e iniciar o servidor.

3. Configuração do Frontend

Consulte o [README do frontend](https://github.com/Hachibitz/finsavior-front#readme) para obter instruções sobre como configurar e executar o frontend localmente.

## Contribuição

Contribuições são bem-vindas! Se você quiser contribuir com o projeto, siga as etapas abaixo:

1. Fork o projeto
2. Crie sua branch de recurso (`git checkout -b feature/MyFeature`)
3. Commit suas alterações (`git commit -am 'Add some feature'`)
4. Push para a branch (`git push origin feature/MyFeature`)
5. Abra um Pull Request

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Autor: [Hachibitz]
- E-mail: [felipealmeida.ns@outlook.com]
- GitHub: [Hachibitz](https://github.com/Hachibitz)

Espero que este README seja útil e forneça informações claras sobre o projeto FinSavior. Se você tiver mais perguntas, sinta-se à vontade para perguntar.
