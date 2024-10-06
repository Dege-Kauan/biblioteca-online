# Sistema de Gerenciamento de Biblioteca Online

## Descrição do Projeto

O **Sistema de Gerenciamento de Biblioteca Online** é uma aplicação projetada para facilitar o gerenciamento e a organização de uma biblioteca digital. O sistema permite que os usuários pesquisem, reservem e emprestem livros de forma eficiente. A aplicação é composta por três camadas principais: **Frontend**, **Backend** e **Banco de Dados**, cada uma desempenhando um papel fundamental na funcionalidade do sistema.

Este projeto tem como objetivo implementar uma solução completa para a gestão de bibliotecas, incluindo recursos como autenticação de usuários, catalogação de livros e controle de empréstimos. Além disso, o sistema é desenvolvido com a intenção de ser escalável e fácil de manter, utilizando práticas recomendadas em arquitetura de software.

## Objetivos do Sistema

- **Facilitar a busca por livros**: Permitir que os usuários encontrem rapidamente os livros disponíveis na biblioteca.
- **Gerenciar reservas e empréstimos**: Oferecer um sistema para reservar e emprestar livros de forma eficiente, evitando conflitos e garantindo que os usuários possam acessar os livros desejados.
- **Autenticação de usuários**: Implementar um sistema seguro de autenticação que proteja as informações dos usuários e permita acesso personalizado.

## Diagramas UML

Para melhor compreensão da arquitetura do sistema, foram elaborados três diagramas UML:

1. **Diagrama de Arquitetura da Aplicação**:
   - Este diagrama ilustra os componentes principais do sistema, incluindo o **Frontend**, que é a interface com o usuário; o **Backend**, que gerencia a lógica de negócio e as interações com o banco de dados; a **Autenticação**, que lida com o registro e login de usuários; e o **Banco de Dados**, que armazena todas as informações do sistema. Os componentes estão conectados para mostrar a interação entre eles.

2. **Diagrama de Arquitetura de Implantação**:
   - O diagrama de implantação descreve a configuração física do sistema, incluindo os servidores onde a aplicação e o banco de dados estão hospedados. Esse diagrama é crucial para entender como o sistema é distribuído em uma infraestrutura de nuvem, garantindo alta disponibilidade e escalabilidade.

3. **Diagrama de Arquitetura DevOps**:
   - O diagrama DevOps apresenta o pipeline de integração contínua e entrega contínua (CI/CD) utilizado para automatizar o processo de desenvolvimento, teste e implantação da aplicação. Esse diagrama ilustra as ferramentas e práticas que garantem um fluxo de trabalho ágil e eficiente, integrando ferramentas como **GitHub Actions**, **Jenkins** e **Docker**.

## Infraestrutura e Ativação de Usuários

O sistema seria hospedado na **Amazon Web Services (AWS)**, que oferece uma plataforma robusta e escalável para aplicativos web. A arquitetura seria composta por:

- **EC2 (Elastic Compute Cloud)**: Para hospedar a aplicação Backend, permitindo que os desenvolvedores escalem rapidamente a capacidade do servidor de acordo com a demanda.
- **RDS (Relational Database Service)**: Para gerenciar o banco de dados de forma confiável e segura, garantindo que os dados dos usuários e livros estejam sempre disponíveis.
- **CloudFront**: Para distribuição de conteúdo estático do Frontend, garantindo um carregamento rápido e eficiente da interface do usuário.

Além disso, seria utilizado o **AWS Cognito** para gerenciar a autenticação dos usuários, fornecendo uma solução segura e escalável para registro, login e gerenciamento de sessões.

## Palavras-chave

UML, Diagrama de Componentes, Diagrama de Implantação, DevOps, AWS, Biblioteca Online, CI/CD, Gerenciamento de Usuários, Arquitetura de Software, Desenvolvimento Web.
