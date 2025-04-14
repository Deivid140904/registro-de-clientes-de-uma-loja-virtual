# Cadastro de Clientes – Tem de Tudo

## Descrição Geral

Este aplicativo foi desenvolvido como parte da disciplina de **Programação Mobile** no curso de **Análise e Desenvolvimento de Sistemas - 3º semestre - FECAP**.

O app tem como objetivo **facilitar o cadastro inicial de novos clientes** da loja virtual **Tem de Tudo** (www.temdetudo.com.br), principalmente em eventos e lojas físicas. A aplicação guia o usuário desde uma tela de boas-vindas até a confirmação do cadastro, com uma interface simples e intuitiva.

---

## Desenvolvedor

- **Nome:** Deivid Gomes de Oliveira  
- **Curso:** Análise e Desenvolvimento de Sistemas  
- **Semestre:** 3º  
- **Instituição:** FECAP  
- **Disciplina:** Programação Mobile  
- **Professor:** Vinícius Heltai  

---

## Tecnologias e Componentes Utilizados

- Java  
- Android Studio  
- Layouts em XML  
- Navegação entre Activities com `Intent` + `Bundle`  
- Componentes Android:
  - `Button`, `TextView`, `ImageView`, `TextInputLayout`, `EditText`

---

## Funcionalidades e Fluxo de Navegação

1. **Activity 1 – Tela de Boas-Vindas**
   - Imagem da logomarca da loja
   - Botão “Iniciar Cadastro” que leva à próxima tela

2. **Activity 2 – Formulário de Cadastro**
   - Campo de entrada com `TextInputLayout` para digitar o nome
   - Imagem decorativa
   - Botão para enviar os dados e avançar para a confirmação

3. **Activity 3 – Confirmação de Cadastro**
   - Mensagem personalizada:  
     *"Bem-vindo, [nome do cliente]!"*
   - Imagem de “Cadastro Completo”
   - Botão para retornar à tela inicial

---

## Requisitos Atendidos

- ✅ Navegação entre **3 Activities**
- ✅ Uso de:
  - `Button`
  - `TextView`
  - `TextInputLayout`
  - `ImageView` (em todas as telas)
- ✅ Envio de nome via `Intent` com exibição dinâmica na tela de confirmação
- ✅ Interface amigável e funcional

---

## Desafios e Decisões no Desenvolvimento

- **Passagem de Dados:** Utilizei `Intent` e `Bundle` para transferir o nome digitado entre as activities.
- **Design:** Optei por imagens temáticas em cada etapa para deixar a experiência visualmente agradável.
- **Reusabilidade:** O botão de retorno na tela final permite reiniciar o cadastro facilmente, otimizando o uso em eventos.

---

## Executável

- APK gerado: `cadastroTemDeTudo.apk`  
- Projeto completo disponível em formato `.zip`
