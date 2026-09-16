# sucupira_ufrj

Código para baixar, filtrar e modelar dados relacionados aos Programas de Pós-Graduação (PPG's) da UFRJ. Todo o processo pode ser encontrado no arquivo 'ufrj_capes.ipynb'.

Os dados brutos são obtidos através do [Portal de Dados Abertos da CAPES](https://dadosabertos.capes.gov.br/).

Os dados processados são posteriormente utilizados para popular o banco de dados do [Painel "PG e Pesquisa da UFRJ em números"](https://github.com/GID-UFRJ/gid-painel).

---

## Definição de gênero a partir do primeiro nome:

Arquivo json com o mapeamento obtido a partir do arquivo 'grupos.csv' do dataset 'Gênero dos Nomes' do projeto [Brasil IO](https://brasil.io/dataset/genero-nomes/grupos/). Licença:  [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). 

O código utilizado para a geração do json está no arquivo 'genero.ipynb'.
