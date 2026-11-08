# ⏱️ Chronos24 — Monitor Inteligente de Budget de Tempo & Micro-Decisões (PWA)

Aplicativo Web Progressivo (**PWA**) desenvolvido com arquitetura **Single Codebase** (base de código única responsiva para **Mobile, Tablet e Desktop**).

## ✨ Funcionalidades Principais

1. **Orçamento Diário de 24 Horas (Time Budgeting)**
   - Alocação interativa entre **Sono**, **Trabalho**, **Lazer** e **Autocuidado**.
   - Alertas visuais em tempo real quando a soma passa de 24h (*Estouro de Orçamento*), quando sobram horas livres ou quando a conta fecha exatamente em `24.0h`.
   - Botão **Auto-Fechar 24h** e presets rápidos (*Equilibrado*, *Sprint* e *Descanso*).
2. **Experiência Mobile (Execução Rápida no Dia a Dia)**
   - **Cronômetro Rápido (Pomodoro / Deep Work / Pausa)** integrado ao orçamento: ao concluir uma sessão, o tempo é creditado automaticamente nas horas realizadas da categoria.
   - **Gatilhos de Bem-Estar**: rastreador visual de copos de água (`250ml`) e contador de pausas ativas (*Levantar da Cadeira*).
   - **Assistente Matinal de Micro-Decisões (< 2 min)**: recomendação de *Look do Dia* conforme clima local, *Marmita/Refeição* e *Checklist das 3 Tarefas Cruciais*.
3. **Experiência Desktop (Análise & Planejamento)**
   - Gráficos comparativos **Planejado vs. Realizado** e **Score de Equilíbrio Diário**.
   - **Linha do Tempo de Agenda** com simulação de sincronização Google/Outlook Calendar.
   - **Planejamento para o Dia Seguinte** com persistência offline via `localStorage`.

## 🚀 Como Publicar no GitHub Pages (Passo a Passo)

1. Crie um novo repositório público no GitHub (ex.: `chronos24-pwa`).
2. Faça o upload de todos os arquivos desta pasta na raiz do repositório:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
3. No repositório do GitHub, clique em **Settings** (Configurações) → **Pages** (no menu lateral esquerdo).
4. Em **Build and deployment** → **Branch**, selecione `main` (ou `master`), mantenha a pasta `/(root)` e clique em **Save**.
5. Aguarde cerca de 1 minuto e acesse o link gerado (`https://seu-usuario.github.io/chronos24-pwa/`) no computador da faculdade ou no celular!
