# Computação clássica e quântica aplicadas ao mercado financeiro

Os códigos são relacionados ao nosso artigo que pode ser encontrado no link abaixo.

- <a href="https://www.dualq.tech/wp-content/uploads/DualQ_quantum-finance.pdf" target="_blank">LINK do artigo</a>

O repositório encontra-se organizado da seguinte forma: 

1- Um Jupyter notebook que explora a abordagem clássica (Markowitz) onde você poderá obter a Fronteira Eficiente para diversos ativos como: ações da B3, ações de empresas americanas (NYSE/NASDAQ), Criptomoedas etc; Conforme figura abaixo:

![picture](https://www.dualq.tech/wp-content/uploads/fronteira_vf4.png)

Bem como contém uma abordagem quântica de uma implementação simples do QAOA (Quantum Approximate Optimization Algorithm) com o Qiskit (IBM Q), podendo ser usado para o mesmo grupo de ativos e testado diretamente no Google Colab.

- <a href= "https://github.com/askery/computacao-quantica-aplicada-ao-mercado-financeiro/blob/main/Quantum_Finance_DualQ.ipynb" target="_blank">Notebook 1 - Implementação da abordagem clássica e uma pequena demonstração do QAOA com Qiskit</a>

2- Um Jupyter notebook que explora a abordagem quântica com o QAOA usando o myQLM com os mesmos ingredientes anteriores, onde exploramos mais profundamente a qualidade da solução e a covergência do QAOA em função do número de camadas.

- <a href= "https://github.com/askery/computacao-quantica-aplicada-ao-mercado-financeiro/blob/main/QAOA_myQLM.ipynb" target="_blank">Notebook 2 - implementação do QAOA com o myQLM</a>

# Sobre o myQLM.

Para instalação do myQLM recomendamos seguir a própria documentação do software, disponível em: 
<a href= "https://myqlm.github.io/myqlm_specific/install.html" target="_blank">Instalando o myQLM</a>

Dica: dada a compatibilidade com Python 3.9 (tanto no Linux como no Windows), primeiro nós criamos um ambiente com a referida versão (com o nome "myqlm") com o comando

```conda create -n myqlm python=3.9```

Ativamos o ambiente com o comando

```conda activate myqlm```

Então seguimos todos os passos de instalação da documentação do myQLM.
