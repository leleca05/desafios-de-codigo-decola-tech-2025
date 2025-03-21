# desafios-de-codigo-decola-tech-2025
Conteúdo Decola Tech 25
Desafios de Códigos desenvolvidos no bootcamp
Desafio 1- Simulando Funcionalidades de Sistemas - Implementando um Processo de Autenticação
Descrição
Implemente um programa que simule um login em uma API REST, verificando um usuário e senha fixos (admin/1234).

Entrada
Dois valores: o primeiro é o nome de usuário (string) e o segundo é a senha (string).

Saída
Se os valores forem "admin" e "1234", exiba "Login bem-sucedido!", caso contrário, "Falha na autenticacao!".

Desafio 2 - Simulando Funcionalidades de Sistemas - Simulando um Endpoint de Conversão de Moeda
Descrição
Implemente um programa que simule um endpoint de API REST para converter valores em dólares para reais. O programa deve receber um valor decimal representando um montante em dólares e convertê-lo para reais utilizando uma cotação fixa de R$5,00 por US$1,00.

A saída do programa deve exibir o valor convertido no formato "Valor em reais: R${valor}", garantindo que o resultado tenha duas casas decimais.

Entrada
Um único número decimal (double) representando o valor em dólares.

Saída
O valor convertido para reais no formato "Valor em reais: R${valor}", com duas casas decimais.

Desafio 3 - Simulando Registros e Atualizações em Sistemas - Simulando uma Inserção de Dados
Descrição
Crie um programa que simula a iserção de dados, então, armazene 3 registros de usuários e exiba a lista atualizada.

Entrada
Dois valores:
Nome do usuário (string)
Idade (inteiro)

Saída
Mensagem confirmando a inserção no formato: "Usuário {nome1}, {nome2}, {nome3}"

Desafio 4 - Simulando Registros e Atualizações em Sistemas - Atualizando um Usuário no Banco
Descrição
Você foi designado para desenvolver um programa que armazena dados de usuários e permite verificar se um usuário existe no sistema. O programa deve seguir os seguintes passos:

Cadastrar um número fixo de usuários, onde cada usuário possui um ID único e uma idade. Verificar a existência de usuários no banco de dados com base em uma lista de IDs fornecida. Exibir mensagens apropriadas indicando se o usuário foi encontrado ou não.

Entrada
O programa recebe os seguintes dados na entrada:
Um número inteiro N representando o número de usuários a serem cadastrados.
Para cada um dos N usuários, dois números inteiros:
O primeiro número representa o ID do usuário.
O segundo número representa a idade do usuário.
Um número inteiro M representando a quantidade de IDs que serão verificados.
M números inteiros, representando os IDs a serem verificados no banco de dados.

Saída
1. Cadastro de usuários → "user {ID} OK"

Verificação de usuários:
"ID registered user" → Se o ID for encontrado.
"ID invalid user" → Se o ID não for encontrado.
Observação: A idade do usuário é informada no cadastro, mas não é utilizada durante a verificação de IDs.

Desafio 5 - Simulando Funcionalidades de um Sistema de Artigos - Simulando um Banco de Dados de Artigos
Descrição
Implemente um programa que simula a busca de um artigo de blog baseado no ID e retorna o título correspondente. Cada artigo possui um ID, um título, um autor e uma data de publicação. Caso o usuário informe um ID que não exista no banco, o programa deve exibir a mensagem "Erro: Artigo nao encontrado!".

Requisitos
Você deverá criar um banco de artigos utilizando uma estrutura de dados apropriada. O banco deve conter os seguintes artigos:
ID Título
1 Introducao ao Angular
2 Como usar Services
3 Rotas no Angular
4 Criando Pipes
5 Gerenciamento de Estado no Angular
6 Lazy Loading e Performance
Para armazenar os artigos, utilize uma estrutura de chave-valor, onde o ID do artigo será a chave (Integer) e o título será o valor (String).

Entrada
Um número inteiro representando o ID do artigo.

Saída
O título do artigo no formato "Artigo: {título}". Caso o ID não exista, exibir "Erro: Artigo nao encontrado!".

Desafio 6 - Simulando Funcionalidades de um Sistema de Artigos - Filtrando Artigos Usando Pesquisa por Palavra-Chave
Descrição
Implemente um programa que receba um termo de pesquisa e retorne todos os títulos de artigos que contenham esse termo.

Regras da busca
A busca deve ser case insensitive, ou seja, não deve diferenciar maiúsculas e minúsculas. Se houver correspondências, a saída deve listar os artigos encontrados no formato esperado. Se nenhum artigo for encontrado, o programa deve exibir uma mensagem indicando que não houve resultados. Lista de Artigos Disponíveis Implemente a base de dados contendo os seguintes artigos:
Introducao ao Angular
Como usar Services
Rotas no Angular
Criando Pipes
Cada título deve ser armazenado e pesquisado de forma que a busca não diferencie maiúsculas e minúsculas.

Entrada
O programa recebe uma única linha de entrada, contendo um termo de pesquisa (string) que pode ter uma ou mais palavras.

Saída
1. Se houver correspondências, exibir os artigos no formato:
Artigos encontrados: - {Título do Artigo 1}
- {Título do Artigo 2}

Se nenhum artigo corresponder ao termo pesquisado: Nenhum artigo encontrado para o termo: {termo}
Desafio 7 - Simulando Funcionalidades de um Sistema de Artigos
Descrição
Implemente um programa que simula um sistema de curtidas para artigos de um blog. O sistema permite adicionar curtidas e consultar curtidas de um artigo existente.

O usuário pode escolher entre:
Adicionar curtidas a um artigo existente.
Consultar curtidas de um artigo pelo ID.
Sair do programa.
Se o usuário tentar interagir com um artigo inexistente, o sistema deve exibir "Erro: Artigo não encontrado!".

Entrada
O programa permite interações em um loop controlado até que o usuário escolha a opção "Sair":

Número da opção:
1 → Adicionar curtidas.
2 → Consultar curtidas.
3 → Sair.
ID do artigo (inteiro).

Para a opção 1, o usuário deve informar o número de curtidas (inteiro) a serem adicionadas.

Saída
Para a opção 1: "Curtidas atualizadas: {total de curtidas}". Para a opção 2: "Artigo: {título} | Curtidas: {total}".
