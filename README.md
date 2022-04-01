## Curso Aplicações em meteorologia usando Python (2022)

Curso de Python elaborado por Rafael Cesario de Abreu, Natália Machado Crespo com colaboração das Profas. Rita Yuri Ynoue, Marcia Akemi Yamasoe do Instituto de Astronomia, Geofísica e Ciências Atmosféricas (IAG-USP) para alunos da graduação e pós graduação de Meteorologia indicando algumas aplicações da linguagem de programação na análise de dados de ciências atmosféricas. São cinco aulas contendo:

- [Aula 1](aulas/Aula01a-Basico.ipynb)
    - Básico da linguagem: Para que serve; para que é usada. Comandos básicos, como importar pacotes
    - Visualização de dados: Como fazer cálculos e visualizar os resultados, modificar os eixos e formatar a figura
- [Aula 2](aulas/Aula02.ipynb)
    - Análise de dados univariados: Cálculo de anomalias, tendências, médias mensais, sazonais e anuais, preencher dados faltantes
- [Aula 3](aulas/Aula03-Dados_multivariados.ipynb)
    - Análise de dados multivariados: Cálculo de anomalias, extração de tendência, climatologias espaciais, extração de dados de uma região específica
- [Aula 4](aulas/Aula04.ipynb)
    - Comparação de diferentes datasets: interpolar para a mesma grade e calcular estatísticas
    - Composição de campos espaciais
- [Aula 5](aulas/Aula05-PCA.ipynb)
    - Análise de Componentes Principais (ACP)


De forma mais técnica, são abordados pacotes como `numpy`, `pandas`, `matplotlib`, `cartopy`, `xarray` e `statsmodels` que são base para grande parte da análise de dados que encontramos na área.

### Material Extra

Existe um material extra que contém algumas informações complementares que podem ser úteis:

- [Como instalar](material_extra/Como_instalar.pdf):  Nesse arquivo há informações sobre como instalar o Python em seu ambiente local ou rodar os Jupyter Notebooks usando o Google Colaboratoy.

- [Material Complementar](material_extra/Material_Complementar.pdf): Esse arquivo contém uma breve descrição teórica sobre alguns assuntos que serão abordados para facilitar a compreensão das aulas.

- [Cheat Sheet](material_extra/Cheat_Sheet.pdf): Arquivo de suporte com alguns comandos que são frequentemente utilizados para diferentes bibliotecas do Python


### Grupo no Discord

Se quiser tirar dúvidas ou dar sugestões temos um grupo no discord aberto para receber essas questões chamado de [Curso Python 2022](https://discord.gg/BgUqsSc4uV).

### Notas importantes

**Dados externos**: Os dados que são utilizados nessas aulas podem ser obtidos a partir do [link do Google Drive](https://drive.google.com/drive/folders/1hmcwi8subJuCai1fo3DwR3dx7nKg-JPQ?usp=sharing). Para rodar os notebooks com sucesso é importante atualizar os caminhos conforme cada notebook
 
**Execução dos notebooks**: Os notebooks foram escritos para serem rodados dentro do Google Colaboratory, caso você não vá utilizar esse recurso e prefere rodar localmente no seu ambiente linux ou windows é importante remover as células que contém:

```python
from google.colab import drive
drive.mount('/content/drive')
```
