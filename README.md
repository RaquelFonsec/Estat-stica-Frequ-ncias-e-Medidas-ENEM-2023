# Estatística Frequências e Medidas - WOMANKERSCODE

Este projeto aborda análises estatísticas utilizando a base de dados fictícia do ENEM 2023. O objetivo é extrair informações relevantes para alinhar estratégias de ensino em um cursinho preparatório para estudantes que desejam ingressar na universidade em 2025.

- **Base de Dados:** [enem_2023.json](https://import.cdn.thinkific.com/401289/gQbVuYr9TaimUX9dQAqV_enem_2023.json)
- **Número de Registros:** 1000 estudantes

## Dados
O conjunto de dados possui 6 colunas, sendo 5 delas representando as disciplinas do ENEM e uma representando o gênero dos participantes. Cada linha representa um estudante, totalizando 1000 entradas.

## Perguntas a serem Respondidas

1. **Amplitude de Nota por Disciplina:**
   - Qual das disciplinas tem a maior amplitude de nota?

2. **Média e Mediana por Disciplina:**
   - Qual é a média e a mediana para cada uma das disciplinas? (Lembre-se de remover todos os valores nulos ao considerar a mediana)

3. **Ciência da Computação - Peso nas Disciplinas:**
   - Considerando o curso de Ciência da Computação da UFPE, com pesos para cada disciplina, qual o desvio padrão e média das notas dos 500 estudantes mais bem colocados?

4. **Vagas em Ciência da Computação:**
   - Se todos esses estudantes aplicassem para Ciência da Computação e existem apenas 40 vagas, qual seria a variância e média da nota dos estudantes que entraram no curso?

5. **Terceiro Quartil para Matemática e Linguagens:**
   - Qual é o valor do teto do terceiro quartil para as disciplinas de Matemática e Linguagens?

6. **Histogramas e Simetria:**
   - histograma de Redação e Linguagens, de 20 em 20 pontos. Podemos dizer que são histogramas simétricos? 

7. **Histograma com Range Fixo:**
   - colocar um range fixo de 0 até 1000, observar se  tem a mesma opinião quanto à simetria? (`plt.hist(dado, bins=_, range=[0, 1000])`)

8. **Boxplot de Ciências da Natureza e Redação:**
   -  boxplot do quartil de todas as disciplinas de Ciências da Natureza e Redação. É possível enxergar outliers? Utilizado o método IQR.

9. **Remoção de Outliers:**
   - Remover todos os outliers e verificar se eles são passíveis de alterar a média nacional significativamente. Considere significativamente um valor acima de 5%.

10. **Substituição de Valores Nulos:**
    - Considerando valores nulos, tentar encontrar qual seria a melhor medida de tendência que pode substituir as notas nulas. Média, moda ou mediana? Substituir o valor por todos os três e dizer qual delas altera menos a média geral e o desvio padrão.

Fique à vontade para explorar, analisar e contribuir para este projeto. Boa análise estatística!
## Como Executar

1. Clone o repositório para o seu ambiente local:

    ```bash
    git clone https://github.com/RaquelFonsec/Estat-stica-Frequ-ncias-e-Medidas-ENEM-2023.git
    ```

2. Instale as dependências necessárias:

    ```bash
    pip install -r requirements.txt
    ```

3. Execute o script principal:

    ```bash
    python seu_script.py
    ```

Certifique-se de ter o Python e o pip instalados antes de prosseguir.



---
