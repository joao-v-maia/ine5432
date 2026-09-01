# O processo de tradução

Traduzir pode ser entendido como realizar uma transformação equivalente entre linguagens. Você tem um texto (ou código) em uma certa linguagem e quer transformar para outra linguagem, de forma que a sintaxe seja alterada para acompanhar a nova linguagem mas a semântica se mantenha.

Na computação temos processos de tradução sendo utilizados em diversos softwares, como interpretadores, montadores, pré-processadores e compiladores.

# Introdução a compiladores

Podemos dizer que o compilador é um software que traduz um código de uma linguagem fonte (normalmente linguagens de programação) para uma linguagem objeto (normalmente linguagem de máquina do processador alvo), e esse processo de tradução possui diversas etapas diferentes, sendo que o funcionamento de cada etapa pode variar conforme a implementação do compilador.

# Estrutura geral do compilador

Como dito antes, o compilador possui diversas etapas com papéis diferentes, no geral podemos definir 2 partes, análise e síntese, que são novamente divididas em 3 etapas para cada parte.

## Análise

1. Léxica
2. Sintática
3. Semântica

## Síntese

1. Código intermediário
2. Otimização
3. Código final