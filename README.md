# Guia de Execução: Projeto Rock, Paper, Scissors

Este repositório implementa um projeto de aprendizado profundo baseado no capítulo 6 do livro *Deep Learning with PyTorch Step-by-Step*.

---

## Requisitos

Antes de iniciar, certifique-se de ter instalado:

- Python 3.7+
- PyTorch
- Bibliotecas adicionais: `torchvision`, `matplotlib`

Instale as dependências com:
```bash
pip install -r requirements.txt
```

---

## Estrutura do Repositório

- **`colab_script.ipynb`**: Notebook completo com o código comentado e organizado.
- **`src/`**: Pasta contendo os módulos auxiliares do projeto.
- **`data/`**: Contém os datasets utilizados (substituir conforme necessidade).

---

## Passos para Execução

1. **Configuração dos Dados:**
   - Coloque os dados nas pastas `data/rps` e `data/rps-test-set`.
   - Certifique-se de que os arquivos de imagem estejam organizados em subpastas por classe.

2. **Executar o Notebook:**
   - Abra o arquivo `colab_script.ipynb` no Google Colab ou Jupyter Notebook.
   - Siga as seções para reproduzir o experimento.

3. **Treinamento e Avaliação:**
   - O notebook inclui treinamento com scheduler de learning rate e análise de gradientes.

4. **Visualizações:**
   - Apresente gráficos de perda e gradientes para compreender o desempenho do modelo.

---

## Resultados

- **Melhor taxa de aprendizado:** Determinada pelo teste de intervalo (visualizado no notebook).
- **Scheduler Cíclico:** Ajusta dinamicamente o `learning rate`, promovendo convergência.
- **Visualização de Gradientes:** Insights sobre como o modelo aprende ao longo do treinamento.

---

## Referências

- Livro: *Deep Learning with PyTorch Step-by-Step* por Daniel Voigt Godoy
- Repositório de Referência: [https://github.com/emelynfreire/DeepLearningwithPyTorch](https://github.com/emelynfreire/DeepLearningwithPyTorch)

