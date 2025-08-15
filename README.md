Dashboard de Inadimplência Escolar em Power BI
Descrição
Este repositório documenta um projeto real de análise de inadimplência escolar, cobrindo desde a exploração inicial dos dados até a criação de um painel interativo em Power BI. Durante o processo, dados sensíveis foram devidamente ocultados para proteger a privacidade das informações.


Objetivo
O projeto visa identificar padrões e tendências de inadimplência em instituições educacionais, propondo melhorias no funil de cobrança e auxiliando na recuperação eficaz de receitas.


Estrutura do Repositório
/dashboards: Contém o arquivo Power BI (Dashboard-Inadimplencia.pbix) com visualizações detalhadas.
/scripts: Inclui o Google Colab (EDA-inadimplencia.ipynb) utilizado para EDA e tratamento dos dados.
/documents: Relatórios executivos e materiais de suporte, detalhando a análise financeira.
/data: Conjunto de dados utilizados no projeto:
base_de_dados.xlsx: Arquivo original com dados brutos.
base.csv: Dados após tratamento, prontos para análise.
funil.csv: Dados do funil de cobrança tratados.


Guia de Uso
Pré-requisitos
Power BI Desktop: Necessário para abrir e interagir com o painel.
Python e Google Colab: Para rodar os scripts de análise de dados.
Etapas do Projeto
Análise Exploratória de Dados (EDA) em Python:
Usando bibliotecas como pandas, os, glob e datetime, o EDA explora a estrutura, qualidade e padrões nos dados.
O notebook EDA-inadimplencia.ipynb pode ser executado no Google Colab para replicar as análises.


Tratamento de Dados:
As bases originais foram refinadas, eliminando duplicidades e corrigindo inconsistências.
Os arquivos resultantes (base.csv e funil.csv) são usados como input para o Power BI.
Dashboard em Power BI:
O painel interativo visualiza dados críticos de inadimplência, segmentação por região, série e unidade.
O arquivo .pbix é carregado diretamente no Power BI Desktop para análise visual.


Contribuições
Colaborações são incentivadas. Siga os passos para contribuir:


Realize um fork do projeto.


Crie uma nova branch (git checkout -b feature/MinhaFeature).


Faça commit das alterações (git commit -m 'Adicionar nova feature').


Envie para a branch (git push origin feature/MinhaFeature).


Abra um Pull Request.


Licença
Este projeto está sob a MIT License - veja o arquivo LICENSE para mais detalhes.


Contato
Para dúvidas ou sugestões, entre em contato com Andres Silva no LinkedIn.
