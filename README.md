# Análise dos dados da Libertadores da América de 2011 a 2023

A Copa Libertadores da América, principal torneio de clubes da América do Sul, é palco de grandes jogos que atraem milhões de fãs em todo o mundo. De 2011 a 2023, essa competição proporcionou grandes emoções, com momentos de glória, drama e surpresa. Neste estudo, vamos realizar uma análise abrangente dos dados da Copa Libertadores durante esse período de treze anos, explorando tendências, padrões e insights que ajudarão a enender o sucesso das equipes, as dinâmicas de desempenho e as características distintivas da maior competição de futebol do continente sul-americano. Ao aprofundar nos dados, buscou-se obter uma análise mais ampla da competição e identificar padrões de desempenho da competição.

## Dicionário de dados

_Edition_: Edição de disputa da competição
_Round_: Fase do torneiro
_Date_: Data da partida
_Home Club_: Nome do time mandante
_Away Club_: Nome do time visitante
_Home Score_: Quantidade de gols do time mandante
_AwayScore_: Quantidade de gols do time visitante

## Fonte dos dados
Os dados estão disponíveis no Kaggle no link: https://www.kaggle.com/datasets/ernestonlm/conmebol-libertadores-results-from-2011-to-2022

## Questions & Answers
### 1 - Qual o time que mais disputou a Libertadores nesse período?
Time com mais jogos: Boca Juniors - 111 jogos

### 2 - Qual a distribuição histórica dos resultados? E por fase da competição?
![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/58662eda-9e8e-4a25-baa6-1ec0045c3930)
#### Análise:
Aqui é evidente a influência dos times da casa no resultado final da partida. São apresentadas abaixo alguns possíveis motivos para o resultado sempre ser positivo para o time mandante.

1 - Apoio da Torcida: Os times mandantes contam com o apoio de seus torcedores, criando um ambiente de total incentivo e pressão sobre os adversários.

2 - Familiaridade com o estádio e condições locais: Os times mandantes geralmente estão acostumados com o estádio onde jogam assim como com as condições locais, como o clima, torcida e o gramado.

3 - "Fator Campo": Os times da casa conseguem impor seu estilo de jogo e controlar o ritmo da partida, se aproveitando desse conhecimento de campo e das condições já destacadas acima.

4 - Viagens e Desgaste: Os times visitantes enfrentam longas viagens antes dos jogos e muitas horas de aeroporto e translado, o que pode resultar em cansaço e desconforto resultando em um possível desgaste dos atletas.

5 - Pressão: Jogar como visitante na Libertadores pode gerar uma pressão psicológica adicional sobre os jogadores, especialmente em estádios lotados e hostis. Essa pressão pode afetar o desempenho dos jogadores visitantes e beneficiar os times da casa.

![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/8138f7f4-ef3f-4d4d-bd64-02d6753b8629)
#### Análise: 
Aqui também é evidente que o fator casa é importante, independente da fase da competição. O que pode se descar é que a vitória dos times visitantes são muito concentradas na fase de grupos do torneio.

### 3 - Qual o percentual de vitórias por país?
![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/2c917e7f-1382-4d45-9427-27e936b56336)
#### Análise:
Os times brasileiros e argentinos têm historicamente dominado a Copa Libertadores, o principal torneio de clubes da América do Sul, por algumas razões:

1 - Tradição e História: Tanto o Brasil quanto a Argentina têm uma rica tradição no futebol, com clubes que têm uma longa história de sucesso tanto em nível nacional quanto internacional. Essa tradição cria uma cultura de excelência e aspirações de vitória em competições como a Libertadores.

2 - Investimento Financeiro: Os clubes brasileiros e argentinos têm recursos financeiros significativos em comparação com outros clubes sul-americanos. Isso permite que eles contratem jogadores de alto nível, técnicos experientes e invistam em infraestrutura e desenvolvimento de jovens talentos.

3 - Profissionalismo e Estrutura Organizacional: Os clubes brasileiros e argentinos têm uma estrutura organizacional profissionalizada, com gestão eficiente, academias de base bem estabelecidas e uma infraestrutura sólida de apoio aos jogadores. Isso contribui para um ambiente propício ao desenvolvimento e sucesso no futebol.

4 - Competições internas fortes: As ligas brasileira e argentina são consideradas duas das mais competitivas da América do Sul. Os clubes que competem nessas ligas enfrentam regularmente desafios intensos, o que os prepara bem para competições internacionais como a Libertadores.

