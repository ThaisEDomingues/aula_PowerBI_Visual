# Dashboard de Satisfação e Visitas Mensais
Este repositório contém os arquivos de desenvolvimento e a demonstração visual do dashboard de análise de desempenho regional e engajamento mensal de usuários/clientes.

O objetivo deste relatório é monitorar a média de satisfação por região e o volume de visitas mensais, permitindo que os gestores identifiquem os pontos focais de engajamento e as áreas que necessitam de melhorias no atendimento ou operação.

## 📂 Estrutura do Repositório
AulaPB_Visual.pbix: Arquivo original do Power BI Desktop contendo o modelo de dados, relacionamentos, medidas DAX e a estrutura visual do relatório.

Captura de tela 2026-05-25 181202.png: Imagem demonstrativa do painel principal para visualização rápida.

## 📊 Estrutura do Dashboard
O painel é composto por uma única página focada em três análises principais e dois blocos de segmentação de dados (filtros):

### 1. Média de Satisfação por Região (Gráfico de Colunas)
O que analisa: A nota média de satisfação atribuída pelos usuários, segmentada por localização geográfica.

Métricas visíveis: * South (Sul): 4,5 (Maior índice de satisfação)

North (Norte): 4,4

West (Oeste): 4,3

East (Leste): 4,1

Central (Central): 3,9 (Menor índice de satisfação - ponto de atenção)

### 2. Visitas Mensais (Gráfico de Pizza)
O que analisa: A distribuição percentual e volumétrica (em milhares) do total de visitas acumuladas ao longo dos meses do ano.

Destaque: Permite entender a sazonalidade e quais meses geraram maior tráfego para a operação (ex: Maio com 7,25%, Julho com 9,16%, etc.).

### 3. Visitas Mensais por Região (Gráfico de Linha com Área)
O que analisa: O comportamento histórico e a tendência do volume de visitantes totais ao longo do tempo (Eixo X cronológico detalhado por mês e subdividido por região).

Objetivo: Identificar picos e vales de acessos/visitas para prever demandas futuras em regiões específicas.

### 4. Painel de Filtros (Segmentadores de Dados)
Filtro de Mês (Month): Permite filtrar todo o painel para analisar meses específicos (de Janeiro a Dezembro).

Filtro de Região (Region): Permite isolar os dados para focar apenas em uma ou mais regiões de interesse (Central, East, North, South, West).

## 🛠️ Tecnologias Utilizadas
Power BI Desktop: Ferramenta utilizada para a modelagem dos dados e criação dos componentes visuais.

Engine de Dados: O arquivo possui estruturas internas de metadados (CY26SU02.json para identidade visual, configurações de segurança e modelo de dados comprimido).

## 👥 Créditos
Desenvolvido por: Thais (conforme assinatura fixada no rodapé do relatório).
