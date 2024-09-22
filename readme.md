# App

GymPass style app.

## RFs (Requisitos Funcionais)
[] Deve ser possível se cadastrar;
[] Deve ser possível se autenticar;
[] Deve ser possível obter o perfil de um usuário logado;
[] Deve ser possível o numero de check-ins realizados pelo usuário logado;
[] Deve ser possível o usuário obter seu historio de check-ins;
[] Deve ser possível o usuário buscar academias próximas;
[] Deve ser possível o usuário buscar academias pelo nome;
[] Deve ser possível realizar o check-in de um usuário;
[] Deve ser possível cadastrar uma academia;

## RNs (Regras de Negocio)
[] O usuário não deve poder se cadastrar com um e-mail duplicado;
[] O usuário não deve poder fazer 2 check-ins no mesmo dia; 
[] O usuário não deve puder fazer check-in se estiver a mais de 100 metros dela;
[] O check-in só pode ser validado até 20 min de ser criado;
[] O check-in só pode ser validado por administradores;
[] Academias só podem ser criadas por administradores;


## FNs (Requisitos Não Funcionais)
[] A senha do usuário deve estar criptografadas;
[] Os dados da aplicação devem estar persistidos em um banco de dados PostgreSQL;
[] Todas as listas de dados precisam ser paginadas por 20 itens por pagina;
[] O usuário deve ser identificado por um JWT (JSON Web Tokens)


