# Testes de exposição de resinas

Aqui iremos explicar como realizar os testes de exposição das resinas **Smooth3D** utilizando o arquivo padrão de calibração.

<p align="center">
  <img src="https://github.com/Smooth3DResinas/testeExposicaoUnica/blob/main/readme/calibration.png" />
</p>

## Como imprimir:

Você deve baixar o arquivo de calibração [calibraçãoSmooth3D.stl](https://github.com/Smooth3DResinas/testeExposicaoUnica/raw/main/calibra%C3%A7%C3%A3oSmooth3D.stl) e ajustar os tempos de exposição em seu software fatiador de acordo com a tabela abaixo.

## Referência de tempos de exposição:

| Resina          | Tempo camadas de base (MONO) | Tempo camadas normais (MONO) | Tempo camadas de base (RGB) | Tempo camadas normais (RGB) |
| --------------- | ---------------------------- | ---------------------------- | --------------------------- | --------------------------- |
| Padrão          | 20s                          | 2.5s                         | 100s                        | 5s                          |
| Bow             | 15s                          | 1.2s                         | 60s                         | 2.5s                        |
| Action          | 15s                          | 1.7s                         | 80s                         | 5s                          |
| 4k              | 15s                          | 1.3s                         | 80s                         | 4s                          |
| Modelismo       | 15s                          | 1.5s                         | 80s                         | 5s                          |
| D20             | 20s                          | 2s                           | 80s                         | 6s                          |
| ART ABS Like    | 15s                          | 1.3s                         | 80s                         | 4s                          |
| Semi-Flexível   | 15s                          | 1.5s                         | 80s                         | 5s                          |
| IMPACT Robótica | 10s                          | 1s                           | 60s                         | 2.5s                        |

# Analisando os resultados:

> Caso não obtenha o resultado esperado nos primeiro testes, repita o processo quantas vezes forem necessárias até chegar na configuração ideal.

## Sub Exposição 
* Ocorre quando o tempo de exposição a luz UV das camadas normais está abaixo do recomendado.
1. Os recursos encolherão criando algum espaçamento entre os elementos.
2. Alguns elementos não serão impressos ou aparecerão falhados.
3. No geral, os elementos vão parecer mais finos que o normal.
4. Quando isso acontecer, aumente em aproximadamente 10% o tempo de exposição das camadas normais e refaça a impressão.  

## Sobre Exposição 
* Ocorre quando o tempo de exposição a luz UV das camadas normais está acima do recomendado.
1. Os recursos se expandirão e irão se sobrepor ao elemento vizinho mais próximo.
2. Os menores recursos podem ser impressos (devido expansão e mais pixels curados).
3. No geral, parecerá gordo e largo.
4. Quando isso acontecer, diminua em aproximadamente 10% o tempo de exposição das camadas normais e refaça a impressão.  

## Exposição Ideal:
1. Os recursos parecem iguais em comparação com a visualização.
2. Os espaçamentos são perfeitos (sem reduzir ou expandir para o vizinho)
3. Os menores recursos estão faltando (é muito difícil curar um único pixel sem sobre exposição).
4. No geral, parece nítido e preciso.

## Resolução de problemas:

Se não conseguiu imprimir o arquivo de calibração recomendamos que leia nosso tópico sobre [resolução de problemas.](https://github.com/Smooth3DResinas/Resolucoes)

# Exemplos:

### Espirais:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_spirals.png?raw=true)

### Barras Zebra:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_bars.png?raw=true)

### Pilares:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_pillars.png?raw=true)

### Texto:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_text.png?raw=true)

## Amostra:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/exemplo.jpg?raw=true)
