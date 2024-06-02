
# Análise de Imagens e Otimização de Rotas de Poda de Árvores

Este é um programa Python desenvolvido para analisar imagens contendo árvores, identificar as árvores na imagem e otimizar as rotas de poda para essas árvores.

## Funcionalidades

- **Pré-processamento da Imagem:** O programa realiza o pré-processamento da imagem para detectar as bordas e identificar os contornos das árvores.
- **Identificação de Árvores:** Utilizando técnicas de processamento de imagens, o programa identifica as árvores presentes na imagem.
- **Otimização de Rotas de Poda:** Com base nas localizações das árvores identificadas, o programa calcula a rota ótima para a poda das árvores, minimizando a distância percorrida.
- **Visualização das Árvores Identificadas:** O programa exibe visualmente as árvores identificadas na imagem, com a opção de salvar a imagem com as árvores identificadas.
- **Cálculo da Distância da Rota Ótima:** O programa calcula a distância total da rota ótima de poda para fornecer informações sobre a eficiência da rota.

## Requisitos

- Python 3.x
- OpenCV (opencv-python)
- NetworkX
- Matplotlib

Você pode instalar as dependências usando o comando:

```
pip install opencv-python networkx matplotlib
```

## Como Usar

1. Clone o repositório ou baixe o arquivo ZIP.
2. Certifique-se de ter o Python e as dependências instaladas em seu sistema.
3. Coloque a imagem que deseja analisar na mesma pasta que o script Python.
4. Execute o programa Python:
   ```
   python tree_pruning.py
   ```
5. O programa solicitará o caminho para a imagem de árvores que você deseja analisar. Insira o caminho da imagem quando solicitado.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de pull request para melhorar o código ou adicionar novas funcionalidades.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.
