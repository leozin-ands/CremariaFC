# ⚽ Cremaria FC — Site Oficial do Time

Site do **Cremaria Futebol Clube** para gestão interna do time: agenda de jogos, elenco, fluxo de caixa, material, patrocínios e pedidos de camisas.

---

## 📋 Funcionalidades

| Página | Descrição |
|---|---|
| 🗓 **Agenda** | Jogos disputados e futuros, resultados, gols e observações |
| 👥 **Elenco** | Plantel organizado por posição (Goleiros, Zagueiros, Laterais...) |
| 💰 **Caixa 2025** | Extrato completo de entradas e saídas financeiras |
| 📊 **Caixa 2026** | Movimentações financeiras do ano atual |
| 📦 **Material** | Controle de uniformes e equipamentos |
| 🤝 **Patrocínios** | Pacotes de patrocínio e parcerias fechadas |
| 👕 **Camisas 2025** | Pedidos de camisas da torcida com status de pagamento |

---

## 🛠 Tecnologia

- **Frontend:** HTML + CSS + JavaScript puro (zero dependências)
- **Banco de dados:** [Claude Artifacts DB](https://claude.ai) — dados compartilhados em tempo real entre todos os usuários
- **Hospedagem:** Vercel (via `vercel.json`) ou qualquer servidor estático

---

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/cremaria-fc.git
cd cremaria-fc

# Abra no navegador
open index.html
# ou
npx serve .
```

> **Nota:** Para os dados sincronizarem entre usuários, o site precisa ser acessado via [Claude Artifacts](https://claude.ai/artifact/FbdCpqe5uLe85hS6NA5rZM). Localmente, os dados ficam salvos no `localStorage` do navegador (somente local).

---

## 📁 Estrutura do Projeto

```
cremaria-fc/
├── index.html       # Todo o site (HTML + CSS + JS em um único arquivo)
├── vercel.json      # Configuração de deploy na Vercel
└── README.md        # Este arquivo
```

---

## ✏️ Como editar dados

Qualquer membro com acesso ao link pode:

1. **Clicar em qualquer célula** das tabelas
2. **Digitar o novo valor**
3. **Pressionar Enter** ou clicar fora — salva automaticamente

Para **adicionar linhas**, use os formulários no rodapé de cada seção.

Para **remover linhas**, clique no botão `✕` ao lado da linha.

---

## 🎨 Design

- **Cores:** Preto (`#080808`) com detalhes em Roxo (`#7c3aed`)
- **Tipografia:** Rajdhani (títulos) + Inter (dados)
- **Estilo:** Dark mode nativo, responsivo

---

## 🔧 Deploy na Vercel

1. Faça o push para o GitHub
2. Acesse [vercel.com](https://vercel.com) → **New Project**
3. Importe o repositório
4. Deploy automático ✅

---

## 📞 Contato

**PIX:** `9b317fc4-601c-4f80-aea6-16bca3106370`

**Instagram:** @cremaria_fc

---

*Cremaria Futebol Clube — Fundado com raça e cream* ⚽🖤🟣
