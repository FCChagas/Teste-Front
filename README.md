# Teste-Front
Teste Destinado aos Interessados para Vaga Front End
# Serão Três Etapas
1.	Criar projeto com VUE.js (Utilizar store para armazenamento de dados)
(Você não deve usar Framework CSS (Bootstrap, Tailwind, Bulma, PureCSS etc.)
2.	Tela de Login<br>
2.1.	Utilizar Mock Online Fake ou Arquivo JSON dentro do Projeto.
3.	Crud de Clientes<br>
3.1.	Utilizar consumo de API em nosso swagger de testes.
# VISUAL E AÇÕES
Nós queremos que você se sinta livre para desenvolver o modelo do jeito que você quiser, nós não temos wireframes ou algo do tipo para essa tarefa. Você irá criar duas telas responsivas:

# PÁGINA LOGIN:
Precisa ter um caixa de login centralizada na tela com dois inputs para o usuário se logar consumindo um Mock Online ou um arquivo JSON.<br>
•	Validando usuário e senha se existem ou estão corretos.<br>
•	Redirecionar para página de clientes abaixo:<br>

# PAGINA CLIENTE
A página precisa ter as seguintes funcionalidades:<br>
- Possuir Cabeçalho, Menu e Rodapé.<br>
- Atualização dos dados do cliente na base de dados<br>
    - Inclusão<br>
    - Alteração<br>
    - Exclusão<br>
- Apresentar a lista de clientes salvos na base de dados em uma tabela, podendo filtrar na lista pelo nome e cpf.<br>
- Validação de campos como CPF e data de nascimento (obrigatório).<br>
- Swagger: https://extranet.fcc.org.br/webapi/testecandidato/swagger/index.html<br>
- Necessariamente fazer a comunicação com a base de dados através do consumo das APIS (Axios)<br>
Objetivo um cadastro de cliente, preenchendo seus dados básicos e dados de endereço.<br>
Abaixo segue campos necessários.<br>
Cliente<br>
- CPF – String
- Nome – String
- RG – String
- Data Expedição – Datetime
- Órgão Expedição – String
- UF – String
- Data de nascimento – Datetime
- Sexo – String
- Estado Civil – String

Endereço Cliente
- CEP – String (buscar em sites online)
- Logradouro – String
- Número – String
- Complemento – String
- Bairro – String
- Cidade – String
- UF – String


# MÉTODO DE AVALIAÇÃO
Seu código estará sob análise do time de Front. O que vamos procurar:
- Boas práticas e padrões
- Código e estrutura de pastas
- Componentização e fluxo de dados

# COMO ENTREGAR:
Subir seu código no git e preencher o form:
https://forms.gle/52HeyfxnjVqwDL1g8
