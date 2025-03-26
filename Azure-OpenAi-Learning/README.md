# Experiências com Azure OpenAI e GitHub Copilot

Este repositório documenta os testes realizados utilizando o GitHub Copilot para transcrição e tradução de texto a partir de imagens. Abaixo estão os resultados de três testes distintos.

## Teste 1: Transcrição de Texto em Português

Para o primeiro teste, utilizei a imagem abaixo:

![Texto](./inputs/TrancriptText.png)

Após carregar a imagem, solicitei ao Copilot que transcrevesse o texto contido na imagem. O resultado foi uma transcrição perfeita em português de todo o conteúdo.

![Resultado da Transcrição](./assets/transcript.png)

## Teste 2: Transcrição e Tradução de Texto em Japonês

No segundo teste, utilizei a imagem abaixo:

![Texto em Japonês](./inputs/TranslateImage.png)

Solicitei ao Copilot que transcrevesse e traduzisse o texto japonês para o português, o que foi feito com muita eficiência.

![Prompt](./assets/prompt.png)
![Resposta](./assets/awnser1.png)

## Teste 3: Transcrição de Texto com Caracteres Não Convencionais

Para o terceiro teste, utilizei a imagem abaixo, contendo texto com letras não convencionais, recortadas de um jornal:

![Texto Não Convencional](./inputs/NonConventionalCharacteres.png)

Neste teste, o Copilot não conseguiu executar a transcrição, possivelmente devido a um bloqueio existente para esse tipo de tarefa.

![Falha](./assets/fail.png)
