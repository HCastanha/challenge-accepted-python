### O Desafio

- Ler dois arquivos NetCDF com dados de temperatura, sendo um com *dados de previsão* e o outro com *dados observados*;
- Calcular o índice RMSE para cada intervalo de 6 horas na série temporal em todos os pontos da matriz;

<img src="https://i.imgur.com/MlK4w0X.png" alt="RMSE - Root Mean Square Error" />

- Plotar mapas de duas dimensões do índice de cada período e um gráfico da série temporal do mesmo índice para São Paulo (Latitude **-23.5489** e Longitude **-46.6388**, correspondente ao ponto Y: **8** e X: **26** na grade da matriz dos dados);
- Crie um arquivo PROJECT.md com descrições de todos os passos para instalação e utilização do seu software;
- Escrever o resultado do cálculo do índice em um arquivo NetCDF (**Opcional**).

### Proposta de Resolução ao Desafio

Arquivo ipynb atendendo às demandas enunciadas no [README.md](../README.md) e supra replicadas.

### Dependências

- netcdf4
- numpy
- pandas


### Sobre arquivos netCDF

- Tipo comummente utilizado na comunidade científica para dados georreferenciados
- Suporte a referenciamento geográfico, bem como a séries temporais
- Ótima pedida para dados meteorológicos, portanto


### 