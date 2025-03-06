# Métodos de Pagamento Brasileiros

## Visão Geral
O dataset **"Métodos de Pagamento Brasileiros"** fornece estatísticas mensais abrangentes sobre transações de pagamento no Brasil, com dados provenientes do **Banco Central do Brasil**. Esse conjunto de dados é essencial para pesquisadores, analistas e formuladores de políticas interessados na dinâmica dos métodos de pagamento no país.

Através deste dataset, é possível acompanhar a evolução dos diferentes meios de pagamento ao longo do tempo, como o crescimento do **PIX** e a queda de métodos tradicionais como o **DOC**. Isso possibilita uma análise detalhada sobre a adoção e o uso de diversos instrumentos financeiros no Brasil.

## 📊 Principais Características
- **Período**: Dados mensais a partir de **janeiro de 2016**.
- **Fonte**: Banco Central do Brasil, garantindo **precisão e confiabilidade**.
- **Métodos de pagamento incluídos**:
  - **PIX**: Pagamentos instantâneos.
  - **TED (Transferência Eletrônica Disponível)**: Transferências de alto valor.
  - **TEC (Transferência Eletrônica de Crédito)**: Comumente utilizado para pagamento de salários.
  - **DOC (Documento de Ordem de Crédito)**: Transferências interbancárias.
  - **Cheque**: Método de pagamento em papel.
  - **Boleto**: Boletos bancários emitidos por instituições financeiras.
- **Métricas**: O dataset inclui **quantidade** e **valor total** das transações para cada método de pagamento.

## 📁 Estrutura do Dataset
A tabela contém as seguintes colunas:

| Coluna       | Descrição |
|-------------|--------------------------------|
| **AnoMes**   | Mês de referência no formato AAAAMM. |
| **Qtd_PIX**  | Número de transações PIX. |
| **Valor_PIX** | Valor total das transações PIX. |
| **Qtd_TED**  | Número de transações TED. |
| **Valor_TED** | Valor total das transações TED. |
| **Qtd_TEC**  | Número de transações TEC. |
| **Valor_TEC** | Valor total das transações TEC. |
| **Qtd_Cheque** | Número de transações com cheque. |
| **Valor_Cheque** | Valor total das transações com cheque. |
| **Qtd_Boleto** | Número de transações via boleto. |
| **Valor_Boleto** | Valor total das transações via boleto. |
| **Qtd_DOC**  | Número de transações DOC. |
| **Valor_DOC** | Valor total das transações DOC. |

## 📈 Possíveis Análises
Este dataset pode ser utilizado para diversas análises, incluindo:
- **Análise de tendências**: Monitoramento do crescimento ou declínio dos diferentes métodos de pagamento.
- **Pesquisa econômica**: Estudo do impacto de eventos econômicos no comportamento financeiro da população.
- **Planejamento financeiro**: Suporte na tomada de decisões para instituições financeiras e empresas.
- **Formulação de políticas**: Auxílio na criação de regulamentos e estratégias para incentivar o uso de determinados métodos de pagamento.

## 🚀 Como Usar
1. **Baixe o dataset** diretamente do Banco Central do Brasil ou da base disponibilizada neste repositório.
2. **Carregue os dados** em sua ferramenta de análise preferida (**Python, R, SQL, Power BI, etc.**).
3. **Explore e analise os dados** conforme as necessidades do seu estudo.

Se tiver dúvidas ou sugestões, fique à vontade para contribuir com este repositório! 😊

[![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)](https://docs.google.com/spreadsheets/d/1py2jGg9y4raWJ-fr7p97lyWfchzWXZzc3u8F2V9WvYc/edit?usp=sharing)

