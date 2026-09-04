# O Lutador

O Lutador é classe de personagem que empunha armas e escudos e faz deles suas ferramentas de combate. Lutadores são especialistas no combate corpo-a-corpo ou no manuseio de arcos e balestras e possuem diversas maneiras de serem construídos. A escolha dos talentos do Lutador pode fazê-lo um ladrão furtivo que mata sem ser percebido, um bárbaro furioso capaz de derrubar opositores de qualquer tamanho com sua força bruta, um guerreiro envolto por uma carapaça metálica impenetrável que tem a voz sempre abafada por seu nobre helmo ou até mesmo um atirador com olhos de águia que atinge inimigos a grandes distâncias.

A escolha do tipo de arma com a qual um Lutador enfrentará suas ameaças é o pilar que sustenta esta classe. A escolha de uma arma média, grande ou de projétil determinará quais os efeitos que um Lutador poderá causar em seus inimigos por meio de **manobras de combate** e a escolha de uma arma específica dentro dessas categorias permitirá ao combatente causar cortes, perfurações ou contusões em seus inimigos, seja buscando por vulnerabilidades a certo tipo de ataque ou para contornar defesas específicas de seus alvos.

Em questão de proteção, Lutadores podem ser treinados no uso de armaduras leves, médias ou pesadas. É importante lembrar que a defesa ofertada por cada equipamento é inversamente proporcional a movimentação que ele permite e também a taxa de sucesso em proezas de **agilidade** e **fortaleza**. Vale ressaltar que a utilidade de um escudo vai além de ter algo entre sua cara e um machado, seu escudo pode ser usado para golpear inimigos numa manobra de combate.


## Lista de Manobras

O que afeta a capacidade de um Lutador de realizar manobras de combate é a arma que eles empunham, algumas manobras podem ser realizadas independente da arma carregada, outras exigem que o Lutador esteja desarmado. Armas médias e grandes podem realizar as mesmas manobras, a diferença é que manobras que exigem precisão são mais fáceis de serem realizadas com armas menores.

**Manobras Independentes de Armas**

| Manobra  | Custos      |
| :------- | :---------: |
| Empurrão | 2 de fôlego |
| Rasteira | 5 de fôlego |

**Manobras de Armas Corpo-a-Corpo**

| Manobra          | Custos p/ armas médias | Custos p/ armas grandes |
| :--------------- | :--------------------: | :---------------------: |
| Golpe nas Pernas | 2 de fôlego            | 2 de fôlego             |
| Pose Defensiva   | 4 de fôlego            | 3 de fôlego             |
| Ripostar         | 7 de fôlego            | 8 de fôlego             |
| Provocar         | 10 de fôlego           | - de fôlego             |
| Desarme          | 12 de fôlego           | 12 de fôlego            |


**Manobras de Armas Corpo-a-Corpo por Tipo de Dano**

| Manobra            | Custos p/ armas médias | Custos p/ armas grandes |
| :----------------- | :--------------------: | :---------------------: |
| Corte Sangrento    | 3 de fôlego            | 4 de fôlego             |
| Pancada Deslocante | 3 de fôlego            | 2 de fôlego             |
| Pancada Atordoante | 5 de fôlego            | 6 de fôlego             |
| Estocada Firme     | 4 de fôlego            | 4 de fôlego             |

**Manobras de Armas de Projetil**

| Manobra                  | Custos            |
| :----------------------- | :---------------: |
| Tiro nas Pernas          | 2 de fôlego       |
| Arremessar Equipamento   | 4/8/12 de fôlego  |
| Cravar Dardo/Flecha      | 5 de fôlego       |
| Atirar duas Flechas      | 10 de fôlego      |
| Dardo Preciso            | 10 de fôlego      |
| Ricochete                | 10 de fôlego      |

## Efeitos das Manobras

=== "Independentes de Arma"

    **Empurrão**: Empurra um inimigo em 1 metro. Pode ser usada enquanto carrega coisas nas mãos. Mira a defesa de FORTALEZA, +2 de fôlego por metro extra empurrado com limite igual a FORTALEZA do Lutador.  
    *Escudos*: Causam 3 de dano ao realizar esta manobra.

    **Rasteira**: O alvo perde o apoio e cai ao chão. O alvo fica DERRUBADO e recebe 3 de dano contundente pela queda. Mira a defesa de AGILIDADE.
    *Armas longas*: Realizam esta manobra com +1 de alcance.

