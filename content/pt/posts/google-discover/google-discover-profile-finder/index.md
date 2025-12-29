---
title: "Google Discover Profile Finder: porque isso nunca deveria ser tão difícil"
date: 2025-12-27
slug: "google-discover-profile-finder"
description: "Um mini app em Streamlit que encontra o Google Discover Profile de uma entidade via Knowledge Graph (MID → hash → URL)."
tags:
  - google-discover
  - seo
  - knowledge-graph
  - streamlit
images:
  - google-discover-profile-finder.jpeg
---

## 👀 Descobrir o Google Discover Profile nunca deveria ser tão difícil

Pra quem trabalha com **SEO**, **news**, **conteúdo** ou **mídia**, o Discover ainda é uma caixa-preta.

E uma das partes mais irritantes desse ecossistema é a existência daqueles **“links secretos”** que o Google gera para perfis do Discover — geralmente ligados a entidades do **Knowledge Graph**.

Você sabe que o perfil existe.  
Mas achar o link… parece um jogo.

Então eu fiz um mini app em Streamlit que faz o trabalho pesado por você:

- 🔹 consulta a **Google Knowledge Graph API**
- 🔹 extrai o **MID real** da entidade
- 🔹 converte o MID para o **hash** usado pelo Google nas URLs de Discover Profile
- 🔹 devolve um link limpo, pronto pra usar

---

## O resultado?

👉 Um caminho simples, aberto e transparente para descobrir qual é o **Discover Profile** associado a **qualquer entidade** que exista no KG.

👉 Exemplo: este é o Discover Profile da **Semrush**:  
https://lnkd.in/drnMzBpi

---

## Código aberto, leve, zero truques

🔗 https://lnkd.in/d4PnN-zV

Se você trabalha com SEO, **vale brincar com isso**. É útil — e é divertido.

Se você trabalha no Google… fica aqui meu abraço. 😅
