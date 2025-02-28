Você foi contratado para criar um sistema que realiza a classificação de imagens de frutas para uma empresa de e-commerce. O objetivo é que, ao enviar uma imagem, o sistema identifique se a fruta é uma maçã, uma banana ou uma laranja. Sabendo que você possui um banco de imagens já categorizado, explique quais tipos de redes neurais você utilizaria para resolver esse problema, como seria o processo de implementação utilizando Python e quais etapas principais precisam ser seguidas para treinar o modelo.

Padrão de Resposta para a Atividade:

Indicação clara do tipo de rede neural usada e justificativa do porquê de ser a escolha mais adequada;
- Vamos utilizar uma Rede Neural Convolucional (RNC), por uma série de motivos:
- Redes neurais convolucionais são capazes de extrair todo tipo de informação sobre imagens. Características como textura, bordas, cores, todas essas podem ser detectadas por esse tipo de rede.
- Diferentemente de outros tipos de rede (como MLP), elas reduzem a complexidade do problema aplicando filtros e tornando o processo mais eficiente.

Descrição do processo de pré-processamento das imagens;
- Vamos aplicar uma série de efeitos e processamento nas imagens.
- As imagens são separadas em conjunto de treino e conjunto de teste.
- As imagens são redimensionadas para terem o mesmo formato em forma reduzida.
- Os valores de cor dos pixels são normalizados para que fiquem entre 0 e 1.
- Também seria possível utilizar data augmentation, fazendo uso das mesmas imagens porém em ângulos e cores diferentes, melhorando a generalização do modelo.

Apresentação do modelo de rede neural em Python, com uma breve explicação de cada camada;

Compilação e treinamento do modelo, mencionando a função de perda e o otimizador usados;

Processo de avaliação e validação do modelo;

Conclusão explicando como o modelo resolverá o problema proposto.

### Dataset: Fruits-360 (modificado)

> Dataset contendo imagens de frutas e vegetais.

> O dataset foi modificado para incluir apenas imagens de maçãs, bananas e laranjas

> Ele contém variações de ângulo e rotação nas imagens das frutas

Disponível em: https://github.com/Horea94/Fruit-Images-Dataset