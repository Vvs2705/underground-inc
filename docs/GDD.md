# UNDERGROUND INC.
## Game Design Document — Versão de Produto

> **Revisão 2026-10-09 (comparativo de mercado):** comparativo com 7 idle de mineração (Idle Miner Tycoon, Gold and Goblins, Idle Zombie Miner, Drill & Collect, Deep Town, Mr. Mine, Tap Tap Dig 2) em [`COMPETITIVO.md`](COMPETITIVO.md). O que mudou, sem renumerar nem apagar nada:
> - **KPIs numéricos e kill criteria** que faltavam (novo **§56**): D1 ≥ 26%, D7 ≥ 5%, coorte de 1,5–2k installs, CPI ≤ US$0,70, cancelar só depois de 2 iterações (veredito de 2026-10-06).
> - **Escopo de MVP** (§51) de 2–3 semanas em 2D lateral; o resto deste documento passa a ser mapa de longo prazo.
> - **Guardrails:** 1 moeda no MVP (§21); offline com teto de 2 h a 50% (§22); nada aleatório pago (Mystery Wall com raio-X no §17, baús de conteúdo fixo no §37, ECA Digital); booster pago fora de corridas (§35); interstitial desligado na v0.1 (§36); bônus da mesma categoria somam (§46).
> - **O core ganha tensão** (§2, §15): profundidade não é exclusiva (Deep Town, Mr. Mine, Drill & Collect), e no Idle Miner toda camada é igual. Proposta: o veio com escolha.
> - **Novo §55 (Diferenciais competitivos)**, com os 3 primeiros: veio com escolha, sem parede de progressão provado pelo bot e parede com raio-X.
> - **Novo §57:** o que reaproveitar do núcleo do Forge Street (simulação por tick, bot, cofre, diário).

### 1. VISÃO

**Gênero:** Idle / Tycoon / Exploration / Collection

**Plataformas:** Android / iOS

**Orientação:** Portrait

**Modelo:** Free-to-Play.

**Fantasia central:**

Construir uma empresa de mineração que começa praticamente na superfície e desce cada vez mais fundo até descobrir cavernas, ruínas, criaturas, minerais impossíveis e segredos subterrâneos.

A pergunta central é:

**“O que existe mais abaixo?”**

---

# 2. DIFERENCIAL

A maioria dos jogos idle depende principalmente de números crescendo.

Underground Inc. adicionará uma motivação espacial extremamente clara:

**profundidade.**

0 m.

50 m.

100 m.

500 m.

1 km.

5 km.

10 km.

Cada grande marco revela um novo mundo.

> **Revisão 2026-10-09.** Profundidade é diferencial de **anúncio e de meta**, mas **não é exclusiva**: Deep Town, Dig Down: Idle Empire, Mr. Mine e vários jogos de "cavar" vendem a mesma pergunta (`COMPETITIVO.md` a). Também não é diferencial de **mecânica**: na estrutura do Idle Miner Tycoon, toda camada repete o mesmo loop (raia B da validação). O que nos separa precisa estar na decisão do jogador, e o §55 propõe isso. O principal é o **veio com escolha** (UG-1): cada camada nova mostra 2–3 veios no corte, e escolher qual abrir muda o perfil daquela camada.

---

# 3. PITCH

Perfure cada vez mais fundo, automatize sua operação, descubra minerais raros e transforme uma pequena escavação em um império subterrâneo.

---

# 4. PILARES

## Descoberta

Jogador sempre possui algo abaixo para alcançar.

## Automação

Operação começa manual.

Gradualmente torna-se máquina industrial.

## Crescimento visual

Mina precisa parecer cada vez maior.

## Coleção

Minerais.

Artefatos.

Máquinas.

Funcionários.

## Mistério

Ruínas e descobertas criam curiosidade.

---

# 5. GAMEPLAY VERTICAL

A mina será representada verticalmente.

Topo:

base.

Abaixo:

camadas.

Jogador pode deslizar pela mina.

Visualmente observamos:

elevadores;

mineradores;

trilhos;

máquinas;

veios minerais.

Esse scrolling vertical é parte importante da identidade.

---

# 6. CORE LOOP

Minerar

→

extrair minério

→

transportar

→

refinar

→

vender

→

ganhar dinheiro

→

melhorar máquinas

→

descer

→

descobrir recursos superiores

