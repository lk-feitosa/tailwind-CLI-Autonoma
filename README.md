# 🌐 Projeto Base - Tailwind CSS v4 CLI Autônoma

Este projeto é um ponto de partida leve e funcional com **Tailwind CSS v4**, usando apenas a **CLI autônoma** (sem `npm`, sem `node_modules`, sem PostCSS).

---

## ✅ Estrutura

```
novo-projeto/ 
├── index.html 
├── src/ 
│   ├── js/ 
│   └── styles/ 
│       ├── input.css    ← contém @import "tailwindcss"
│       └── style.css    ← será gerado
└── tailwindcss          ← CLI (baixe e mova manualmente)
```

---

## 🚀 Como usar (Linux)

1. **Baixe o binário da CLI v4.1.3:**

```bash
curl -sLO https://github.com/tailwindlabs/tailwindcss/releases/download/v4.1.3/tailwindcss-linux-x64
chmod +x tailwindcss-linux-x64
mv tailwindcss-linux-x64 tailwindcss
```

2. **Rode o compilador com `watch`:**

```bash
./tailwindcss --input src/styles/input.css --output src/styles/style.css --watch
```

3. **Abra o `index.html` no navegador e pronto!**

---

## 🧠 Por que usar esse método?

- ✅ Sem dependências pesadas  
- 💼 Totalmente local e portátil  
- ⚡ Ideal para projetos simples e protótipos  
- 📴 Roda até offline  

---

## ✨ Créditos

Feito por [lk-feitosa](https://github.com/lk-feitosa)
