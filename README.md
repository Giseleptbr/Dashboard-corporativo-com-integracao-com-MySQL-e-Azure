# Dashboard-corporativo-com-integracao-com-MySQL-e-Azure
Integração um banco de dados relacional MySQL hospedado na Azure com o Power BI, realizando transformações e análises sobre a base "Company". Projeto final DIO.

## 🚀 Etapas do Projeto

1. **Criação da instância MySQL na Azure**
2. **Execução dos scripts SQL para criação das tabelas e inserção dos dados**
3. **Conexão via MySQL Workbench para testes**
4. **Conexão direta do Power BI ao banco MySQL da Azure**
5. **Transformações dos dados no Power Query**
6. **Geração de relatório no Power BI para identificar anomalias e hierarquias**

## 🛠️ Tecnologias Utilizadas

- MySQL 8.0 na Azure
- Power BI Desktop
- MySQL Workbench
- SQL
- GitHub

## 🧩 Scripts

Os arquivos SQL utilizados estão disponíveis na pasta `/scripts`.  
- `script_bd_company.sql`: criação do banco e tabelas com constraints
- `insercao_de_dados_e_queries_sql.sql`: inserção de dados e consultas

## 📈 Transformações Realizadas no Power BI

- Conversão de tipos de dados
- Tratamento de valores nulos
- Junção entre tabelas `employee` e `departament`
- Criação de coluna de nome completo
- Junção com nomes dos gerentes
- Análise de departamentos sem gerente
- Criação de campo `departamento_localizacao`
- Contagem de colaboradores por gerente

## 📷 Conexões e Evidências

As capturas de tela da conexão e ambiente estão disponíveis na pasta `/imagens`.
