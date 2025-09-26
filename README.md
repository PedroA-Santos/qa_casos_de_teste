# 📋 Casos de Teste - Projeto MyApp (Fictício)

Este repositório contém casos de teste criados para fins de estudo em **Quality Assurance (QA)**.

## Funcionalidades testadas
- Cadastro de Usuário
- Login
- Carrinho de Compras
- Checkout

## Estrutura
- `Casos_de_Teste_Cadastro.xlsx` → Cenários de cadastro de usuário
- `Casos_de_Teste_Login.xlsx` → Cenários de login de usuário
- `Casos_de_Teste_Carrinho.xlsx` → Cenários de carrinho de compras

## Exemplos de Casos de Teste
**CT01 - Cadastro Válido**
- Pré-condição: Usuário não cadastrado
- Passos:
  1. Acessar tela de cadastro
  2. Preencher Nome, E-mail, Senha e Confirmar Senha
  3. Clicar em "Cadastrar"
- Resultado Esperado: Sistema deve exibir mensagem "Cadastro realizado com sucesso"

**CT05 - Cadastro com senha e confirmação diferentes**
- Resultado Esperado: Exibir mensagem "Senhas distintas"
- Resultado Obtido: Sistema não exibiu mensagem e cadastrou usuário (**BUG**)

## Objetivo
📌 Este repositório faz parte do meu aprendizado em QA e será expandido com novos cenários e funcionalidades.

---