→

repetir.

---

# 7. SISTEMAS DE PRODUÇÃO

Cada camada possui cadeia:

### Extração

Minerador/máquina extrai.

### Transporte

Carrinho ou esteira leva minério.

### Elevador

Move minério verticalmente.

### Refinaria

Processa.

### Armazém

Mantém recursos.

### Venda

Gera cash.

Cada ponto pode ser gargalo.

Isso gera decisões reais.

---

# 8. PROFUNDIDADE

Profundidade é a progressão visual macro.

Exemplo:

0–100 m:

terra e carvão.

100–300 m:

ferro.

300–600 m:

cobre.

600–1.000 m:

ouro.

1–2 km:

cristais.

2–5 km:

cavernas antigas.

5–10 km:

minerais exóticos.

10 km+:

conteúdo fantástico.

Não precisamos obedecer geologia real.

---

# 9. BIOMAS

## Bioma 1 — Upper Mine

Terra.

Pedra.

Carvão.

## Bioma 2 — Iron Depths

Metal.

Calor.

## Bioma 3 — Crystal Caverns

Cristais.

Água.

## Bioma 4 — Ancient Ruins

Construções antigas.

Artefatos.

## Bioma 5 — Magma Core

Lava.

Minerais raros.

## Bioma 6 — Lost World

Ecossistema subterrâneo.

## Bioma 7+

Podemos extrapolar para ficção científica/fantasia.

---

# 10. MINERAIS

Raridades:

Common.

Uncommon.

Rare.

Epic.

Legendary.

Mythic.

Cada mineral entra na:

**Mineral Collection.**

Descobrir todos os minerais de um bioma concede bônus.

---

# 11. ARTEFATOS

Durante mineração, o jogador encontra:

fósseis;

relíquias;

objetos antigos;

máquinas abandonadas;

cristais especiais.

Artefatos são permanentes.

Alguns oferecem bônus.

Outros são colecionáveis.

---

# 12. MUSEU

Base pode conter:

**Underground Museum.**

Artefatos encontrados aparecem visualmente.

Coleções completas geram recompensas.

Isso cria progressão além de dinheiro.

---

# 13. WORKERS

Tipos:

Miner.

Engineer.

Geologist.

Driver.

Operator.

Manager.

Cada função possui bônus.

Funcionários raros podem ter habilidades.

---

# 14. EQUIPAMENTOS

Picareta.

Broca.

Escavadeira.

Esteira.

Elevador.

Refinaria.

Scanner.

Mega Drill.

Máquinas possuem:

Level.

Efficiency.

Capacity.

Speed.

---

# 15. GARGALOS

Exemplo:

Minerador produz:

100 minério/min.

Elevador transporta:

60/min.

Logo:

40 acumulam.

Jogador percebe visualmente.

Pode melhorar elevador.

Essa matemática simples gera gerenciamento.

> **Revisão 2026-10-09 (tensão do core).** Do jeito que está, o gargalo tem uma resposta só: melhorar o ponto que acumula. É o defeito que a validação achou também no Forge e no Airport ("decisão óbvia"). Para haver decisão, o upgrade precisa competir com outra coisa. Fontes de tensão propostas (detalhe no §55):
> - **veio com escolha (UG-1):** rico e lento × pobre e rápido, disputando o mesmo elevador;
> - **escorar ou arriscar (UG-3):** ao abrir camada, pagar a escora ou descer direto e aceitar uma interdição de 60 s, só na sessão ativa;
> - **a mina inteira trabalha junto (UG-7):** as camadas de cima abastecem as de baixo, então o upgrade de cima compete com o de baixo;
> - **turno da noite (UG-6):** antes de sair, escolher quais camadas rodam no offline.

---

# 16. DEPTH GATES

Algumas profundidades possuem barreiras.

Exemplo:

rocha maciça.

lava.

porta antiga.

Jogador precisa:

poder de perfuração;

recurso especial;

pesquisa.

Esses gates criam antecipação.

---

# 17. MYSTERY WALL

Eventos aleatórios:

parede rachada.

Jogador pode investigar.

Possíveis recompensas:

baú;

artefato;

mineral raro;

caverna secreta;

evento.

Rewarded Ad pode acelerar abertura, mas nunca ser obrigatório.

