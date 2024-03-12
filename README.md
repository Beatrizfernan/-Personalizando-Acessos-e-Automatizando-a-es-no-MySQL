# **Desafio de Personalização de Acessos e Automatização de Ações no MySQL**

Este é um projeto desenvolvido para cumprir os desafios propostos relacionados à personalização de acessos e automatização de ações no MySQL.

## **Parte 1 – Personalizando acessos com views**

Nesta parte do desafio, foram criadas visões para diversos cenários específicos, visando personalizar o acesso aos dados no MySQL. As visões criadas são:

1. Número de empregados por departamento e localidade.
2. Lista de departamentos e seus gerentes.
3. Projetos com maior número de empregados (por ordenação decrescente).
4. Lista de projetos, departamentos e gerentes.
5. Quais empregados possuem dependentes e se são gerentes.

As permissões de acesso às visões foram definidas de acordo com o tipo de conta de usuários, garantindo o acesso apropriado aos dados.

## **Parte 2 – Criando gatilhos para cenário de e-commerce**

Nesta parte do desafio, foram criados gatilhos (triggers) para lidar com ações que ocorrem antes ou depois da inserção, atualização ou remoção de dados no banco de dados, considerando um cenário de e-commerce. Os seguintes gatilhos foram criados:

1. Trigger de remoção: before delete.
2. Trigger de atualização: before update.

## **Como utilizar este projeto**

1. Certifique-se de ter um servidor MySQL configurado e em execução.
2. Execute os scripts SQL fornecidos na ordem especificada para criar as visões e os gatilhos necessários.
3. Ajuste as permissões de acesso conforme necessário, de acordo com a estrutura real do seu banco de dados.
4. Utilize as visões criadas para acessar os dados de forma personalizada.
5. Teste os gatilhos criados para garantir que funcionem conforme o esperado.
