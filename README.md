# Quanto tempo você já viveu?

Exercício de lógica de programação transformado em aplicativo web.

> **Enunciado:** Faça um programa que receba a idade de uma pessoa em anos, calcule e imprima essa idade em: Meses, Dias, Horas e Minutos.

## O que o app mostra
- **Entrada:** campo de idade com botões − / +, controle deslizante e exemplos rápidos, com validação (vazio, negativo, decimal, acima de 150).
- **Saída:** os quatro resultados com a conta que gerou cada um.
- **Como o programa pensa:** o fluxo Entrada → Processamento → Saída com os valores reais.
- **Código:** o mesmo algoritmo em Portugol Studio, Python e JavaScript, atualizado com a idade digitada.

## Regras de conversão
| De | Para | Conta |
|---|---|---|
| anos | meses | idade × 12 |
| anos | dias | idade × 365 |
| dias | horas | dias × 24 |
| horas | minutos | horas × 60 |

Anos bissextos não são considerados, como no enunciado.

## Publicar no GitHub Pages
1. Crie um repositório público e envie o arquivo `index.html` (e este README).
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Tudo está em um único arquivo (HTML + CSS + JavaScript), sem dependências para instalar.
