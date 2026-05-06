# 🧪 Ferramenta de Teste de Software: Insomnia

## 📌 Descrição

Este projeto tem como objetivo demonstrar o uso da ferramenta **Insomnia** para testes de APIs REST, utilizando a API pública ViaCEP como exemplo prático.

A atividade foi desenvolvida para a disciplina de **Gestão e Qualidade de Software**, com foco na aplicação de testes de caixa preta.

---

## 👥 Integrantes

* Gustavo Ferreira
* Gustavo Teixeira
* Daniel Fernandes
* João Vitor Fonseca

---

## 🛠️ Ferramentas Utilizadas

* Insomnia (cliente de API)
* API ViaCEP (dados de endereço por CEP)

---

## 🧠 Conceitos Aplicados

* Teste de caixa preta
* Requisições HTTP (GET)
* Status Code (200 OK)
* JSON (formato de resposta)
* Validação de entrada de dados

---

## 🌐 API Utilizada

Foi utilizada a API pública ViaCEP, que permite buscar informações de endereço a partir de um CEP brasileiro.

Exemplo de endpoint:
https://viacep.com.br/ws/{cep}/json/

---

## ⚡ Demonstração dos Testes

### ✅ 1. CEP Válido

* Requisição realizada com um CEP existente
* Resultado: Status 200 e retorno completo dos dados

---

### ❌ 2. CEP Inválido

* Requisição com CEP inexistente
* Resultado: Retorno com `"erro": true`

---

### 🔤 3. CEP com Letras

* Teste com entrada fora do padrão numérico
* Objetivo: verificar validação de dados

---

### 🌍 4. CEP Estrangeiro

* Teste com formato de CEP de outro país
* Objetivo: analisar comportamento fora do domínio da API

---

## 📊 Resultados

Os testes demonstraram que a API responde corretamente para entradas válidas e identifica erros em casos inválidos, reforçando a importância da validação de dados.

---

## 🔍 Análise da Ferramenta

### 👍 Vantagens

* Interface simples e intuitiva
* Execução rápida de testes
* Organização de requisições

### 👎 Desvantagens

* Pouca automação
* Menos popular que outras ferramentas
* Recursos limitados na versão gratuita

---

## 🏁 Conclusão

O Insomnia se mostrou uma ferramenta eficiente para testes de APIs, permitindo validar respostas e identificar erros de forma prática.

Seu uso é recomendado tanto para aprendizado quanto para aplicação em projetos reais.

---

## 📁 Arquivos do Projeto

* Arquivo JSON exportado do Insomnia
* Prints da execução dos testes

---

## 📚 Observação

Este projeto tem fins acadêmicos e foi desenvolvido como atividade prática da disciplina.

---
