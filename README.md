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
│       ├── input.css    ← contém @import "tailwindcss";
│       └── style.css    ← será gerado
└── tailwindcss          ← CLI (baixe e mova manualmente)
```

---

## 📦 Download do binário Tailwind CLI

> Baixe o executável da CLI autônoma diretamente do GitHub e renomeie como `tailwindcss` antes de usar.

🔗 **[Clique aqui para baixar (Linux)](https://github.com/lk-feitosa/tailwind-CLI-Autonoma/releases/download/v4.1.3/tailwindcss)**

```bash
chmod +x tailwindcss
```

---

## 🚀 Como usar (Linux)

1. **Rode o compilador com watch:**

```bash
./tailwindcss --input src/styles/input.css --output src/styles/style.css --watch
```

2. Abra o `index.html` no navegador e pronto!

---

## 🧠 Por que usar esse método?

- Sem dependências pesadas  
- Totalmente local e portátil  
- Ideal para projetos simples e protótipos  
- Roda até offline  

---

✨ Créditos  
Feito por [lk-feitosa](https://github.com/lk-feitosa)