> **Revisão 2026-10-09 (ECA Digital).** Recompensa sorteada que se destrava com anúncio ou gem fica perto demais de "item aleatório pago". A Lei 15.211/2025 (ECA Digital) está em vigor desde 17/03/2026, e a leitura jurídica do art. 20 é decisão pendente do Vinicius. A Mystery Wall passa a ser **parede com raio-X** (UG-2, §55): o conteúdo é determinístico (pela profundidade e pela contagem de paredes), e a silhueta do prêmio aparece antes de abrir. O anúncio só acelera o tempo e nunca muda o que sai. No MVP: 1 tipo de parede com prêmio fixo (raia B).

---

# 18. BASE

Na superfície temos:

Office.

Warehouse.

Research Lab.

Museum.

Workshop.

Trade Center.

Crew Quarters.

Cada prédio oferece progressão.

---

# 19. RESEARCH

Árvore permanente:

Mining.

Transport.

Refining.

Exploration.

Automation.

Commerce.

Exemplo:

+5% mining speed.

+10% elevator capacity.

+5% rare mineral chance.

+10% offline efficiency.

---

# 20. ASCENSION

Precisamos de um equivalente de prestige que não pareça apagar progresso.

Usaremos:

**Deep Expedition.**

Ao chegar a determinado marco:

jogador inicia uma nova operação em região mais profunda.

Recebe:

Core Tokens.

Core Tokens oferecem upgrades permanentes.

Coleções e artefatos permanecem.

> **Revisão 2026-10-09.** A Deep Expedition entra na **v0.2**, não no MVP (raia B). Core Tokens só existem quando houver ralo definido no mapa de fontes e ralos. A expedição não pode ser a rota obrigatória de toda sessão: o bot mede quantos minutos de jogo ativo separam uma expedição da seguinte.

---

# 21. ECONOMIA

### Cash

Moeda operacional.

### Gems

Premium.

### Research Points

Tecnologia.

### Core Tokens

Progressão permanente.

### Event Currency

Eventos.

### Materials

Recursos específicos para upgrades.

> **Revisão 2026-10-09 (guardrails do veredito).** São 6 moedas aqui (7 com Blueprints) e o escopo é de live-service. **No MVP: 1 moeda (Cash).** As outras entram uma por vez, só depois de existir ralo para ela no mapa de fontes e ralos, nesta ordem: Core Tokens (v0.2, com a Deep Expedition) → Research Points → Gems (só com IAP aprovado) → Event Currency → Materials. Fonte sem ralo é inflação anunciada.

---

# 22. OFFLINE PROGRESS

Durante ausência:

mina continua parcialmente operando.

Ao retornar:

jogador coleta.

Rewarded Ad:

multiplica recompensa.

Managers podem aumentar eficiência offline.

> **Revisão 2026-10-09 (teto definido).** A validação apontou que o offline não tinha teto. Regra do MVP (a mesma do cofre do Forge Street, já testada):
> - ganho offline = taxa online medida (média móvel) × **50%** × min(tempo fora, **2 h**); com upgrades, no máximo 8 h;
> - teto relativo: no máximo 2× o preço do upgrade mais barato ainda travado (no Forge, isso impediu 8 h fora de comprarem 7 upgrades de uma vez);
> - Δt ≤ 0 paga 0; o cofre só abre com ≥ 60 s fora; cada claim tem id de transação; offline nunca dá gem nem moeda de evento;
> - rewarded 2× no claim (o mais natural do gênero, raia B);
> - sem backend não há anti-cheat de relógio: aceitamos a trapaça local com teto;
> - o **turno da noite** (UG-6, §55) escolhe quais camadas rodam fora.

---

# 23. MISSÕES

### Daily

mine X minério.

upgrade X máquinas.

encontre recurso raro.

### Career

alcance 1 km.

descubra 30 minerais.

### Exploration

descubra artefatos.

### Event

objetivos temporários.

---

# 24. EXPEDIÇÕES

Sistema secundário.

Jogador envia equipe.

Duração:

30 min.

2 h.

4 h.

8 h.

Recompensas:

artefatos;

blueprints;

gems;

materials.

Cria motivo de retorno.

> **Revisão 2026-10-09.** Expedições ficam fora do MVP. Quando entrarem, **não dão gems** (a validação achou o vazamento de hard currency sem orçamento) e os prêmios são fixos e mostrados antes de enviar.

---

# 25. BLUEPRINTS

