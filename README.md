## Contoso Sales Dashboard
<img align="right" width="500" height="320" src="https://github.com/AndersonOS/ContosoPortifolio/blob/main/imagens/VendasVisaoGeral.jpg?raw=true">
Foi desenvolvido um dashboard no Power BI para a Contoso com o objetivo de facilitar a identificação dos principais fatores que afetam o desempenho de vendas. 
Esta ferramenta proporciona análises dinâmicas e um compartilhamento descomplicado para os tomadores de decisão.<br>

Os principais desafios que motivaram este projeto foram:

Possibilidade de conexão da ferramenta diretamente a uma base de dados SQL, eliminando a extração manual de vários relatórios em planilha.<br>
A dificuldade em realizar segmentações intuitivas e compartilháveis por unidades, categorias de produtos, itens e intervalos de tempo.<br>
A falta de capacidade para avaliar a performance através de comparações temporais relevantes (ano a ano, acumulado do ano, mês a mês).
<br>
<a href="https://app.powerbi.com/view?r=eyJrIjoiOTU3ZmU1MTktYjlkZS00Mjk4LWEwMjEtMjY5Mzg1NGE0MjQ4IiwidCI6ImViNmMzNzVlLTA5MDItNGFkMC1iZTJmLTdjZmUxMTJjZTVkNSJ9" target="_blank">Clique aqui</a> e acesse o a solução desenvolvida para o cliente.


<br><br>

## Modelo e fonte de dados 
<img align="left" width="500" height="320" src="https://github.com/AndersonOS/ContosoPortifolio/blob/main/imagens/VendasModelagem.jpg?raw=true">

A conexão foi realizada a um data warehouse, em SQL Server contendo todas informações necessárias. Dessa forma, não houve necessidade de conexão com outras fontes de dados como planilhas, arquivos de textos ou web scrapping.

<br><br><br><br><br><br><br><br>

## Medidas
<img align="right" width="500" height="320" src="https://github.com/AndersonOS/ContosoPortifolio/blob/main/imagens/VendasMedidas.jpg?raw=true">
Após entender as necessidades do cliente e as regras de negócio, e como aplicá-las ao modelo de dados, demos início ao desenvolvimento.
Principais medidas desenvolvidas;
 - Vendas
 -  Medidas de inteligência temporal para comparação de performance e resultados entre períodos distintos ou cumulativos.
Para organizar as medidas, criamos uma tabela contendo todas as medidas, sempre seguindo a padronização dos nomes.


<br><br><br><br><br><br><br><br>

## Ferramentas e linguagens utilizadas
<div style="display: inline_block">
  <img align="center" alt="SQL" height="40" width="40" src="https://github.com/AndersonOS/Portfolio/blob/main/linguagens/sql.png?raw=true">
  <img align="center" alt="Power BI" height="40" width="40" src="https://github.com/AndersonOS/Portfolio/blob/main/linguagens/power%20bi.png?raw=true">
</div>
