Sistema de Recomendação por Imagens Digitais

Este repositório apresenta o desenvolvimento de um sistema de recomendação de imagens baseado em similaridade, utilizando aprendizado de máquina e redes neurais convolucionais. O projeto tem como objetivo permitir que, dado uma imagem de consulta, sejam retornadas as imagens mais semelhantes presentes no banco de dados.

Funcionalidades

Indexação de imagens: Extração de características de imagens utilizando o modelo VGG16 pré-treinado.

Recomendação baseada em similaridade: Cálculo da similaridade por cosseno para sugerir as imagens mais similares à consulta.

Exibição visual: Visualização da imagem de consulta ao lado das recomendações geradas.

Tecnologias Utilizadas

Python 3.8+

TensorFlow / Keras

Matplotlib

Scikit-learn

PIL (Python Imaging Library)

Estrutura do Projeto

Carregamento do Modelo: Utiliza o modelo VGG16 pré-treinado para extrair características de imagens.

Indexação das Imagens: Organização do banco de dados em classes e extração de vetores característicos.

Sistema de Recomendação: Retorna as imagens mais similares com base na similaridade por cosseno.

Visualização dos Resultados: Apresenta os resultados de forma intuitiva e visual.

Como Executar

Clone o repositório.

Insira o dataset de imagens no diretório apropriado, organizado em subpastas por classes (e.g., "cadeiras", "relógios").

Ajuste o caminho para o dataset e para a imagem de consulta no código.

Execute o script principal para visualizar os resultados.

Aplicabilidade

Este sistema pode ser usado em aplicações de e-commerce, galerias de imagens, e plataformas de busca visual, promovendo experiências personalizadas para os usuários.
