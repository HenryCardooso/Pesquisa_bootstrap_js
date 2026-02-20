# 🏎️ Trabalho Prático: Requisições e APIs com JavaScript

Este repositório contém os exemplos práticos desenvolvidos para o trabalho de JavaScript, focando no funcionamento de APIs, requisições HTTP e manipulação dinâmica do DOM.

## 👥 Integrantes do Grupo
Arthur Ribeiro de Azevedo  
Carlos Daniel Gualberto dos Santos  
Gustavo Santana Rebolo  
Henry Menezes Cardoso  
Larissa Eduarda Braz da Silva  
Othávio Kauan Gomes Corrêa  
Rafaela Merlotto Parrilla  

---

## 🛠️ Conteúdo do Trabalho

O trabalho foi dividido em três demonstrações principais para cobrir todos os requisitos obrigatórios:

### 1. Fazendo requisições com fetch()
Demonstramos a sintaxe base da API Fetch utilizando a **JSONPlaceholder**. Este exemplo foca na conexão inicial com o servidor.
**Arquivo:** exemplo-fetch.html
**API utilizada:** /users

### 2. O Método .then() e manipulação de JSON
Nesta etapa, focamos no tratamento da "Promessa" (Promise) e na transformação da resposta em dados utilizáveis. Utilizamos o .slice(0, 5) para filtrar os dados recebidos.
**Arquivo:** exemplo-then.html
**API utilizada:** /posts

### 3. Exemplo Completo e Tratamento de Erro (.catch())
Nosso exemplo principal utiliza o tema do filme **Carros**. Ele une todos os conceitos anteriores: busca de dados, conversão, criação de cards visuais (imagem + texto) e o tratamento de erros caso a comunicação falhe.
**Arquivo:** exemplo-carros.html
**Destaque:** Uso do bloco .catch() para emitir alertas amigáveis ao usuário em caso de falha.

---

## 🚀 Explicação Técnica dos Comandos

| Comando | Função |
| :--- | :--- |
| fetch(url) | Inicia a requisição ao servidor (retorna uma Promise). |
| .then(res => res.json()) | Converte a resposta bruta do servidor para o formato JSON (objeto JS). |
| .then(dados => { ... }) | Bloco onde os dados já convertidos são manipulados para aparecer no HTML. |
| .catch(erro => { ... }) | Captura qualquer falha no processo (erro de rede, URL inválida, etc). |
| document.createElement() | Cria novos elementos HTML via JavaScript para exibição dinâmica. |



---

## 🏎️ Como visualizar os exemplos
1. Clone ou baixe este repositório.
2. Abra cada arquivo .html em seu navegador.
3. Clique nos botões de ação para disparar as requisições em tempo real.

---
**Professor:** Valmir Gomes de Jesus  
**Disciplina:** Desenvolvimento Web / JavaScript
