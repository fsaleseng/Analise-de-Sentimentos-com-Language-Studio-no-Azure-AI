# Análise de Frases no Azure

Este repositório contém um documento de texto com algumas sentenças. Utilizaremos o Azure Text Analytics para realizar uma análise de sentimentos dessas sentenças.

## Como funciona

1. **Preparação dos Dados**: As sentenças são pré-processadas para remover quaisquer caracteres especiais e garantir a consistência dos dados.
2. **Conexão com o Azure**: Estabelecemos uma conexão com a API do Azure Text Analytics para enviar as sentenças para análise.
3. **Análise de Sentimentos**: Utilizamos a funcionalidade de análise de sentimentos do Azure para determinar o sentimento de cada sentença.
4. **Resultados**: Os resultados da análise são armazenados e podem ser visualizados para compreender o sentimento geral das sentenças.

## Executando a Análise

1. Certifique-se de ter uma conta válida no Azure e acesso à API do Text Analytics.
2. Execute o código fornecido neste repositório para iniciar a análise.
3. Analise os resultados para obter insights sobre o sentimento das sentenças.

## Arquivos

- **sentencas.txt**: O documento de texto contendo as sentenças a serem analisadas.
- **azure_analysis.py**: O script Python utilizado para realizar a análise no Azure.
- **resultados_sentimentos.csv**: O arquivo CSV contendo os resultados da análise de sentimentos.

## Recursos Adicionais

- [Azure Text Analytics](https://azure.microsoft.com/services/cognitive-services/text-analytics/)
- [Documentação do Azure Text Analytics](https://docs.microsoft.com/azure/cognitive-services/text-analytics/)

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias ou novas funcionalidades.

