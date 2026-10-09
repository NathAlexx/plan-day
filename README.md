# ⏱️ TimeCraft - Organizador de Rotina 24h & Notificações

Aplicativo web progressivo (PWA) de gerenciamento e organização de tempo em 24 horas, com visualização de foco em tempo real ("O que fazer agora"), relógio circular interativo de 24h, notificações do sistema na virada de horários e persistência local.

---

## 🚀 Como publicar no GitHub Pages para acessar no Celular

### Passo 1: Criar um repositório no GitHub
1. Acesse [github.com/new](https://github.com/new) e crie um novo repositório (ex: `timecraft` ou `organizador-tempo`).
2. Marque o repositório como **Público** (Public).

### Passo 2: Subir os arquivos para o repositório
No terminal da pasta do projeto, execute os comandos:

```bash
git init
git add .
git commit -m "feat: meu organizador de tempo 24h com notificacoes e pwa"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
git push -u origin main
```

*(Ou você pode simplesmente arrastar e soltar os arquivos `index.html`, `manifest.json` e `sw.js` direto na interface web do GitHub!)*

### Passo 3: Ativar o GitHub Pages
1. No seu repositório do GitHub, vá na aba **Settings** (Configurações).
2. No menu lateral esquerdo, clique em **Pages**.
3. Em **Branch**, selecione `main` e a pasta `/ (root)`.
4. Clique em **Save**.
5. Em menos de 1 minuto, seu link estará no ar:
   👉 `https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`

### Passo 4: Instalar no celular como Aplicativo (PWA)
* **No Android (Google Chrome):** Abra o link do GitHub Pages, toque nos 3 pontinhos no canto superior direito e selecione **"Adicionar à tela inicial"** ou **"Instalar aplicativo"**.
* **No iPhone (Safari):** Abra o link, toque no botão de **Compartilhar** (ícone do quadrado com a setinha para cima) e escolha **"Adicionar à Tela de Início"**.

---

## ✨ Recursos Inclusos
* 🎯 **Tela Principal "Agora":** Mostra imediatamente o que você deveria estar fazendo neste exato minuto, com tempo restante e barra de progresso.
* 🔔 **Notificações do Navegador:** Alerta com sino suave e vibração sempre que mudar de atividade.
* 🧭 **Relógio 24h:** Visualização circular completa da distribuição do dia.
* 📋 **CRUD & Banco Local:** Crie, edite, duplique e exclua horários, com backup em JSON e impressão em PDF.