=== "Armas Corpo-a-Corpo"

    **Golpe nas Pernas**: Golpe que mira a Defesa de ARMADURA do alvo. Acerto causa 2 de dano a menos que um ataque normal e deixa o alvo LENTO por 1 turno. Crítico dobra o dano e deixa o alvo ALEIJADO por 1 turno.

    **Pose defensiva**: Firma os pés no chão e se prepara para receber um ataque. Com *armas médias* aumenta a Defesa de Armadura em **+1**, *armas grandes*, *escudo médio* e *broquel* em **+2** e *escudos grandes* **+3**. Para cada ponto em que o ataque inimigo superar sua armadura original se perde 1 ponto de fôlego, quando seu fôlego acabar a manobra e seus bônus acabam junto. Se um ataque superar sua armadura original em X e o seu fôlego restante for Y < X o ataque acerta, a não ser que ele seja o primeiro ataque após a realização da manobra.

    **Ripostar**: Usado como reação a um ataque inimigo que use algum tipo de arma corpo-a-corpo (gasta seu turno). Ataca Defesa de AGILIDADE do alvo e se acertar, rebate o ataque tornando o atacante ZONZO e concedendo um ataque imediato ao lutador que ripostou. Escudos e Rapieiras realizam esta manobra com vantagem menor.

    **Provocar**: Exclusivo para usuários de escudos médios ou grandes. Jogada modificada pelo atributo de CARISMA, mira Defesa de Vontade. Com golpes no escudo e palavras de provocação, faz com que todos os alvos até 2m de distância te ataquem em seus próximos turnos. 

    **Desarmar**: Tira a arma de um inimigo e a joga ao chão. Mira a defesa de AGILIDADE.

    **Corte Sangrento** Ataque que busca abrir um grande corte no inimigo. Acerto causa 2 de dano cortante a menos que um ataque normal e faz o indivíduo receber 2 de dano de sangramento por 2 turnos. Mira a defesa de AGILIDADE e a arma deve ser capaz de causar dano cortante para realizar esta manobra.  
    *Armas Médias*: +2 de fôlego por turno extra de duração.  
    *Armas Grandes*: +3 de fôlego por turno extra de duração.

    **Pancada Deslocante**: Porrada em um ângulo que busca deslocar o alvo. Acerto causa 2 de dano contundente a menos que um ataque normal e move o alvo 1 quadrado lateralmente. Mira defesa de FORTALEZA e a arma deve ser capaz de causar dano contundente para realizar esta manobra. O máximo que se pode mover um alvo é igual ao seu atributo de FORTALEZA.  
    *Armas Médias*: +3 de fôlego por metro extra de deslocamento.  
    *Armas Grandes*: +2 de fôlego por metro extra de deslocamento.

    **Pancada Atordoante**: Golpe que mira a cabeça do alvo com mais jeito que força. Acerto causa 2 de dano contundente a menos que um ataque normal e torna o alvo ZONZO por um turno. Mira a defesa de FORTALEZA e a arma deve ser capaz de causar dano contundente para realizar esta manobra. Escudos podem ser usados para realizar esta manobra.  
    *Armas Médias*: +3 de fôlego por turno extra de duração.  
    *Armas Grandes*: +2 de fôlego por turno extra de duração.  
    *Escudos*: +3 de fôlego por turno extra de duração.

    **Estocada Firme**: Ataque feito avançando em direção ao alvo, deve andar pelo menos um metro em direção ao alvo antes de realizar esta manobra. Escolhe mirar a Defesa de Armadura ou de FORTALEZA, se mirando a Defesa de Armadura um acerto causa +2 de dano, se mirando a Defesa de FORTALEZA um acerto causa -2 de dano e move o alvo 1 quadrado para trás. A arma deve ser de combate corpo-a-corpo média ou grande e capaz de causar dano perfurante. O máximo que se pode mover um alvo é igual ao seu atributo de FORTALEZA.  
    *Armas Médias e Grandes*: +3 de fôlego por metro extra de deslocamento.

=== "Armas de Projétil"

    **Tiro nas Pernas**: Golpe que mira a Defesa de ARMADURA do alvo. Acerto causa 2 de dano a menos que um ataque normal e deixa o alvo LENTO por 1 turno. Crítico dobra o dano e deixa o alvo ALEIJADO por 1 turno.

    **Arremessar Equipamento**: Devido ao treino de pontaria, atiradores são capazes de arremessar objetos com maior precisão. Essa manobra é usada principalmente para atirar granadas e equipamentos especiais contra inimigos, mas pode ser usada pra tacar até mesmo um tijolo. Gasta 4, 8 ou 12 de fôlego para receber +1, +2 ou +3, respectivamente, na jogada de arremesso.

    **Cravar Dardo/Flecha**: Saca um projétil e busca apunhalar as pernas de um inimigo adjacente. Mira a defesa de AGILIDADE, causa 3 + AGILIDADE de dano perfurante e deixa o alvo LENTO por um turno.

    **Atirar Duas Flechas**: Exclusivo para usuários de Arcos. Ataca simultaneamente dois alvos que devem estar dentro de um cone de base 11 com a ponta no atirador e não pode mirar 2 flechas num mesmo alvo. Mira a defesa de Armadura. Crítico dobra o dano para ambos os alvos.

    **Dardo Preciso**: Exclusivo para usuários de Bestas. Gasta fôlego para receber vantagem menor, pode gastar + 5 de fôlego para ganhar vantagem maior. Crítico **triplica** o dano.

    **Ricochete**: Exclusivo para usuários de Fundas. Gasta fôlego para realizar um ataque que se for bem sucedido ricocheteia para outro alvo a até 5m, o tiro ricocheteado perde 2 de dano no próximo alvo. Pode-se mirar novos alvos contanto que ainda haja dano a ser aplicado. Crítico dobra o dano no primeiro alvo, causa dano normal no segundo e passa a perder 2 de dano para cada alvo sucessivo.

