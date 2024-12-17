# app

Gympass App

## RFs (Requisitos Funcionais)

- [] Deve ser possível ser cadastrar;
- [] Deve ser possível se autenticar;
- [] Dese ser possível obter o perfil de um usuario logado;
- [] Deve ser possível obter o número de check-ins realizado pelo usuário logado;
- [] Deve ser possível o usuário seu histórico de check-ins;
- [] Deve ser possível ser possível o usuário buscar academias próximas;
- [] Deve ser possível ser possível o usuário buscar academias pelo nome;
- [] Deve ser possível ser possível o usuário realizar check-ins em uma academia;
- [] Deve ser possível ser possível realozar o check-ins de um usuário;
- [] Deve ser possível cadastrar academias;

## RNs (Regras de Negócio)
- [] O usuário não pode se cadastrar com e-mail duplicado;
- [] O usuário não pode fazer 2 check-ins no mesmo dia;
- [] O usuário não pode fazer checik-in se não estiver perto de 100 metros de distância;
- [] O check-in só pode ser validado até 20 min. após validado;
- [] O check-in só pode ser validado por adiministradores;
- [] A academia só pode se cadastrada por adiministradores;


## RNF (Requisitos Não Funcionais)

- [] A senha do usuário precisa está criptografado
- [] Os dados da aplicacão precisam está persistido em um banco postgreSQL;
- [] Todas as listas de dados precisam está paginadas com 20 itens por página;
- [] O usuário deve  ser identidicado por um JWT (Json WEB Token);