Máquinas especiais precisam de blueprints.

Exemplo:

Laser Drill.

Quantum Elevator.

Crystal Scanner.

Blueprints podem vir de:

expedições;

eventos;

achievements.

---

# 26. EVENTOS

### Gold Rush

Maior produção de ouro.

### Fossil Hunt

Coleção temporária.

### Lost Temple

Mina de evento.

### Deep Race

Alcance maior profundidade durante período.

### Crystal Storm

Cristais aparecem com frequência.

### Ancient Machine

Evento narrativo.

---

# 27. EVENT MINE

Como no aeroporto, podemos possuir mapas independentes.

Exemplo:

**Moon Mine**

7 dias.

Gravidade baixa.

Recursos específicos.

Progressão própria.

Recompensa final permanente.

Isso permite variar tema radicalmente.

---

# 28. SEASONS

28 dias.

Free Track.

Premium Track.

Rewards:

workers;

skins;

boosts;

gems;

artifacts.

---

# 29. SKINS

Máquinas.

Elevadores.

Base.

Workers.

Carrinhos.

Skins podem criar monetização adicional sem afetar balanceamento.

---

# 30. DAILY LOOP

Entrar.

Coletar lucro offline.

Verificar produção.

Resolver gargalo.

Fazer upgrades.

Descer.

Completar missões.

Enviar expedição.

Coletar evento.

Sair.

---

# 31. PRIMEIRO DIA

Jogador começa manualmente.

Toca na rocha.

Obtém primeiro minério.

Contrata minerador.

Constrói carrinho.

Desbloqueia elevador.

Constrói refinaria.

Chega ao primeiro novo estrato.

Encontra primeiro mineral raro.

Descobre primeira Mystery Wall.

O final do D1 deve deixar algo visível logo abaixo que o jogador ainda não alcançou.

---

# 32. D7

Jogador:

possui operação automatizada;

atravessou primeiro bioma;

desbloqueou Research;

encontrou artefatos;

participa de eventos;

utiliza expedições.

---

# 33. D30

Jogador:

opera vários sistemas;

possui coleção crescente;

acessou múltiplos biomas;

realizou Deep Expedition;

busca raridades.

---

# 34. D90

Motivadores principais:

novos biomas;

coleções;

artefatos;

evento;

research;

season;

expeditions;

máquinas especiais.

---

# 35. MONETIZAÇÃO

### Rewarded Ads

offline ×2 ou ×3;

boost temporário;

free chest;

Mystery Wall acceleration;

expedition reward;

extra event reward.

### IAP

Remove Ads.

Starter Pack.

Gem Packs.

Engineer Pack.

Machine Pack.

Season Pass.

Event Bundle.

Permanent Efficiency Pack, com muito cuidado para evitar pay-to-win extremo.

> **Revisão 2026-10-09.**
> - O **Permanent Efficiency Pack** conflita com a Deep Race competitiva (§26): booster pago fica **desligado** em qualquer ranking ou corrida. Se a Deep Race existir, o pack não vale nela.
> - **v0.1 só com rewarded em modo teste, sem IAP** (o modelo de negócio é decisão do Vinicius).
> - **Gate de dinheiro da fase B = IAA de rewarded:** opt-in ≥ 40% no 2× offline, impressões/DAU e ARPDAU. Pagante só a partir de 5k installs.
> - "Free chest" e "Mystery Wall acceleration" seguem o §37: conteúdo fixo e visível.

---

# 36. INTERSTITIALS

Devem ser moderados.

Possíveis momentos:

transição de bioma;

retorno à superfície;

fim de determinadas sessões.

Nunca interromper mineração ativa frequentemente.

> **Revisão 2026-10-09.** Interstitial **desligado na v0.1**, para medir a retenção limpa (veredito). Na v0.2, por RemoteConfig, só depois do 1º depth gate e com intervalo ≥ 90 s. O §55 (UG-5) discute mantê-lo desligado como promessa de marca.

---

# 37. CHESTS

Free Chest.

Rare Chest.

Artifact Chest.

Event Chest.

Evitar lootbox agressiva.

Odds devem ser transparentes onde necessário.

