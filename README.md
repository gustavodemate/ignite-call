![image](https://user-images.githubusercontent.com/107967510/218321398-5247000a-0680-4636-915f-b633d52e672d.png)

Esse projeto foi desenvolvido com as seguintes tecnologias:

React, 
Next.js, 
Typescript, 
Node.js, 
Prisma.io, 
Google APIs, 
Google Cloud Platform, 
Docker, 
Axios, 
Next Seo, 
Nookies, 
React Hook Form, 
Design System, 
Stitches (CSS-in-JS), 
Phosphor icons, 
ESLint, 
Date-fns, 
Zod, 
bookmark Projeto.

O projeto Ignite Call foi construído para agendamentos de compromissos a partir de um calendário com integração com o Google Agenda. O usuário pode se cadastrar no app a partir de sua conta do Google e indicar seus dias da semana e horários em que estará disponível para agendar compromissos. Todo agendamento cadastrado na aplicação tem integração com o Google Agenda, o qeu possibilita ao usuário verificar seus novos compromissos direto na plataforma do Google.

O Ignite Call foi construído inteiramente em um projeto Next.js e utilizado os mecanismos fornecidos pelo framework para criação e integração do front-end e do back-end a partir de um único repositório de código. A comunicação da aplicação com o banco de dados foi feita com o uso da ferramenta Prisma.io e utilizado um banco de dados MySQL em um container Docker. O banco de dados de produção foi publicado a partir do serviço da plataforma PlanetScale e foi utilizado o serviço da Vercel para hospedagem da aplicação.

Para rodar a aplicação será necessária a conexão com um banco de dados local ou container Docker e integrado com a ferramenta Prisma.io. Além da criação do projeto no Google Cloud Platform para coletar as credenciais necessárias para login e integração com a plataforma Google que constam no arquivo .env.example. Este arquivo também contém a URL de conexão que deverá ser utilizada para a conexão do Prisma com o banco de dados.

