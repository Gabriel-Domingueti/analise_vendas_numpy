# Análise de Performance de Vendas com NumPy

Este projeto faz parte do meu roadmap de estudos para **Analista de Dados**. Utilizei o dataset "Sample Sales Data" do Kaggle para demonstrar habilidades fundamentais de manipulação e limpeza de dados usando Python.

## Tecnologias e Conceitos
- **Python 3**: Linguagem base.
- **NumPy**: Processamento vetorial, tratamento de arrays e estatística descritiva.
- **GitHub**: Controle de versão e documentação de portfólio.

## Resultados da Análise
Abaixo estão os indicadores extraídos diretamente do arquivo bruto:
- **Faturamento Total**: $ 8.290.886,79
- **Média por Venda**: $ 2.936,91
- **Maior Venda Unitária**: $ 9.048,16

## Processo de Dados (Data Cleanup)
Para garantir a precisão dos números, segui os seguintes passos:
1. **Tratamento de Encoding**: Correção de erro de leitura (Latin-1) para carregar o CSV corretamente.
2. **Filtragem de Erros**: Uso de máscaras booleanas para garantir que apenas vendas com quantidades e preços positivos fossem processadas.
3. **Vetorização**: Cálculos matemáticos realizados sem o uso de loops `for`, garantindo máxima performance.