> **Revisão 2026-10-09 (ECA Digital).** **Nada aleatório pago.** Rare, Artifact e Event Chest + gems compráveis = item aleatório pago, com risco jurídico no Brasil (Lei 15.211/2025) e obrigação de odds na Play. Regra: todo baú tem **conteúdo fixo e visível** antes de abrir, seja ganho, seja por anúncio, seja pago. Baú aleatório só com parecer jurídico, odds publicadas e bloqueio no BR.

---

# 38. COLEÇÕES

Minerals.

Artifacts.

Machines.

Workers.

Biomes.

Collections criam objetivos de longo prazo paralelos.

---

# 39. WORLD MAP

Depois de determinado progresso:

jogador descobre outros locais.

Exemplo:

Desert Mine.

Arctic Mine.

Jungle Mine.

Volcanic Mine.

Cada uma adiciona variações sem quebrar core loop.

---

# 40. SOCIAL

Fase posterior:

Mining Corporation.

Jogadores contribuem para meta coletiva.

Exemplo:

extrair 1 bilhão de toneladas.

Recompensas coletivas.

Leaderboards opcionais.

---

# 41. LIVE OPS

Segunda:

weekly mission.

Terça:

mini event.

Quinta:

event mine.

Fim de semana:

production boost.

Mensal:

season.

Trimestral:

novo bioma/feature.

---

# 42. CONTEÚDO DE LANÇAMENTO

3–4 biomas.

20+ minerais.

20 artefatos.

10 workers especiais.

10+ máquinas.

Research Tree.

Expeditions.

Museum.

Daily/Weekly.

3 eventos.

1 Event Mine.

Isso gera semanas de progressão antes da primeira grande atualização.

---

# 43. ARTE

3D estilizado.

Corte lateral/isométrico.

Biomas possuem identidades cromáticas distintas.

Objetivo:

jogador reconhecer profundidade instantaneamente.

Quanto mais fundo:

mais fantástico.

A mina precisa parecer viva.

> **Revisão 2026-10-09.** O **MVP é 2D em corte lateral** (raias B e C): é a arte mais barata entre os idle e a mais legível para o "How deep can you go?". Workers são sprites com tween, e cada bioma é um kit modular (fundo + 3 texturas de rocha + 2 minerais). 3D só entra se um criativo provar que precisa.

---

# 44. ÁUDIO

Pedra quebrando.

Broca.

Carrinho.

Elevador.

Cristal.

Moedas.

Artefato.

Explosão controlada.

Ambientação muda por profundidade.

Regiões profundas podem ter atmosfera mais misteriosa.

---

# 45. ARQUITETURA UNITY

GameManager

MineManager

DepthManager

LayerManager

ResourceManager

ProductionManager

TransportManager

ElevatorManager

RefineryManager

WorkerManager

EquipmentManager

ResearchManager

ArtifactManager

CollectionManager

ExpeditionManager

EventManager

OfflineProgressManager

EconomyManager

SaveManager

AnalyticsManager

AdsManager

IAPManager

RemoteConfigManager

AudioManager.

> **Revisão 2026-10-09.** Os 24 managers acima são a arquitetura de um produto de anos. Para o MVP vale o padrão do Forge Street (§57): **núcleo em C# puro** (simulação por tick, testável sem abrir o Unity) + **bot de balance** + **diário de playtest**, e uma View fina por cima. A lista acima fica como mapa de longo prazo.

---

# 46. SISTEMA MATEMÁTICO

Cada produção deve ser baseada em fórmulas configuráveis.

Exemplo conceitual:

ProductionRate = BaseProduction × UpgradeMultiplier × WorkerBonus × ResearchBonus × EventBonus.

TransportCapacity utiliza lógica semelhante.

Tudo deve estar em configuração.

Nada importante deve ficar hardcoded.

> **Revisão 2026-10-09 (inflação).** Multiplicar bônus sobre bônus (Upgrade × Worker × Research × Event) acelera a inflação, e "notação apropriada" não é ralo (raia B). Regra: bônus da **mesma categoria somam** (+5% + 10% = +15%) e só categorias diferentes multiplicam, com no máximo 3 fatores ativos no MVP. Cada curva nova passa pelo bot antes de ir a jogador: tempo até o próximo depth gate em jogo ativo e em jogo "lento" (×0,4, a lição do teste do Forge no POCO F4).

---

# 47. PERFORMANCE

Precisamos evitar centenas de NPCs simulados individualmente.

Usaremos:

object pooling;

LOD;

simulação agregada fora da área visível;

