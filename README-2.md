# 🚀 Atualizador Automático — HR System

Ferramenta profissional para enviar arquivos direto para o GitHub pelo celular ou computador, sem precisar instalar nada.

**Acesse em:** `https://SEU-USUARIO.github.io/atualizador-automatico`

---

## 📋 Como publicar pela primeira vez

Siga os passos abaixo — leva menos de 5 minutos.

---

### Passo 1 — Criar o repositório

1. Acesse [github.com/new](https://github.com/new)
2. Preencha:
   - **Repository name:** `atualizador-automatico`
   - **Visibility:** ✅ Public
   - **Add a README file:** deixe **desmarcado**
3. Clique em **Create repository**

---

### Passo 2 — Fazer upload do arquivo

1. Na página do repositório recém-criado, clique em **"uploading an existing file"**
2. Arraste ou selecione o arquivo **`index.html`**
3. Na seção *Commit changes*, escreva: `Primeiro deploy do Atualizador`
4. Clique em **Commit changes**

---

### Passo 3 — Ativar o GitHub Pages

1. No repositório, vá em **Settings** (⚙️)
2. No menu lateral, clique em **Pages**
3. Em *Branch*, selecione **main** e a pasta **/ (root)**
4. Clique em **Save**
5. Aguarde ~1 minuto e acesse:

```
https://SEU-USUARIO.github.io/atualizador-automatico
```

> Substitua `SEU-USUARIO` pelo seu usuário do GitHub.

---

## 🔑 Criar o Token do GitHub (PAT)

O app precisa de um token para enviar arquivos. Crie um assim:

1. Acesse [github.com/settings/tokens/new](https://github.com/settings/tokens/new)
2. Preencha:
   - **Note:** `Atualizador HR`
   - **Expiration:** 90 days (ou *No expiration*)
3. Em *Scopes*, marque apenas: ✅ **repo**
4. Clique em **Generate token**
5. **Copie o token imediatamente** — ele só aparece uma vez!

Cole o token no campo **"Token do GitHub"** dentro do app.

---

## 📱 Adicionar à tela inicial do celular

Para acessar como um app, sem abrir o navegador:

**iPhone (Safari):**
1. Abra o link no Safari
2. Toque em **Compartilhar** (ícone de caixa com seta)
3. Toque em **Adicionar à Tela de Início**
4. Confirme o nome e toque em **Adicionar**

**Android (Chrome):**
1. Abra o link no Chrome
2. Toque nos **três pontos** (menu)
3. Toque em **Adicionar à tela inicial**
4. Confirme e toque em **Adicionar**

---

## 🔄 Como atualizar o próprio app

Se você melhorar o `index.html` e quiser publicar a nova versão:

1. Abra o próprio **Atualizador Automático**
2. Configure com o repositório `atualizador-automatico`
3. Selecione o novo `index.html`
4. Clique em **Enviar agora**

O app se atualiza sozinho! 🎉

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---|---|
| 🔌 Teste de conexão | Verifica token, repositório e branch |
| 📦 Auto-completar repos | Busca seus repositórios automaticamente |
| ⚡ Ações rápidas | Atalhos pré-configurados para deploys comuns |
| 📋 Histórico | Registra os últimos 20 deploys |
| 📊 Barra de status | Mostra repo, branch e arquivos em tempo real |
| 📱 Mobile-first | Funciona perfeitamente no celular |

---

## ❓ Dúvidas frequentes

**O GitHub Pages demora para atualizar?**
Sim, pode levar até 2 minutos após o envio. É normal.

**Posso usar com repositórios privados?**
Sim! O token com escopo `repo` acessa repositórios privados normalmente. Mas o GitHub Pages gratuito só publica repositórios públicos.

**Meu token está seguro?**
O token é salvo apenas no `localStorage` do seu próprio navegador, nunca em servidores externos.

---

*Desenvolvido para o sistema HR · Atualizado via GitHub Deployer Pro*