5 - Cultura do Futebol: Tanto no Brasil quanto na Argentina, o futebol é uma paixão nacional. Esse sentimento cria um ambiente onde os jogadores são incentivados a alcançar o mais alto nível de desempenho, e os clubes são motivados a buscar sucesso em todas as competições em que participam.

6 - Histórico de Sucesso: O sucesso passado dos clubes brasileiros e argentinos na Libertadores alimenta a crença de que eles podem vencer novamente. Isso cria uma mentalidade vencedora e uma pressão adicional para manter a tradição de excelência.

### 4 - Quais os países que mais tiveram times participando do torneio?
![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/9f1d6cc3-c157-4669-8b25-0ec0b7e921e5)
#### Análise: 
Novamente é evidenciado a tradição dos times argentinos e brasileiros na competição, fatores que influenciam essa supremacia foram mostrados já acima.

### 5 - Quais os times que mais somaram pontos nessas últimas edições de Libertadores?
Time          Pontuação
Boca Juniors      270
River Plate       268
Palmeiras         256
Nacional          234
Grêmio            224
Atlético Mineiro  222
Flamengo          218
Cerro Porteño     214
Libertad          196
Olimpia           192
Emelec            90
#### Análise:
Quando se fala em Copa Libertadores da América não há como não se lembrar do Boca e do River. Os dados mostram o quanto esses dois clubes argentinos são tão tradicionais e tão temidos pelos seus adversários continentais e muito isso se explica por:

1 - História e tradição: Ambos os clubes têm uma rica história no futebol argentino e sul-americano. Boca Juniors e River Plate acumularam ao longo dos anos uma vasta coleção de títulos nacionais e internacionais.

2 - Grande base de torcedores: Boca e River possuem algumas das maiores e mais apaixonadas bases de torcedores no futebol mundial.

3 - Investimento financeiro: São clubes financeiramente mais sólidos da Argentina, com capacidade para investir em infraestrutura, contratação de jogadores de alto nível e desenvolvimento de suas categorias de base.

### 6 - Quais os países que mais pontuaram nessas últimas edições de Libertadores?

         Time  Pontuação
0      Brasil       2122
1   Argentina       1848
2    Paraguai        742
3    Colômbia        666
4       Chile        580
5     Uruguai        546
6     Bolívia        534
7     Equador        526
8        Peru        466
9   Venezuela        440
10     México        288

#### Análise:
É importante pontuar para essa análise que os times mexicanos não são mais convidados à participar da Libertadores desde 2016, o que justifica a posição do país no quadro acima.

### 7 - Qual a distribuição de pontos conquistados pelas equipes de cada país por temporada?
![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/3c5bf32b-4202-427b-ade0-fd3218a267f2)
#### Análise:
Nesse gráfico é também visivel como Argentina e Brasil se descatacam ao longo dos anos perante os outros times da América do Sul. Os fatores para tentar explicar esse comportamento já foram citados anteriormente.

### 8 - Quais os placares mais comuns dos jogos analisados?
![image](https://github.com/luanrossini/analise_liberadores/assets/119509335/995406d1-24ac-4019-980a-fe08a0123fbd)
#### Análise:
Os placares mais comuns das partidas tendem a ser os placares mais "apertados". Com no máximo dois gols de diferença, mostra que a competição tem um alto nível de competitividade e os duelos tendem a ter poucas goleadas ou muitos gols na mesma partida.

# Conclusão
Após uma análise abrangente dos dados da Copa Libertadores da América de 2011 a 2023, fica clara a hegemonia dos times brasileiros e argentinos em relação às equipes do restante da América do Sul.

Os padrões identificados nos dados revelam aspectos interessantes sobre o desempenho das equipes ao longo do tempo. A disparidade entre vitórias em casa e fora destaca o papel crucial do apoio da torcida e do "fator campo" na determinação dos resultados. Além disso, os placares mais "apertados" são frequentes na competição, refletindo a intensidade e equilíbrio dos jogos.

Além disso, é interessante também analisar que os placares mais "apertados" são os que mais acontecem na competição. Vitórias por no máximo 2 gols de diferença são os resultados finais mais frequentes.

Os números também evidenciam a ampla influência dos clubes brasileiros e argentinos na Copa Libertadores. Com mais times participantes e uma soma significativa de pontos ao longo dos anos, esses dois países reafirmam sua tradição e domínio no torneio. Esse sucesso é impulsionado pelo investimento financeiro e pela estrutura organizacional dos clubes, que geram retornos consistentes em forma de desempenho e títulos.

Este estudo não apenas destaca a importância da Copa Libertadores como um símbolo de identidade e unidade latino-americanas, mas também ressalta o crescente domínio dos times brasileiros e argentinos em relação aos seus concorrentes regionais.






