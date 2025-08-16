# 🛍️ Store_API

Este projeto está sendo desenvolvido como parte do **Desafio do Bootcamp Santander Backend com Python**, promovido pelo **Santander Open Academy** em parceria com a **DIO**.

## 📚 Descrição

A **Store_API** é uma aplicação backend desenvolvida com **FastAPI**, que tem como objetivo simular uma API de loja virtual. Durante o desenvolvimento, são aplicados conceitos de **TDD (Test-Driven Development)** utilizando **Pytest**, além da integração com o banco de dados **MongoDB**.

Este projeto também serve como referência para boas práticas de documentação e estruturação de projetos em Python.

## 🚀 Tecnologias Utilizadas

- Python 3.11+
- FastAPI
- Pytest
- MongoDB
- Pydantic
- Docker 
  

## 🧪 Testes

Os testes são escritos com **Pytest**, cobrindo tanto testes unitários quanto testes de integração. O objetivo é garantir a confiabilidade da API desde o início do desenvolvimento, seguindo os princípios do TDD.

## 📄 Documentação

A documentação da API é gerada automaticamente pelo FastAPI e pode ser acessada via Swagger UI:
http://localhost:8000/docs após iniciar o servidor.

## 🛠️ Como Executar o Projeto

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/Store_API.git
cd Store_API

# Rodar a aplicação
uvicorn main:app --reload

# Rodar os testes
pytest

