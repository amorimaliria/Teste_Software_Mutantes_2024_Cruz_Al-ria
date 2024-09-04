# Teste_Software_Mutantes_2024_Cruz_Aliria

## Alíria de Santana de Amorim Cruz

## Atividade 2 - Teste de Software 
### A atividade proposta envolve a execução de testes de mutação em um projeto Python, a análise dos resultados e a criação de um relatório detalhado. O objetivo é identificar e documentar os mutantes gerados, a partir de modificações no código original, e avaliar a eficácia dos testes de mutação. O relatório deve apresentar os resultados obtidos, incluindo a quantidade de mutantes mortos e vivos, bem como a análise dos testes e a interpretação dos resultados. 

### 1- Execução do roteiro do vídeo indicado
#### Etapa 1
Configuração do Ambiente:
    ◦ Instalar o Python 3.7+ e criar um ambiente virtual.
    ◦ Instalar as dependências: pytest, pytest-cov, mutmut.

#### Etapa 2
Execução da ferramenta pytest:
Esse comando executa os testes definidos no arquivo test_cal.py com um nível de detalhe elevado na saída dos resultados, útil para depuração e análise mais aprofundada dos testes.

---------- coverage: platform win32, python 3.11.4-final-0 -----------
Name     Stmts   Miss  Cover
----------------------------
cal.py     109     49    55%
----------------------------
TOTAL      109     49    55%

O resultado indica que 55% dos códigos foram cobertos pelos testes, o que é um indicador positivo para a qualidade dos testes.

#### Etapa 3
Execução dos testes de mutação:
Esse comando executa os testes de mutação sobre o código do arquivo cal.py e compara os resultados com os testes originais. O relatório de mutação é gerado automaticamente e pode ser analisado para avaliar a eficácia dos testes.

