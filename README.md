Análise de Evasão de Clientes (Churn) - Telecomunicações

📌 Visão Geral
Este projeto analisa padrões de evasão de clientes (Churn) em uma empresa de telecomunicações, identificando fatores críticos que influenciam o cancelamento de serviços. A análise revelou uma taxa média de evasão de 26.5%, com insights valiosos para estratégias de retenção.

📊 Principais Métricas
Taxa de Churn: 26.5%

Fator #1 de Risco: Contratos mensais (3x mais evasão que anuais)

Período Crítico: Primeiros 6 meses (42.1% evasão)

Faixa Problemática: Planos de $90-120/mês (42.3% evasão)

🛠️ Como Usar
Clone o repositório:

bash
git clone https://github.com/seu-usuario/analise-churn-telecom.git
Instale as dependências:

bash
pip install -r requirements.txt
Execute o notebook Jupyter:

bash
jupyter notebook analise_churn.ipynb
📂 Estrutura do Projeto
text
analise-churn-telecom/
├── data/
│   └── TelecomX_Data.json       # Dados originais
├── notebooks/
│   └── analise_churn.ipynb      # Análise completa
├── outputs/
│   ├── churn_dist.png           # Gráficos exportados
│   └── tenure_churn.png         
└── README.md                    # Este arquivo
🔍 Principais Descobertas
Clientes com menos de 6 meses têm maior risco

Pagamentos eletrônicos associados a +34.7% Churn

Serviços adicionais reduzem evasão em 28%

Clientes com dependentes são 16.2% mais fiéis

💡 Recomendações Implementáveis
Programa de fidelização para primeiros 6 meses

Incentivos para conversão em contratos anuais

Redesenho dos planos de $90-120/mês

Campanhas específicas para idosos (41.7% Churn)

📈 Impacto Esperado
Potencial para reduzir a evasão em 15-20% no primeiro ano de implementação das ações recomendadas.

🤝 Como Contribuir
Contribuições são bem-vindas! Siga estes passos:

Faça um fork do projeto

Crie sua branch (git checkout -b feature/analise-multivariada)

Commit suas mudanças (git commit -m 'Adiciona análise de cohort')

Push para a branch (git push origin feature/analise-multivariada)

Abra um Pull Request

📜 Licença
MIT License - veja o arquivo LICENSE para detalhes.


