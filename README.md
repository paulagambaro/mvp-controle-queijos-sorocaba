# MVP: Sistema de Controle de Validade e Combate ao Desperdício de Queijos

Sistema web mobile-first desenvolvido para auxiliar na gestão de inventário e no combate ao desperdício alimentar em uma revenda de queijos artesanais localizada em **Sorocaba (SP)**.

## 🎯 Objetivo do Projeto
Desenvolver um Minimum Viable Product (MVP) focado na usabilidade de gestores seniores (público 60+), permitindo o registro ágil de lotes de queijos, o controle rigoroso de datas de validade e a emissão de alertas visuais para priorização de vendas de produtos prestes a vencer, alinhando-se diretamente ao **ODS 12 (Consumo e Produção Responsáveis)**.

---

## 📱 Telas do MVP
1. **Tela 1 — Entrada e Autenticação:** Acesso seguro com credenciais autorizadas para iniciar o turno no balcão.
2. **Tela 2 — Registro de Lotes (Funcionalidade Central):** Formulário simplificado para cadastro de novos lotes de queijos (código, tipo, quantidade, fabricação e validade).
3. **Tela 3 — Alertas e Controle de Validade:** Tabela consolidada com indicadores de estado, listagem de estoque e alertas visuais de vencimento (acessibilidade não redundante: cor, ícone ⚠️ e texto descritivo).

---

## 🛠️ Tecnologias Utilizadas
* **Backend:** Python com **Flask**
* **Banco de Dados:** **SQLite** com **Flask-SQLAlchemy**
* **Frontend:** HTML5, CSS3 (Responsivo para dispositivos móveis)
* **Acessibilidade:** Diretrizes WCAG AA (contraste adequado, áreas de toque ampliadas e múltiplos indicadores de estado).

---

## 🚀 Como Executar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone [https://github.com/paulagambaro/mvp-controle-queijos-sorocaba.git](https://github.com/paulagambaro/mvp-controle-queijos-sorocaba.git)
   cd mvp-controle-queijos-sorocaba