tick systems;

animações simplificadas.

A mina pode parecer enorme sem calcular fisicamente cada minério.

---

# 48. ANALYTICS

depth_reached

biome_unlocked

mineral_discovered

artifact_found

machine_upgrade

production_bottleneck

offline_claim

research_unlock

expedition_start

expedition_complete

event_progress

rewarded_complete

iap_purchase.

---

# 49. KPIs

Tutorial completion.

D1.

D3.

D7.

D30.

Depth progression.

Sessions/day.

Offline claim rate.

Ad opt-in.

Event participation.

Collection engagement.

Payer conversion.

ARPDAU.

CPI.

LTV.

> **Revisão 2026-10-09.** Os números, a amostra e os kill criteria estão no **§56**.

---

# 50. UA

Esse projeto possui um hook visual potencialmente forte.

Exemplo:

Tela mostra profundidade:

0 m.

100 m.

500 m.

1.000 m.

A câmera desce continuamente.

Texto:

**“How deep can you go?”**

Outro:

parede misteriosa.

Jogador escolhe local de perfuração.

Descobre sala secreta.

Outro:

mina pequena transformando-se em instalação gigantesca.

---

# 51. ROADMAP

## MVP

Mining.

Transport.

Elevator.

Upgrade.

Depth.

Offline.

> **Revisão 2026-10-09 (MVP de 2–3 semanas, raia B):**
> - **Entra:** 1 mina com 5 camadas (minerador → carrinho), elevador e armazém/venda; 3 atributos por estação (velocidade, capacidade, nível); 1 gerente por camada que a automatiza; medidor de profundidade com 1 depth gate (300 m, exige broca nível X); offline de 2 h a 50%; rewarded 2× no claim e boost 2× de 5 min; Mystery Wall de 1 tipo com prêmio fixo; 3 minerais e 2 visuais de bioma; **veio com escolha nas camadas 3–5 (UG-1)**.
> - **Corta:** gems, research, museu, artefatos, expedições, blueprints, workers raros, baús, eventos, season, world map, social e prestige (prestige só na v0.2).
> - **Antes de construir:** o slot idle se decide por um teste só de criativos, Underground × Forge (veredito). O Forge Street já está em desenvolvimento; o Underground é a alternativa se ele falhar no playtest.

## Alpha

2 biomas.

research.

collections.

museum.

ads.

IAP.

## Soft Launch

3–4 biomas.

events.

expeditions.

remote config.

analytics.

## Global

season.

event mines.

live ops.

pipeline de conteúdo.

---

# 52. ANO 1

Q1:

lançamento.

Q2:

Lost Ruins.

novas máquinas.

Q3:

Mining Corporations.

Event Mines expandidas.

Q4:

Lost World.

coleções avançadas.

grande evento sazonal.

---

# 53. RISCOS

### Idle excessivamente passivo

Mitigação:

gargalos, descoberta e expeditions.

### Progressão vira apenas números

Mitigação:

novos biomas e descobertas visuais.

### Economia inflaciona

Mitigação:

notação apropriada e progressão em tiers.

### Conteúdo visual caro

Mitigação:

kits modulares por bioma.

### Ads excessivos

Mitigação:

rewarded como principal publicidade.

> **Revisão 2026-10-09 (riscos novos).**
> - **O líder do subgênero é o Idle Miner Tycoon** (150M+ downloads, Kolibri/Ubisoft), e o nosso loop é o dele. Sem um diferencial de mecânica (§55), o jogo é lido como clone. Mitigação: UG-1 no MVP e criativo próprio.
> - **Profundidade não é exclusiva** (Deep Town, Dig Down, Mr. Mine). Mitigação: o criativo mostra a **escolha** do veio e a parede com raio-X, não só a câmera descendo.
> - **Escopo de live-service** (7 moedas, museu, season, world map, social) para um estúdio pequeno. Mitigação: MVP do §51 e uma moeda por vez (§21).
> - **ECA Digital** (baús e Mystery Wall). Mitigação: §17 e §37.

---

# 54. VISÃO DE LONGO PRAZO

O maior diferencial comercial de Underground Inc. deve ser sua capacidade de continuar fazendo a mesma pergunta durante meses:

**“O que existe mais embaixo?”**

A primeira mina é apenas o começo.

Depois podemos revelar:

ruínas;

