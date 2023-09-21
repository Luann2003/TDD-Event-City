# TDD-Event-City
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Luann2003/TDD-Event-City/blob/main/LICENSE) 

O Projeto TDD-Event-City é uma aplicação que foi desenvolvida seguindo a metodologia de Desenvolvimento Orientado a Testes (TDD). O TDD é uma prática de programação que envolve escrever testes automatizados antes de escrever o código de produção. Esses testes servem como especificações do comportamento esperado do sistema e são uma parte fundamental do desenvolvimento deste projeto.
## Sobre o projeto
Neste projeto, a estrutura de testes foi organizada de forma a separar os testes de unidade, testes de integração e testes de aceitação. Isso proporciona uma cobertura abrangente dos cenários de teste.

Este projeto foi desenvolvido como parte dos meus estudos no programa Dev Superior, um programa intensivo de desenvolvimento back-end.

## Ciclo TDD
Escrever um teste: Primeiro, um teste automatizado é escrito para descrever um novo recurso ou funcionalidade. Este teste inicial falha, pois o código de produção correspondente ainda não foi implementado.

Escrever código de produção: O código de produção é então implementado para fazer com que o teste passe. O foco é apenas fazer o teste passar, não se preocupando com otimizações ou recursos adicionais neste momento.

Refatorar: Após o teste passar, o código é refinado e otimizado conforme necessário. Certifique-se de que os testes existentes continuem a passar durante esse processo.

## Benefícios do TDD
O uso do TDD neste projeto trouxe diversos benefícios, incluindo:

Documentação viva: Os testes servem como documentação viva do comportamento do sistema. Qualquer pessoa pode ler os testes e entender como o sistema deve funcionar.

Detecção precoce de erros: Erros são identificados rapidamente, já que os testes são executados automaticamente a cada alteração de código.

Facilita a refatoração: A confiança nos testes permite que você faça alterações no código com segurança, sabendo que os testes o protegerão contra regressões.

Colaboração: Os testes facilitam a colaboração em equipe, pois garantem que todos estejam na mesma página em relação ao comportamento esperado do sistema.

## Testes de Requisito

A seguir estão os testes de requisitos que devem ser atendidos pelo projeto:

- **POST /events deve retornar 401 Unauthorized para usuário não logado**

- **POST /events deve retornar 201 Created para CLIENT logado e dados corretos**

- **POST /events deve retornar 201 Created para ADMIN logado e dados corretos**

- **POST /events deve retornar 422 Unprocessable Entity para ADMIN logado e nome em branco**

- **POST /events deve retornar 422 Unprocessable Entity para ADMIN logado e data no passado**

- **POST /events deve retornar 422 Unprocessable Entity para ADMIN logado e cidade nula**

- **GET /events deve retornar 200 Ok com página de recursos**

- **POST /cities deve retornar 401 Unauthorized para usuário não logado**

- **POST /cities deve retornar 403 Forbidden para CLIENT logado**

- **POST /cities deve retornar 201 Created para ADMIN logado e dados corretos**

- **POST /cities deve retornar 422 Unprocessable Entity para ADMIN logado e nome em branco**

- **GET /cities deve retornar 200 Ok com todos recursos ordenados por nome**


```bash
# Clone o repositório
git clone https://github.com/Luann2003/TDD-Event-City.git

# Navegue até o diretório do projeto
cd TDD-Event-City

# Compile e execute o programa
java main.java
```
# Autor
Luan Victor de Ramos Luciano

https://www.linkedin.com/in/luan-luciano-1603b4197/


