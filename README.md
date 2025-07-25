# 📉 Análise de Evasão de Clientes (Churn) - TelecomX

Este projeto tem como objetivo analisar os dados de clientes da empresa fictícia **TelecomX** e identificar os principais fatores que contribuem para a **evasão de clientes (Churn)**. A análise foi conduzida com base em dados reais simulados, utilizando Python e bibliotecas de ciência de dados.

---

## 📌 Objetivo

Investigar os fatores associados à perda de clientes e propor **insights e recomendações** para reduzir o churn na empresa. A análise visa responder:

- Quem são os clientes mais propensos a cancelar?
- Quais serviços ou perfis estão mais associados à evasão?
- Quais ações podem ser tomadas para reter esses clientes?

---

## 📂 Estrutura do Projeto

```bash
📁 challenge2-data-science/
│
├── LICENSE.md                  # Licença MIT
├── README.md                   # Este arquivo
├── Requirements.txt            # Dependências a serem instaladas
├── TelecomX_BR (1).ipynb       # Notebook com a análise completa
├── TelecomX_Data.json          # Base de dados utilizada
└── TelecomX_dicionario.md      # Dicionário utilizado
```

---

## 🧪 Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** — Manipulação de dados
- **NumPy** — Operações numéricas
- **Matplotlib** — Visualizações gráficas
- **Seaborn** — Visualizações estatísticas
- **Jupyter Notebook** — Ambiente interativo de análise

---

## 📊 Principais Análises

- Distribuição de clientes com e sem churn
- Correlação entre churn e:
  - Tipo de contrato
  - Serviços adicionais (streaming, segurança, suporte)
  - Forma de pagamento e faturamento
  - Tempo de permanência (`tenure`)
- Gráficos de barras, histogramas e heatmaps
- Geração de insights acionáveis com base nos dados

---

## 💡 Principais Insights

- Clientes com **contrato mensal**, **pagamento via boleto eletrônico** e **sem serviços adicionais** apresentam maiores taxas de churn.
- Usuários com **Internet via fibra óptica** e **baixo tempo de permanência** estão entre os que mais cancelam.
- A ausência de serviços como **suporte técnico, backup online e segurança** está fortemente associada à evasão.

---

## ✅ Recomendações

- Oferecer **descontos ou bônus** para contratos de longo prazo.
- Incentivar a ativação de serviços complementares com **testes gratuitos**.
- Criar **campanhas específicas para retenção** de novos clientes.
- Monitorar proativamente clientes com baixo `tenure` e perfil de risco.

---

## ▶️ Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/Bainazz/challenge2-data-science.git
```

2. Instale as dependências:
```bash
pip install -r Requirements.txt
```

3. Execute o notebook:
```bash
jupyter notebook TelecomX_BR (1).ipynb
```

---

# 📎 Licença
Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.

---

# 👤 Autor
Desenvolvido por Braian Mezalira.
Contribuições, sugestões e feedbacks são bem-vindos!
