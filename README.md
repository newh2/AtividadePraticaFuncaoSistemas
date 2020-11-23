# Atividade Pratica Função Sistemas! 

## Adicionar campo CPF no formulário, respeitando as seguintes premissas:

-  O campo deverá seguir o padrão visual dos demais campos da tela
-  Preenchimento do campo é obrigatório
-  Formatação do campo deve serguir o padrão do CPF (999.999.999-99)
-  Validar CPF utilizando calculos para verificação dos últimos digitos
-  Não permitir o cadastro de um CPF que já existe na base de dados
-  Criar o campo CPF na tabela Clientes do banco de dados


<br></br>

## Como foi feito:

- Foi criado o campo no sql utilizando o script: 
  ALTER TABLE CLIENTES ADD CPF VARCHAR(14)
- Fora adicionado o campo CPF em todas funções do banco de dados
- Criação da função ValidarCPF para validação dos digitos do CPF
- Atualização das classes controller, model e view
- Atualização das classes jquery com o campo CPF
- Criação do campo utilizando a regra do bootstrap para colunas
- Formatação do campo CPF utilizando JavaScript

<br></br>
## Stacks utilizadas:

<img align="left" alt="GitHub" src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
<img align="left" src="https://img.shields.io/badge/c%23%20-%23239120.svg?&style=for-the-badge&logo=c-sharp&logoColor=white"/>
<img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src="https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white"/>
