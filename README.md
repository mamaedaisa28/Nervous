# Maré — acompanhamento diário

App de página única (HTML/CSS/JS, sem build) com:
- **Hoje**: checklist diário que muda automaticamente conforme o mês do seu plano de 6 meses, e um guia de respiração 4/8 animado.
- **Diário**: registro rápido de humor + intensidade (0–10) + nota livre.
- **Plano**: os 6 meses completos, em acordeão, com o mês atual já aberto.
- **Progresso**: sequência de dias, dias ativos e um mapa de calor dos últimos 45 dias.

Os dados ficam salvos apenas no seu navegador/conta (armazenamento pessoal), não são compartilhados com mais ninguém.

## Como colocar no ar (Vercel)

**Opção 1 — mais fácil, sem instalar nada:**
1. Acesse [vercel.com/new](https://vercel.com/new) e crie uma conta gratuita (pode usar GitHub, Google ou e-mail).
2. Clique em "Deploy" e arraste esta pasta (`nervous-app`) direto na área de upload.
3. Em alguns segundos você recebe um link tipo `seu-app.vercel.app` — pronto, é só usar.

**Opção 2 — via linha de comando:**
```bash
npm install -g vercel
cd nervous-app
vercel
```
Siga as perguntas (pode aceitar todas as opções padrão). No fim, o terminal te dá o link do app.

**Opção 3 — via GitHub:**
1. Suba esta pasta para um repositório novo no GitHub.
2. Em vercel.com/new, escolha "Import Git Repository" e selecione o repositório.
3. Não precisa configurar nada (é HTML estático) — clique em Deploy.

Depois de publicado, adicione o link à tela inicial do seu celular (Safari/Chrome → "Adicionar à tela de início") pra abrir como se fosse um app.
