# Microsoft Azure AI-900

## Criação de Modelo de regressão para previsão do aluguel de bicicletas
OBS.: foi necesssário contornar a origem dos dados, pois os passos oferecidos pela instrutora incorriam em erro de carregamento

Foi feito o envio do arquivo para o Azure
Utilizaram-se o modelo de Random Forest e LightGBM para realização da previsão com os seguintes parâmetros:
- 3 avaliações no máximo
- 3 nós no máximo
- Limite de pontuação da métrica de 0.085
- Validação por divisão de validação de treinamento
- Criação de um registro de modelo a partir do resultado do treinamento (Modelo / + Regustro / De uma saída de trabalho)
- Criação de um ponto de extremidade (apresentou erro, impossibilitando conseguir os pontos de extremidade)

## Reconhecimento de texto em imagens
- Imagem utilizada: [agile manifest.jpg](https://github.com/quintinomedeiros/ms_azure_ai_900/blob/main/agile_manifest.jpg)
- Texto transcrito: agile_manifest_transcricao.txt
