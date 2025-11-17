# Classificador de Sentimento com BERT (Tópico: Onça)

O projeto consiste em um pipeline de Deep Learning que realiza o fine-tuning do modelo **BERTimbau** (`neuralmind/bert-base-portuguese-cased`) para classificar comentários de notícias em três categorias de sentimento: **Positivo**, **Negativo** e **Neutro**.

## Conteúdo

* `classificador-comentarios-video-onça.ipynb`: O notebook completo contendo todo o código, desde a preparação dos dados até o treinamento e avaliação do modelo.

## Como Executar

Como este projeto foi desenvolvido no Google Colab, a maneira mais fácil de executá-lo é:

1.  Baixe o arquivo `.ipynb` deste repositório.
2.  Acesse o [Google Colab](https://colab.research.google.com/).
3.  Faça o upload do arquivo.
4.  No menu do Colab, vá em **Ambiente de execução** > **Alterar o tipo de ambiente de execução** e certifique-se de selecionar **T4 GPU** para acelerar o treinamento.
5.  Execute as células sequencialmente.

## Tecnologias Utilizadas

* Python
* PyTorch
* Transformers (Hugging Face)
* Scikit-learn
* Pandas
