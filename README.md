# Site para Escola de Forró

## Descrição

Este é um projeto de site para uma escola de forró que complementa a presença no Instagram, oferecendo informações organizadas sobre aulas, professores e inscrições. O objetivo é fornecer uma plataforma acessível, responsiva e com funcionalidades de gestão de alunos.

## Tecnologias Utilizadas

- **Frontend**: React.js
- **Backend**: Node.js com Express
- **Banco de Dados**: PostgreSQL
- **Gerenciamento de Estado**: Context API ou Redux (a definir)
- **Autenticação**: JWT (JSON Web Token)
- **Notificações**: Nodemailer (para envio de notificações por e-mail)
- **Hospedagem**: A definir (ex: Vercel, Render, Heroku)

## Funcionalidades

- **Home**: Página inicial com informações sobre a escola e chamada para inscrições.
- **Sobre a Escola**: Descrição da escola e diferenciais.
- **Aulas**: Horários e locais das aulas, incluindo mapa do Google.
- **Professores**: Fotos e mini-bios dos professores.
- **Inscrição e Contato**: Formulário de inscrição e canais de contato.
- **Área Administrativa**: Painel para administradores visualizarem inscrições e notificações por e-mail.
- **Blog (Opcional)**: Seção com dicas de forró e artigos de interesse.

Estrutura do Projeto
Frontend

    Páginas:

        /: Página inicial.

        /sobre: Página sobre a escola.

        /aulas: Página com horários e locais das aulas.

        /professores: Página com informações dos professores.

        /inscricao: Página de formulário de inscrição.

    Componentes:

        Navbar: Navegação do site.

        Footer: Rodapé com informações adicionais.

Backend

    API Endpoints:

        GET /api/aulas: Retorna os horários e locais das aulas.

        POST /api/inscricao: Recebe os dados de inscrição de novos alunos.

        GET /api/professores: Retorna a lista de professores.

    Banco de Dados:

        Tabelas: aulas, inscricoes, professores.

Como Contribuir

    Faça um fork deste repositório.

    Crie uma branch para a sua feature:

    git checkout -b minha-feature

    Faça suas alterações.

    Envie um pull request.