civilizações perdidas;

oceanos subterrâneos;

ecossistemas;

tecnologia antiga;

núcleo planetário;

portais;

outros planetas.

A progressão começa industrial e gradualmente pode se tornar fantástica.

Isso permite que o jogo cresça por anos sem abandonar seu core.

O jogador não está apenas acumulando dinheiro.

Ele está realizando uma **expedição contínua ao desconhecido**.

---

# 55. DIFERENCIAIS COMPETITIVOS (revisão 2026-10-09)

Resumo. O detalhe de cada um (por que, como, custo, risco e validação) e as fontes estão em [`COMPETITIVO.md`](COMPETITIVO.md) d–e. Status de todos: **PROPOSTO**. Custo para o nosso time: P ≤ 1 semana · M 2–4 semanas · G ≥ 1 mês.

| # | Diferencial | O que os similares fazem | Custo | Prova barata |
|---|---|---|---|---|
| UG-1 | **Veio com escolha:** cada camada nova mostra 2–3 veios no corte (rico e duro × pobre e macio × raro e longe do elevador); escolher qual abrir define a produção e o gargalo daquela camada. Trocar depois custa tempo, não dinheiro real | toda camada é igual, só muda o número | M | bot: nenhuma escolha domina em > 70% das sementes; criativo "qual você abriria?" × controle |
| UG-2 | **Parede com raio-X:** a Mystery Wall mostra a silhueta do prêmio antes de abrir; conteúdo determinístico; anúncio só acelera | baús sorteados, gems por gacha | P | ≥ 60% abrem a 1ª parede; criativo "o que tem atrás da parede?" |
| UG-3 | **Escorar ou arriscar:** ao abrir uma camada, o jogador escolhe escorar (custa tempo e Cash) ou descer direto (chance de infiltração ou gás que interdita aquela camada por 60 s). Só acontece com o jogo aberto, nunca destrói nada e um toque resolve | desabamento aleatório sem escolha (Drill & Collect) ou nenhum risco | M | o bot mede o valor esperado das duas opções (nenhuma domina); ≥ 70% resolvem o incidente em 10 s sem chamar de chato |
| UG-4 | **Caderno do geólogo (minerais do Brasil):** cada mineral é real (quartzo, ametista, turmalina Paraíba, topázio imperial, nióbio, ouro de Minas), com 1 curiosidade verdadeira e a região de origem | minerais genéricos ou fantasia | P | ≥ 30% abrem o caderno sozinhos; página da loja com o tema BR × genérico |
| UG-5 | **Sem parede de progressão, provado pelo bot:** promessa pública de que a próxima camada sempre chega em ≤ 1 sessão de jogo ativo, sem pagar; interstitial nunca | paredes, pagar para descer | P | bot + bot lento: tempo até cada gate ≤ 12 min de jogo ativo |
| UG-6 | **Turno da noite:** antes de sair, o jogador escolhe até 2 camadas para rodar no offline (as outras param). Decide onde o cofre rende | offline automático, sem escolha | P | ≥ 50% dos que voltam mudam a escolha pelo menos 1× na 1ª semana |
| UG-7 | **A mina inteira trabalha junto:** as camadas de cima produzem o que as de baixo consomem (escoras, trilhos, combustível da broca), então uma camada antiga nunca fica inútil e continua recebendo upgrade | minas antigas perdem relevância (a própria publisher de Gold and Goblins admite) | M | bot: as camadas 1–2 continuam recebendo ≥ 15% das compras depois do 300 m |

**Ordem recomendada:** UG-1 → UG-5 → UG-2. Depois UG-7 (resolve o problema que o líder de receita admite), UG-6 (barato e casa com o offline do MVP), UG-4 (identidade para o 1º mercado) e UG-3 (só se o playtest pedir tensão ativa).

**Invariantes de design** (cada uma vira teste negativo no núcleo):
- Nenhum veio domina: o bot roda cada escolha com 2 bases de semente e ≥ 30 amostras.
- A parede nunca sorteia e nunca vende o que sai.
- Incidente (UG-3) nunca acontece offline e nunca destrói progresso comprado; nenhuma das duas opções domina no bot.
- Toda concessão tem id de transação.

# 56. KPIs NUMÉRICOS E KILL CRITERIA (revisão 2026-10-09)

