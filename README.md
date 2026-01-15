# Análise de Dados de E-commerce

## 📋 Descrição
Este projeto realiza uma análise completa de dados de transações de e-commerce para identificar padrões de vendas, comportamento do cliente e desempenho financeiro ao longo do tempo. Utilizando dados reais de transações comerciais, a análise revela tendências sazonais e demonstra como a receita mensal evolui ao longo de um ano completo.

## 🎯 Objetivos
* Analisar a evolução temporal das vendas e receita ao longo de 13 meses
* Identificar padrões sazonais e períodos de pico de vendas
* Segmentar o desempenho por mês para orientar estratégias de marketing
* Quantificar o crescimento da base de clientes e produtos únicos
* Estabelecer métricas base para previsões futuras de vendas

## 📊 Metodologia e Ferramentas
* **Linguagem de Programação:** Python
* **Bibliotecas Principais:** pandas, numpy, matplotlib, seaborn, scipy
* **Ferramentas de Visualização:** Matplotlib, Seaborn
* **Ambiente:** Jupyter Notebook

## 🗃️ O Conjunto de Dados
* **Fonte:** Dataset interno de e-commerce (`ecommerce_dataset_us.csv`)
* **Descrição:** Transações detalhadas de e-commerce incluindo informações de pedidos, produtos, quantidades, preços e clientes
* **Período:** Novembro 2018 a Dezembro 2019 (13 meses completos)
* **Tamanho e Escopo:** 541.909 registros iniciais, 536.641 após limpeza, com 7 características principais

## 🔍 Análise Exploratória de Dados (EDA)
* **Tratamento de Dados:** Remoção de 5.268 duplicatas, conversão de datas para formato datetime, preenchimento de valores ausentes em 'Description' e 'CustomerID', transformação de tipos de dados
* **Estatísticas Descritivas:** Base consolidada de 4.373 clientes únicos e 4.070 produtos únicos, com receita total analisada por período
* **Descobertas Iniciais:** 
  - Crescimento consistente no número de pedidos, de 310 em nov/2018 para 3.552 em nov/2019
  - Receita mensal mostra padrão sazonal claro, com pico em novembro (R$ 1.490.607)
  - Base de clientes ativos cresceu de 207 para 1.730 no mesmo período

## 📈 Modelagem & Resultados
* **Técnica Utilizada:** Análise temporal e agregação por períodos (mensal, semanal)
* **Resultados Obtidos:** Série temporal clara mostrando crescimento orgânico e sazonalidade
* **Insights dos Resultados:** 
  - Novembro representa o mês de maior oportunidade comercial
  - Período pós-natal mostra queda natural que deve ser considerada no planejamento
  - Tendência de crescimento sustentado ao longo do ano analisado

---

## 🚀 Como Executar este Projeto

### Pré-requisitos
* Python 3.7+
* Gerenciador de pacotes pip

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/[seu-usuario]/projeto-ecommerce-analysis.git
```

2. Navegue até o diretório do projeto:
```bash
cd projeto-ecommerce-analysis
```

3. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Execução
* Execute o Jupyter Notebook:
```bash
jupyter notebook projeto_final_ecommerce.ipynb
```

* Execute todas as células em ordem sequencial para reproduzir a análise completa

## 📄 Licença
Este projeto é para fins educacionais e de portfólio.

## 🤝 Contribuições
Sugestões de melhorias na análise são bem-vindas. Sinta-se à vontade para abrir uma issue ou enviar um pull request.

---

*Este projeto foi desenvolvido como parte do portfólio de Análise de Dados. O conjunto de dados representa transações reais de e-commerce processadas e analisadas para extrair insights estratégicos de negócio.*
