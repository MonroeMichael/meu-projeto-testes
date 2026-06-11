# Testes de Interface com Maestro - SauceDemo



##  Visão Geral

Projeto para a disciplina **Gestão da Qualidade e Teste de Software**.

Objetivo: automatizar testes de interface na plataforma `saucedemo.com` usando **Maestro**.



##  Como executar os testes

1. Clone o repositório

2. Certifique-se de ter o Maestro instalado

3. Execute: `maestro test .maestro/`



##  Casos de Teste



&#x20;ID  Cenário  Resultado Esperado  Status 

-----------------------------------------

&#x20;TC-01  Login com standard\_user  Página "Products" é exibida ✅ Aprovado 

&#x20;TC-02  Login com credenciais inválidas  Mensagem "Epic sadface" ✅ Aprovado 

&#x20;TC-03  Login com locked\_out\_user  Mensagem de usuário bloqueado ✅ Aprovado 