A validação apontou que este GDD não tinha número, estimativa nem critério de corte. Valores do veredito de 2026-10-06 e da raia B. Todos são **HIPÓTESE** até a 1ª coorte.

**Metas (coorte paga de 1,5–2k installs, BR/PH/ID, comparando pago com pago):**

| Métrica | Continuar | Iterar | Cancelar (só depois de 2 iterações) |
|---|---|---|---|
| D1 | ≥ 26% | 22–26% | < 22% |
| D7 | ≥ 5% | 4–5% | < 4% |
| CPI (Android, BR/PH/ID) | ≤ US$0,70 | 0,70–1,10 | > 2× o alvo em 8–10 criativos |
| Opt-in do 2× offline | ≥ 40% | 30–40% | < 30% |
| Claim offline na 2ª sessão (retidos no D1) | ≥ 45% | 35–45% | < 35% |
| Jogadores do D0 que chegam aos 300 m | ≥ 40% | 30–40% | < 30% |
| Tutorial / 1ª venda em < 60 s | ≥ 90% | 80–90% | < 80% |

- Pagante só se mede a partir de 5k installs. Antes disso, o gate de dinheiro é IAA de rewarded (opt-in, impressões/DAU, ARPDAU).
- Amostra: com 1k installs, a margem do D7 é ±1,7 pp; com 2k, ±1,2 pp. Decidir D7 com ≥ 2k.
- O CPI-alvo é o mesmo do Forge Street (§15 do GDD 03), porque os dois disputam o mesmo slot idle e o mesmo público.

**Kill criteria (raia B, ajustados ao veredito):**
- **K1, retenção:** D1 < 22% ou D7 < 4% numa coorte de ≥ 1,5k depois de 2 iterações → cancelar.
- **K2, diferencial:** o criativo da escolha do veio ou do raio-X não supera o criativo de controle (fábrica crescendo) em IPM em 2 famílias, **e** < 40% dos jogadores do D0 chegam aos 300 m → a profundidade não está segurando.
- **K3, loop idle:** < 45% dos retidos no D1 fazem claim offline na 2ª sessão, **ou** o opt-in do 2× offline fica < 40% → o idle não gera retorno.

# 57. REUSO DO NÚCLEO DO FORGE STREET (revisão 2026-10-09)

O Forge Street (repo `Vvs2705/forge-street`, v0.6) já tem, testado em C# puro e medido num POCO F4 real (60 fps, 0 crash), quase toda a infraestrutura que o MVP do §51 precisa. Reaproveitar o **padrão e o código** encurta o MVP. Estimativa não medida: de 3–4 semanas (raia C) para 2–3.

| Peça do Forge (`FS.Core` e ferramentas) | Uso no Underground |
|---|---|
| Simulação por tick com estações, filas e carregadores (`Sim`, `Station`, `Carrier`) e métricas de gargalo (`StarveSeconds`/`StallSeconds` = "fome" e "travada") | camada = estação, carrinho e elevador = carregador; o gargalo visível do §15 sai pronto |
| Bot de balance (`Bot.cs`) e testes de marco (`coretests`, ~1 s sem abrir o Unity) | tempo até cada depth gate, prova do UG-1 (nenhum veio domina) e do UG-5 (sem parede) |
| Cofre offline (`ApplyOffline`: teto de tempo, teto relativo, Δt ≤ 0 = 0, id de transação) | §22 do jeito que está, só com 50% em vez de 25% |
| VIP determinístico (sequência de Weyl, sem estado além de um contador) | Mystery Wall e minerais raros sem sorteio (UG-2) |
| Encomendas dimensionadas pela renda real (`RateEma`) | missões diárias do §23 que crescem com a mina |
| Diário de playtest (`diario.csv`) + `diario_report.py` com PORTÕES | KPIs do §56 no playtest Camada 0 |
| Save em texto versionado, que abre saves antigos | save do MVP |
| Gravação de criativos 9:16 do build real (`-record`), `medir_aparelho.sh` e anúncios simulados no LevelPlay | criativos do teste Underground × Forge; FPS/memória no aparelho |

O que **não** se reaproveita: o joystick e a física de andar (o Underground é de toque), a arte (2D lateral × sprites pré-renderizados) e o layout. Se os dois jogos seguirem, vale extrair um pacote `VStack.IdleCore` com estação, fila, cofre, bot e diário. Até lá, copiar e adaptar.
