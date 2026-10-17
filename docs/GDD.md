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

---

## Lições do estúdio aplicadas a Underground Inc. (do Dungeon Courier, 2026-10-16)

> **Status: PROPOSTO.** Nada desta seção foi implementado nem testado neste repositório. O jogo ainda é só GDD e depende da decisão do slot idle (§51).

O Dungeon Courier (DC) chegou à 1.4.1-beta em 2026-10-16 com o GDD inteiro feito, arte v2, tutorial guiado, anúncios e compras integrados e AAB assinado. Cada lição abaixo foi paga lá com tempo, crédito ou retrabalho. A versão completa está no playbook [`LICOES_PARA_O_ESTUDIO.md`](https://github.com/Vvs2705/dungeon-courier/blob/main/docs/LICOES_PARA_O_ESTUDIO.md), com cópia na memória do estúdio (`C:\Users\VINICIUS\Videos\MEUS PROJETOS\Agentes\_memoria\PLAYBOOK_ESTUDIO_DUNGEON_COURIER.md`). Esta seção traduz o playbook para a mina e complementa o §57: o Forge Street dá o núcleo de economia (tick, cofre, bot), e o DC dá o processo, a rota de arte, o tutorial, a interface e o caminho até a loja. Convenção: `dc:` = repo `Vvs2705/dungeon-courier` (pasta `JOGOS NOVOS/06_DUNGEON_COURIER`); `fs:` = repo `Vvs2705/forge-street` (pasta `JOGOS NOVOS/03_FORGE_STREET`). Os clipes Mixamo ficam **fora do git** nos dois jogos: o reuso é cópia do disco, registrada em `docs/PROVENIENCIA.md`. O aval do Vinicius de 2026-10-09 cobre reusar, como cópia, os clipes Mixamo que já estão no disco (`dc:docs/PROVENIENCIA.md` §3).

### Processo
- **Contrato da v0.1 antes de codar.** **Fazer:** `docs/CONTRATO_V01.md` com o MVP do §51 (5 camadas, elevador, armazém/venda, 1 gerente por camada, gate de 300 m, offline de 2 h a 50%, rewarded 2× e boost de 5 min, parede com raio-X de 1 tipo, 3 minerais, 2 visuais de bioma, UG-1 nas camadas 3–5), os números iniciais e o critério de pronto. Também `docs/CONTRATO_LANCAMENTO.md`, com a matriz "§ do GDD × feito" (feito / v0.2 / cortado / depende do Vinicius). **Por quê:** no DC, com o contrato escrito antes, núcleo e View andaram em paralelo sem quebrar a API, e a matriz impediu dar o jogo por pronto antes da hora. **Reaproveitar:** `dc:docs/CONTRATO_V01.md` e `dc:docs/CONTRATO_LANCAMENTO.md` §1.
- **Memória de retomada.** **Fazer:** criar `_memoria/STATUS_underground-inc.md`, com um bloco "CONTINUAR DAQUI" a cada pausa (o que está pronto, o que falta, os comandos). **Por quê:** o Vinicius retoma dizendo só "vamos continuar"; sem o bloco, cada sessão reabre a investigação. **Reaproveitar:** `_memoria/STATUS_dungeon-courier-v01.md` como modelo.
- **Fotos antes do PR e um processo pesado por vez.** **Fazer:** toda mudança visual leva fotos 540×960 de cada tela (`-shot`), conferidas pelo coordenador. Unity, Blender e emulador nunca rodam juntos (PC de 7,7 GB). **Por quê:** no DC, as fotos acharam texto sobreposto e o joystick tampando o personagem, e nenhum dos 169 testes verdes pegou isso. Com dois processos pesados juntos, o sistema mata o Blender.
- **Arte crua fora do git, com backup.** **Fazer:** zips do Tripo, FBX do Mixamo e `.blend` com modelo pago ficam em `arte/tripo` e `arte/mixamo` do **checkout principal** (o worktree some quando é apagado) e num drive privado. Logo, ícones e retratos pintados entram no git (`arte/logo`, `arte/ui`, `arte/retratos`). **Por quê:** o repositório é público e a licença dos modelos não permite redistribuir. **Reaproveitar:** `dc:docs/PROVENIENCIA.md` (livro-razão de créditos e registro por peça).

### Código e testes
- **Esqueleto do projeto: copiar, não reescrever.** **Fazer:** o núcleo vem do Forge, em `fs:client/Assets/_FS/Scripts/Core/`: `Sim.cs` (camada = estação; carrinho e elevador = carregador; estados "fome" e "travada"), `SaveEnvelope.cs` (SHA-256 + schema), `Equipe.cs` (trabalhador fixo e nomeado, sem traço sorteado), `Metas.cs` (o dia vira às 04:00 no fuso gravado: base das diárias do §23) e `Anuncios.cs` (id de transação e teto diário). A casca vem do DC, em `dc:client/Assets/_DC/`: `Editor/Setup.cs`, `Editor/SpriteImport.cs` e, em `Scripts/View/`, `Art.cs`, `Tour.cs`, `Textos.cs`, `Exportar.cs`, `AreaSegura.cs`, `Dp.cs` e `SpriteSheet.cs`; mais as ferramentas `client/tools/coretests` e `viewcheck`. A API do núcleo fica documentada no topo do `Sim.cs`. **Por quê:** o DC roda 169 testes em 2–3 min sem abrir o Unity, e o Forge já tem a economia de filas medida num POCO F4 (60 fps, 0 crash).
- **Namespace `UG`, não `UI`.** **Fazer:** a pasta pode continuar `_UI`, mas o namespace e o asmdef viram `UG` e `UG.Core`. **Por quê:** `UI` colide com o `UnityEngine.UI` do uGUI, a mesma armadilha do `Rect` entre o Core e o Unity no DC (`using Rect = UnityEngine.Rect;`). Pelo mesmo motivo, vale rever o escopo de commit `ui-core` do `CONTRIBUTING.md`.
- **Bot, perfis e `-autoplay`.** **Fazer:** o `-autoplay N` imprime o tempo até o gate de 300 m, a renda por minuto, a % das compras por camada (UG-7: ≥ 15% nas camadas 1–2) e a escolha de veio (UG-1: nenhuma acima de 70%), nos perfis F2P, lento (×0,4) e "assiste anúncio". **Por quê:** no DC, o bot fez o balance e o portão. No Forge, a pessoa real foi 1,7–3,7× mais lenta que o bot, então a duração se mede com gente (diário), não com o bot. **Reaproveitar:** `fs:client/Assets/_FS/Scripts/Core/Bot.cs`, `fs:client/tools/econsim` e `dc:docs/BALANCE.md` (formato).
- **Invariantes do §55 viram testes negativos nomeados.** **Fazer:** a parede nunca sorteia (mesma profundidade e mesma contagem dão o mesmo prêmio); incidente nunca acontece offline; toda concessão tem id de transação; offline com Δt ≤ 0 paga 0. **Por quê:** regra que mora só em prosa não sobrevive ao código. **Reaproveitar:** `fs:client/Assets/_FS/Tests/EditMode/ExploitTests.cs`.
- **Flags de teste**, só com `-testsession` (não lê nem grava save, semente 1): `-tela <nome>`, `-camada K`, `-profundidade M`, `-bot`, `-dev-desbloqueia` (mina inteira aberta, para fotografar os biomas fundos), `-lang pt|en|es|id`, `-shot arq -shotdelay s`, `-record pasta …` (o criativo "How deep can you go?" com a câmera descendo, determinístico), `-tutorial` e `-adtestsuite`. **Por quê:** no DC, fotos da loja, criativos e QA saíram do jogo real sem tocar no save do jogador. **Reaproveitar:** a leitura de argumentos do `dc:Scripts/View/Game.cs`.
- **Diário CSV de playtest.** **Fazer:** eventos `first_sale`, `depth_reached`, `vein_choice`, `wall_open`, `offline_claim`, `rewarded_*` e `tour_step`, sem dado pessoal e exportados pelo próprio jogador. O relatório calcula os portões do §56: 1ª venda em < 60 s, 300 m no D0 e claim na 2ª sessão. **Reaproveitar:** `dc:Scripts/View/Exportar.cs` + `dc:client/tools/diario_report.py` (a versão do Forge já tem PORTÕES).
- **Tabelas por enum com reserva e textos em 4 idiomas.** **Fazer:** biomas, minerais e máquinas indexados por enum, com linha de reserva procedural; enums salvos só crescem no fim. O caderno do geólogo (UG-4) e todo texto fixo vão em `L(pt, en, es, id)`: frase inteira por idioma, números por `{0}`, só Latin-1 ("turmalina Paraíba" passa; fórmula química com subscrito, não). **Por quê:** no DC, enum novo sem linha na tabela quebrava com `IndexOutOfRange`. **Reaproveitar:** `dc:Scripts/View/Textos.cs`.
- **Áudio sintetizado.** **Fazer:** os sons do §44 (pedra quebrando, broca, carrinho, elevador, moeda, o "achado" do mineral raro) saem de script, e a ambiência por profundidade sai de drones sintetizados, com um filtro diferente por bioma. **Por quê:** sem asset de terceiros, não há licença a rastrear. **Reaproveitar:** `dc:client/tools/audio_gen.py`.
- **Portão antes de todo PR.** `dotnet test client/tools/coretests` · `dotnet build client/tools/viewcheck/view` · Unity EditMode · build Windows · `-autoplay 30` com 0 exceções · fotos 540×960 conferidas. Armadilhas já pagas: o dotnet usa NUnit 3.14 e o Unity usa 3.5 (rode o EditMode antes do PR); o viewcheck num worktree novo precisa das DLLs de `Library/ScriptAssemblies`; o Unity reescreve o `Packages/manifest.json` ao criar o projeto; `PlayerPrefs` não pode ser lido em inicializador de campo. **Reaproveitar:** `fs:client/tools/verify.sh`.

### Arte e animação
- **Rota: 3D modelado → sprites 2D em corte.** **Fazer:** o MVP é 2D em corte lateral (§43), e a rota do DC entrega isso: Tripo (imagem grátis → modelo HD → Auto Rig Mixamo) → Blender → `render_sprites.py` com câmera lateral (`--elev` baixo, `--dirs 1`; o lado oposto é espelho) e luz chapada com contorno. O cenário da mina sai do gerador de imagens grátis, não do Tripo: fundo do corte, 3 texturas de rocha e 2 minerais por bioma, parede rachada e silhuetas do raio-X. **Por quê:** um personagem animado de verdade custa 65 créditos e reaproveita clipes; o cenário pintado custa 0. **Reaproveitar:** `dc:client/tools/render_sprites.py`, `render_sprites.ps1`, `folhas.py` e `dc:docs/RENDER_SPRITES.md`.
- **O que gerar no Tripo: Lote 1 do MVP, ≈ 245 créditos (teto ≈ 355).** Créditos só com aval por lote.

  | Peça | Como | Créditos |
  |---|---|---|
  | Minerador humano (capacete com lanterna, macacão) | modelo HD 45 + rig 20 | 65 |
  | Carrinho de mina, elevador (cabine + roldana), broca do depth gate, armazém/venda da superfície | sem rig, 45 cada | 180 |
  | Gerente de camada | o mesmo minerador com outra cor (capacete branco, colete laranja) + prancheta | 0 (+65 se a silhueta não ler na tela) |
  | Picareta e prancheta | gerados **à parte** (regra do Vinicius) e presos ao osso; por script no Blender, como a mochila do ferreiro do Forge | 0 (+45 cada se for pelo Tripo) |
  | Lote 2 (Alpha, §13): engenheiro, geólogo, motorista e operador | 4 corpos novos, ou 2 corpos + troca de cor | 260, ou ≈ 130 |
  | Prédios da superfície (§18) | pintados no corte lateral (no Tripo seriam 7 × 45 = 315) | 0 |

  Confira o saldo antes e depois de cada geração e registre em `docs/PROVENIENCIA.md`. Na 1ª peça de cada sessão, confira a receita do painel: o Tripo já voltou com 8K, textura 4K e 2 M polígonos.
- **Clipes reaproveitados:** todos já estão no disco, no esqueleto `mixamorig:` (0 download, 0 crédito). Os do `_blender/` estão em `06_DUNGEON_COURIER/arte/mixamo/_blender/`.

  | Uso | Clipe | Detalhe |
  |---|---|---|
  | Golpe de picareta (minerar) | `_blender/SkelAttack.fbx` ou `_blender/Smash.fbx` | golpe de cima para baixo, impacto no quadro 6 de 12 / 30 quadros |
  | Jogar minério no carrinho | `_blender/PickThrow.fbx` | o do goblin mineiro; soltura no quadro 7 de 12 |
  | Parado | `03_FORGE_STREET/arte/mixamo/Idle.fbx` (Breathing Idle) | janela 199–289, preset `BREATH` |
  | Andar (gerente, motorista) | `03_FORGE_STREET/arte/mixamo/Walking.fbx` ou ARKANA `mixamo-loc-andar-frente.fbx` | In Place; no do ARKANA, o render tira o root motion |
  | Empurrar o carrinho, carregar minério | `06_DUNGEON_COURIER/arte/mixamo/Hold.fbx` + o andar | com `--hold`, os clipes Carry* herdam os braços dele |
  | Camada com "fome" ou elevador cheio ("travada") | `_blender/Sleep.fbx` + `_blender/Wake.fbx` | sentado encostado (laço); acorda em 0,4 s. O estado parado fica legível sem texto |
  | Incidente de gás (UG-3) | `_blender/Stun.fbx` | sentado tonto, laço |
  | Gerente apitando | `_blender/Call.fbx` | mão na boca |
  | Geólogo examinando a parede | `03_FORGE_STREET/arte/mixamo/LookingAround.fbx` | — |
  | Mineral raro, gate atravessado | Forge `Cheering.fbx` | — |
  | Gerente acenando no cartão do tutorial; venda | Forge `Waving.fbx`; Forge `Thankful.fbx` | — |
  | Criaturas dos biomas fundos (pós-MVP) | `_blender/Emerge.fbx`, `Burrow.fbx`, `Swipe.fbx` | — |

  O que faltar (picar a parede de lado, puxar a alavanca do elevador) se anima direto no Blender, por keyframe em script e com retarget por delta de rotação sobre o repouso. **Reaproveitar:** `dc:client/tools/anim_blender.py`; a origem e o SHA de cada clipe estão em `dc:docs/PROVENIENCIA.md` §3.
- **No Blender, sem crédito.** **Fazer:** (1) variantes por troca de cor: uniforme por função e por bioma, níveis do elevador e do carrinho (madeira → aço → neon) e as skins do §29; com luz chapada, a troca é feita direto na folha renderizada; (2) ajuste de forma em vez de gerar de novo: alongar a broca para virar o Mega Drill, cortar a parede rachada com bmesh bisect (como a tampa do baú do DC); (3) lanterna do capacete com emissão, para as camadas escuras; (4) `.blend` salvo depois do 1º import (o FBX do Tripo leva mais de 10 min para importar) e `timeout` em todo render (um render travou 15 h no DC). **Por quê:** no DC, as roupas, o saco do ladrão e o baú saíram sem crédito. **Reaproveitar:** `dc:client/tools/roupas_cor.py` (já tem a receita "mineiro": capacete âmbar e macacão marrom), `roupas_2d.py`, `roupas_courier.py`, `bau_abrindo.py` e `fs:client/tools/props_blender.py`.
- **Nitidez e tamanho.** **Fazer:** se o minerador parecer pequeno ou borrado no corte, re-renderize com `--hd K` e `--escala E`, com K = min(1,5; 4096 / (quadros × célula)), e ponha um teto de quadros por clipe (`--max-frames`). **Por quê:** com as folhas HD, o APK do DC foi de 67,7 para 83 MiB. **Reaproveitar:** `dc:client/tools/elenco_hd.sh`.
- **Arte de interface pintada no gerador grátis.** **Fazer:** sobre azul-marinho liso e recortados por script: logo, folha de ~20 ícones 4×3 (minerais do caderno UG-4, máquinas, moeda, profundidade), fundo do menu (o corte da mina), retrato da geóloga para o cartão de contexto e silhuetas do raio-X. **Por quê:** no DC, o retrato pintado no estilo do logo ficou muito mais vistoso que o render 3D recortado. **Reaproveitar:** `dc:client/tools/ui_assets.py`.

### Interface e marca
- **UI procedural em 9 fatias**, gerada por código e tingida por `Image.color`: `Botao`; `Moldura` (aqui, placa de aço rebitada em vez de madeira); `Pergaminho` (vira a página do caderno do geólogo); `Contorno` (destaque do tutorial); `Balao` (fala). Mais `Aperta` (escala 0,95 no toque), `Letreiro` no medidor de profundidade e uma paleta por bioma (§9). **Reaproveitar:** `dc:Scripts/View/Art.cs`.
- **Fontes OFL**, com a licença junto em `Resources/Fonts`. No DC: Lilita One nos títulos e botões, Nunito ExtraBold no corpo.
- **Retrato, 20:9 e toque.** CanvasScaler com referência 1080×1920 casando a largura, `AreaSegura` para o notch e alvo de 48 dp (`Dp`) em todo botão de camada. Arrastar rola a mina e toque curto aciona a estação, com limiar de arrasto para um gesto não virar o outro. Nas telas 20:9, a rocha do bioma, escurecida, continua até a borda: faixa lisa parece bug.
- **Ícone adaptativo.** Fundo + frente, com o minerador (ou o capacete com lanterna) a no máximo 0,64 da camada, conferido nas máscaras círculo, squircle e quadrado. O ícone da loja (512) é o mesmo, e o ícone pintado ganha medalhão claro atrás. **Reaproveitar:** `dc:client/tools/icone_app.py` e `Setup.Icones`.

### Onboarding (tutorial guiado)
O tutorial segue o loop do MVP e a meta "1ª venda em < 60 s para ≥ 90%" (§56). A tela congela e só o alvo fica aceso (véu com buraco, contorno dourado e seta). Cada passo aparece uma vez, com "Pular tutorial" e "REVER TUTORIAL" nas configurações, e fica desligado no `-testsession`. Os gatilhos leem o estado do núcleo, e passo de botão se cancela se a tela mudar (no DC, um passo preso sem alvo congelava o jogo). **Reaproveitar:** `dc:Scripts/View/Tour.cs`; troque só a lista de passos e os textos (o campo `Arrastar` mostra o dedo arrastando, e o `Fala` põe retrato e balão).

**Cartão de contexto no lugar de cutscene.** Antes do 1º toque, aparece o retrato pintado da geóloga (PROPOSTO: "Jade, a geóloga"; o nome é decisão do Vinicius), com o balão: *"Comprei este terreno com tudo o que eu tinha. Dizem que embaixo só tem carvão. Eu acho que tem muito mais. Me ajuda a cavar?"* O ciclo fecha no gate de 300 m, com ela de novo: *"Eu sabia! Olha só o que tem lá embaixo."* **Por quê:** no DC, uma cutscene atrasaria o 1º toque e somaria com o tutorial; o cartão do cliente resolveu com uma fala e um retrato. A geóloga também é a dona do caderno do UG-4, então o mesmo retrato serve duas vezes.

| # | Passo (tipo) | Quando | Por quê |
|---|---|---|---|
| 1 | Cartão da geóloga (explicação) | 1ª abertura | contexto numa frase, sem cutscene |
| 2 | "Toque na rocha" (ação: veio da camada 1) | logo depois | o verbo central antes de qualquer escolha (no DC, o verbo vem antes da 1ª bifurcação) |
| 3 | "Suba o minério" (ação: elevador) | com a 1ª pilha de minério | mostra a cadeia do §7, uma peça por vez |
| 4 | "Venda" (ação: armazém/venda) | minério na superfície | 1ª venda em < 60 s (§56) |
| 5 | "Contrate o minerador" (ação) | 1º Cash suficiente | pilar Automação: o toque manual vira máquina |
| 6 | "Isto é um gargalo" (explicação: a pilha piscando "travada") | 1ª vez que o elevador acumula | a matemática do §15 vista, não lida |
| 7 | "Melhore o elevador" (ação) | logo depois do 6 | fecha o gargalo e ensina o menu de upgrade |
| 8 | "Contrate o gerente da camada" (ação) | 1º gerente acessível | a camada roda sozinha (MVP do §51) |
| 9 | "Desça: abra a camada 2" (ação: medidor de profundidade) | Cash para a 2ª camada | a pergunta "o que existe mais abaixo?" |
| 10 | "Escolha o veio" (explicação: os 3 veios no corte) | ao abrir a camada 3 | a 1ª decisão real (UG-1); trocar custa tempo, nunca dinheiro |
| 11 | "Toque na parede: a silhueta mostra o que tem atrás" (ação) | 1ª parede com raio-X | mistério sem sorteio (UG-2); meta: ≥ 60% abrem |
| 12 | "300 m: precisa da broca nível X" (explicação) | 1ª vez perto do gate | a meta da sessão fica visível logo abaixo (§31) |
| 13 | "A mina rendeu enquanto você estava fora" (explicação: cofre) | 1ª volta com ≥ 60 s fora | teto de 2 h e 2× opcional; o botão de coletar sem anúncio fica sempre visível |

- **Ritmo:** os passos 1–4 cabem nos primeiros 60 s. Os outros nascem dos gatilhos, espaçados, para não virar parede de texto. Se o turno da noite (UG-6) entrar, ganha um passo na 1ª saída.
- **Controle:** o jogo é de toque, sem joystick. A lição "nenhum desenho tampa o personagem" vira "a mão do tutorial e os balões não tampam a estação-alvo".

### Monetização e compliance
- **1 moeda (Cash) na v0.1** (§21 já revisado). Gems, Research Points e Core Tokens só entram com ralo no mapa de fontes e ralos.
- **Nada aleatório pago.** A parede com raio-X (§17, UG-2) e os baús de conteúdo fixo (§37) já estão alinhados. Falta alinhar o que o §13 e o §28 deixam aberto (ver os conflitos).
- **Rewarded sempre opcional:** 2× no claim do cofre e boost de 5 min (§51), com o botão "coletar" sem anúncio ao lado.
- **Anúncio não personalizado para todos, sem `AD_ID`.** `LevelPlayPrivacySettings` com GDPR sem consentimento, CCPA opt-out e COPPA desligado, antes do `Init`; `Setup.SemIdDePublicidade` (pós-geração do Gradle) tira o `AD_ID` e as 3 permissões do Privacy Sandbox do manifesto; na Play, a declaração de ID de publicidade é **não**. O app do jogo nasce na conta **V-STACK** do LevelPlay (o Forge tinha ficado em outra conta). Sem chave, o jogo cai no simulador e não chama o `Init`. **Reaproveitar:** `dc:Scripts/View/Anuncios.cs`, `AnunciosLevelPlay.cs` e `dc:docs/MONETIZACAO.md` §4.
- **Interstitial desligado na v0.1** (§36). Quando houver, a regra de quando mostrar mora no núcleo, nunca no SDK (no DC: `sim.InterstitialDue`).
- **Offline com teto de 2 h como trava no código.** O Tuning só encurta, nunca alonga (como o `Balance.OfflineCapSeconds` do Forge). Também valem o teto relativo de 2× o upgrade mais barato ainda travado, Δt ≤ 0 pagando 0 e um id de transação por claim. **Reaproveitar:** `fs:Scripts/Core/Sim.cs` (`ApplyOffline`).
- **IAP, só quando o Vinicius aprovar.** Unity IAP 5.4.3 atrás de uma interface, com loja falsa no PC; compra em 2 passos (o núcleo concede e só então confirma, para não perder a compra se o app fechar); restaurar compras; produtos de conteúdo fixo, listados na loja. **Reaproveitar:** `dc:Scripts/View/Loja.cs` e `LojaIap.cs`.
- **Analytics e privacidade.** Os eventos do §48 são só eventos de jogo, sem dado pessoal. O diário local vem antes de qualquer SDK, e todo SDK entra na tabela de segurança dos dados da Play. A política de privacidade fica pública no GitHub Pages (branch `gh-pages`, 4 idiomas) e cita exatamente as redes usadas.

### Play e lançamento
- **Conta de organização.** A Play Console da V-STACK espera o D-U-N-S grátis pedido no DC (previsão 2026-11-25), e a mesma conta publica este jogo. Não abra conta pessoal nem pague o plano de ~R$ 1.700/ano. A lição do DC é que a burocracia de conta leva ~30 dias úteis: começa no início do projeto, nunca no fim.
- **appId e nome antes do `Setup.cs`.** O `br.com.vstack.<nome>` é irreversível depois de publicado.
- **Chave de upload fora do git**, com backup fora do PC: `%USERPROFILE%/.undergroundinc/upload.jks` + `upload.properties`, como o DC faz em `.dungeoncourier/`. Se a chave se perder, é preciso pedir reset ao suporte.
- **AAB assinado** por `Setup.BuildAndroidBundle`. No DC, isso foi conferido: targetSdk 36, bibliotecas nativas alinhadas a 16 KB e Google Play Billing 9.
- **Loja e criativos por script, do jogo real:** 8 capturas × 4 idiomas do build de release (sem "Development Build"), ícone 512, feature graphic 1024×500 e os vídeos 9:16 dos criativos do §50/§55 ("How deep can you go?", "qual veio você abriria?", "o que tem atrás da parede?"), gravados com `-record`. Esse material serve também ao teste de criativos Underground × Forge (§51). **Reaproveitar:** `dc:client/tools/loja_fotos.sh`, `loja_assets.py`, `criativos.py`, `dc:docs/LOJA.md` e `CRIATIVOS.md`.
- **Pré-release no GitHub** a cada versão, com APK, AAB, zip Windows e o pacote da loja.

### Android
- **Taxa de quadros:** `QualitySettings.vSyncCount = 0` e `Application.targetFrameRate = 60` logo no início (no DC, o POCO F4 foi de 28–36 para 55 fps). Depois, meça bateria e temperatura numa sessão longa; no Forge, a bateria ficou em até 41 °C.
- **APK de worktree:** gere via `subst R: <client>`, porque caminho longo com espaço quebra o CMake do Gradle. O worktree vai em caminho curto (`%TEMP%\wt\...`), nunca no scratchpad (estoura o MAX_PATH).
- **adb no Git Bash:** `adb shell "am start -n <pkg>/<act> -e unity '-a -b'"`, com as aspas por dentro; sem elas, só o 1º argumento chega ao jogo.
- **Aparelho:** mantenha só o APK atual (o build apaga os anteriores). Pergunte ao Vinicius antes de usar o celular dele e fotografe só com o jogo em primeiro plano.
- **Desempenho se mede em aparelho original de entrada.** O POCO de 4 anos se limita depois de 1 min e não serve de régua. A mina "enorme" do §47 (pooling, simulação agregada fora da tela) se prova com o PSS e o FPS medidos no aparelho. **Reaproveitar:** `fs:client/tools/medir_aparelho.sh`.

### Conflitos com o GDD atual
Os conflitos ficam só apontados aqui; as outras seções do GDD não foram editadas. Todos pedem decisão do Vinicius.
1. **§22, offline "com upgrades, no máximo 8 h", contra o guardrail de 2 h.** **Recomendação:** 2 h como trava no código na v0.1. Os upgrades do §19 (+10% offline efficiency) sobem a **taxa**, não o teto. Teto maior só com decisão registrada.
2. **§36 (interstitial na v0.2, por RemoteConfig) contra o §55 UG-5 ("interstitial nunca").** O próprio GDD se contradiz. **Recomendação:** decidir antes do contrato da v0.2. Se entrar, que seja como no DC: um único ponto natural (lá, o CONTINUAR entre contratos; aqui, a volta à superfície), nunca nos 3 primeiros do dia, no máximo 1 a cada 4 min, decidido pelo núcleo (`sim.InterstitialDue`), sumindo com Remove Ads, e com a unidade vazia no `config.json` desligando tudo.
3. **§13, §28 e §35 juntos:** "funcionários raros podem ter habilidades" (§13), Premium Track com workers e gems (§28), Gem Packs e Engineer Pack (§35). Sem regra, isso vira trabalhador raro comprado com gem, que é aleatório pago e segunda moeda premium. **Recomendação:** trabalhador raro sai por marco de profundidade, e pacote pago tem conteúdo fixo e listado. O `Equipe.cs` do Forge já segue "worker fixo e nomeado, nenhum traço sorteado".
4. **§31 (primeiro dia com "constrói refinaria") contra o §51 (MVP sem refinaria).** O tutorial acima segue o MVP. **Recomendação:** alinhar o §31 ao MVP quando o contrato da v0.1 for escrito.
5. **§10 e §19 ("+5% rare mineral chance").** Chance é sorteio. Não é pago hoje, mas um evento (§26, Crystal Storm) somado a um boost comprado chegaria perto. **Recomendação:** mineral raro por sequência determinística (Weyl, como o VIP do Forge e a parede do UG-2), o que também facilita testar.
6. **§43 ("workers são sprites com tween") contra a rota do DC (folhas animadas por clipe).** Animação de verdade custa APK: no DC, as folhas HD somaram 15 MiB. **Recomendação:** folha animada para o minerador e o gerente, que são a "mina viva" do §43; tween para carrinho, elevador e máquinas.
7. **§51 ("antes de construir, um teste só de criativos") contra o guardrail "criativos gravados do jogo real".** Criativo de mockup está vetado. **Recomendação:** o teste precisa de um greybox jogável mínimo (núcleo + View procedural) gravado com `-record`; o núcleo do Forge (§57) encurta esse greybox.
8. **Personagem do cartão de contexto.** O GDD não tem nenhum personagem com nome. **Recomendação:** aprovar (ou trocar) "Jade, a geóloga" e as duas falas acima.

### Primeiros passos recomendados
1. Decidir os conflitos 1, 2, 3, 7 e 8 e registrar a decisão no GDD.
2. Quando o Vinicius pedir o projeto neste grupo: escrever `docs/CONTRATO_V01.md` e a matriz `docs/CONTRATO_LANCAMENTO.md`, e abrir `_memoria/STATUS_underground-inc.md`.
3. Montar o esqueleto (núcleo do Forge + casca do DC, namespace `UG`) com o portão verde ainda vazio.
4. Fazer núcleo e bot antes de qualquer arte, em greybox procedural, e provar o UG-1 (nenhum veio acima de 70%) e o UG-5 (≤ 12 min de jogo ativo até os 300 m, também no bot lento ×0,4).
5. Pôr o tutorial (passos 1–9), o cartão da geóloga e o diário no greybox, e medir a "1ª venda em < 60 s" com gente, não com o bot.
6. Gravar os criativos do greybox com `-record` para o teste do slot idle (§51).
7. Só com o jogo validado: Lote 1 de arte (≈ 245–355 créditos, com aval), UI pintada grátis, ícone adaptativo, appId e chave de upload com backup.
