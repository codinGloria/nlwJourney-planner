<h1 align="center"> Projeto Plann.er ✍🏾 - STAND BY </h1>
Plataforma: Rocketseat - Feito com React e Java.

# Sobre o projeto

O projeto Journey tem como objetivo ajudar o usuário a organizar viagens à trabalho ou lazer. O usuário pode criar uma viagem com nome, data de início e fim. Dentro da viagem o usuário pode planejar sua viagem adicionando atividades para realizar em cada dia.

# Requisitos

1. O usuário cadastra uma viagem informando o local de destino, data de início, data de término, e-mails dos convidados e também seu nome completo e endereço de e-mail;
2. O criador da viagem recebe um e-mail para confirmar a nova viagem através de um link. Ao clicar no link, a viagem é confirmada, os convidados recebem e-mails de confirmação de presença e o criador é redirecionado para a página da viagem;
3. Os convidados, ao clicarem no link de confirmação de presença, são redirecionados para a aplicação onde devem inserir seu nome (além do e-mail que já estará preenchido) e então estarão confirmados na viagem;
4. Na página do evento, os participantes da viagem podem adicionar links importantes da viagem como reserva do AirBnB, locais para serem visitados, etc...
5. Ainda na página do evento, o criador e os convidados podem adicionar atividades que irão ocorrer durante a viagem com título, data e horário;
6. Novos participantes podem ser convidados dentro da página do evento através do e-mail e assim devem passar pelo fluxo de confirmação como qualquer outro convidado

### Terminais de API

A API fornece os seguintes endpoints:

- POST /trips - Cadastrar uma viagem 
- GET /trips/{tripId} - Consulta de viagem 
- PUT /trips/{tripId} - Atualização de viagem 
- GET /trips/{tripId}/confirm - Confirmação de viagem 
- POST /participants/{participantId}/confirm - Confirmação de participante 
- POST /trips/{tripId}/invites - Convidar participante 
- GET /trips/{tripId}/participants - Consultar participantes 
- POST /trips/{tripId}/activities - Cadastro de atividade 
- GET /trips/{tripId}/invites - Consultar atividades de uma viagem 
- POST /trips/{tripId}/links - Criação de link 
- GET /trips/{tripId}/links - Consultar links de uma viagem 

## STANDY BY REASON
  O projeto foi colocado em stand by pelos seguintes motivos:
  
- Tudo que foi passado durante a NLW está feito, portanto, pretendo adicionar mais algumas funcionalidades por conta própria.
- O sistema parece meio incompleto, já que faço as requisições POST por Insomnia/Postman.
- Funcionalidades que serão adicionadas:
  - Validação de dados (campos de datas);
  - Mapeamento das exceções, com tratativas de erro personalizadas.

## Tecnologias

- Java 21
- Spring Boot
- H2 Database
- Insomnia
- React
