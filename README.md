# SOBRE

Este projeto é utilizado para reaproveitar o arquivo .pt (modelo treinado) gerado após treinamento realizado no Google Colab.
O treinamento deve ser realizado no Google Colab, pois ele disponibiliza uma GPU eficiente para tal, porém, as inferências
podem ser realizadas em qualquer PC.

## COMANDOS

Detectar imagens contidas na pasta /test, utilizando o last.pt

```python detect.py --weights weights/last.pt --source=./test --names=./train/roboflow_data.names```

## TESTES

Para a realização de testes, existem imagens na pasta *test* que não estão presentes na base usada para treinamento, logo
pode-se garantir a ausência de vícios.