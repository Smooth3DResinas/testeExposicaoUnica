# Testes de exposição de resinas

Aqui iremos explicar como realizar os testes de exposição das resinas **Smooth3D** utilizando o arquivo padrão de calibração.

<p align="center">
  <img src="https://github.com/Smooth3DResinas/testeExposicaoUnica/blob/main/readme/calibration.png" />
</p>

# Como imprimir:

Você deve baixar o arquivo de calibração [calibraçãoSmooth3D.stl](https://github.com/Smooth3DResinas/testeExposicaoUnica/raw/main/calibra%C3%A7%C3%A3oSmooth3D.stl) e ajustar os tempos de exposição em seu software fatiador de acordo com a tabela no link abaixo:

:blue_book: [Tabela de tempos de exposição](https://github.com/Smooth3DResinas/testeExposicaoUnica/blob/main/readme/CatalogoResinasSmooth3D.pdf)

# Analisando os resultados:


## Sub Exposição 
* Ocorre quando o tempo de exposição a luz UV das camadas normais está abaixo do recomendado
1. Os recursos encolherão criando algum espaçamento entre os elementos.
2. Alguns elementos não serão impressos ou aparecerão falhados.
3. No geral, os elementos vão parecer mais finos que o normal.

## Sobre Exposição 
* Ocorre quando o tempo de exposição a luz UV das camadas normais está acima do recomendado
1. Os recursos se expandirão e irão se sobrepor ao elemento vizinho mais próximo.
2. Os menores recursos podem ser impressos (devido expansão e mais pixels curados).
3. No geral, parecerá gordo e largo.

## Exposição Ideal:
1. Os recursos parecem iguais em comparação com a visualização.
2. Os espaçamentos são perfeitos (sem reduzir ou expandir para o vizinho)
3. Os menores recursos estão faltando (é muito difícil curar um único pixel sem sobre exposição).
4. No geral, parece nítido e preciso.

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

## Outros problemas de impressão:

| PROBLEMA                                                                                           | CAUSAS                                       | SOLUÇÕES                                                     |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------ |
| A peça não aderiu a base de impressão e ficou uma placa no fundo do tanque de resina.              | Nivelamento da mesa de impressão.            | Repetir/Revisar o processo de nivelamento da mesa            |
|                                                                                                    | Tempo de exposição das camadas de base baixo | Aumentar o tempo de exposição das camadas de base            |
|                                                                                                    | Base de impressão com pouca aderência        | Lixar a base de impressão com lixa 80 para metais            |
| Uma parte da peça aderiu a base de impressão e a outra parte ficou no fundo do tanque de impressão | Tempo de exposição das camadas normais baixo | Aumentar o tempo de exposição das camadas de base            |
|                                                                                                    | Configuração inadequada de suportes          | Revisar o posicionamento da peça e a configuração de suporte |
|                                                                                                    | Velocidade de elevação da mesa de impressão  | Diminuir a velocidade de elevação da mesa de impressão       |
| A peça aderiu a base de impressão e ficou muito difícil de removê-la                               | Tempo de exposição das camadas de base alto  | Diminuir o tempo de exposição das camadas de base.           |

