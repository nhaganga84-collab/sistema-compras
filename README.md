# CompraSystem 🛒
### Sistema de Gestão de Compras e Fornecedores
**Desenvolvido para o mercado moçambicano | Maputo, MZ**

---

## 📦 Módulos Implementados

| Módulo | Funcionalidades |
|--------|----------------|
| 🏢 Fornecedores | Cadastro, edição, pesquisa, ativação/desativação |
| 📦 Produtos | Cadastro, preços, controlo de stock com alertas |
| 📋 Pedidos de Compra | Criação, aprovação, estados (Pendente/Aprovado/Recebido/Cancelado) |
| 🛒 Registo de Compras | Registo completo com atualização automática de stock |
| 💳 Contas a Pagar | Controlo de dívidas, alertas de atraso, M-Pesa/e-Mola |
| 📊 Dashboard | KPIs, gráfico de compras, alertas de stock baixo |
| 📈 Relatórios | Compras, Fornecedores, Financeiro com export PDF/Excel |

---

## 🚀 Como Iniciar

### Windows
```
Duplo clique em: iniciar.bat
```

### Linux / Mac
```bash
chmod +x iniciar.sh
./iniciar.sh
```

### Manual
```bash
pip install -r requirements.txt
python app.py
```

Acede em: **http://localhost:5000**

---

## 🗄️ Base de Dados
- **SQLite** (ficheiro `compras.db` criado automaticamente)
- Dados de exemplo inseridos no primeiro arranque

## 🛠️ Tecnologias
- **Backend:** Python 3 + Flask + SQLAlchemy
- **Frontend:** HTML5 + Bootstrap 5 + Chart.js
- **PDF:** ReportLab
- **Excel:** OpenPyXL
- **BD:** SQLite

## 📂 Estrutura
```
comprasystem/
├── app.py              ← Aplicação principal
├── requirements.txt    ← Dependências
├── iniciar.bat         ← Arranque Windows
├── iniciar.sh          ← Arranque Linux/Mac
├── templates/          ← Páginas HTML
│   ├── base.html
│   ├── dashboard.html
│   ├── fornecedores.html
│   ├── produtos.html
│   ├── pedidos.html
│   ├── compras.html
│   ├── contas.html
│   └── relatorios.html
└── compras.db          ← Base de dados (criado ao iniciar)
```

---
*CompraSystem v1.0 — Lourenço © 2025*
