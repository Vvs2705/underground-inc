# Underground Inc.

**Estilo:** idle/tycoon de mineração em corte vertical, retrato.

**O que é:** uma mineradora que começa na superfície e desce cada vez mais fundo.

**Como funciona:** você minera, o elevador sobe o minério, a refinaria transforma e você vende; com o lucro melhora máquinas, contrata e desce para a próxima camada — cavernas, ruínas, criaturas e minerais raros. Cada camada traz um veio com escolha (não é só mais do mesmo) e uma parede com raio-X que mostra o que vem, sem sorteio.

**Como vai ser jogar:** ver a mina crescer para baixo e virar uma máquina industrial, sempre com algo novo embaixo.

## Situação
Alternativa ao Forge Street no slot idle; pode reaproveitar o núcleo do Forge (simulação por tick, bot de balance, cofre offline). Ainda não há código: este repositório guarda o GDD e a estrutura do projeto, pronta para o desenvolvimento começar.

- **GDD:** [`docs/GDD.md`](docs/GDD.md) (revisão competitiva de 2026-10-09 no topo).
- **Comparativo com jogos similares e diferenciais:** [`docs/COMPETITIVO.md`](docs/COMPETITIVO.md).

## Estrutura do repositório
| Pasta | Para quê |
|---|---|
| `docs/` | GDD, comparativo e, depois, balance, validações e contratos de cada fase |
| `client/` | projeto Unity 6 (6000.3.x), Android primeiro, retrato; código do jogo em `client/Assets/_UI/` |
| `client/Assets/_UI/Scripts/Core/` | núcleo em C# puro (regras, simulação, save), testável fora do Unity |
| `client/Assets/_UI/Scripts/View/` | MonoBehaviours, UI, câmera, entrada |
| `client/Assets/_UI/Editor/` | setup do projeto e builds por linha de comando |
| `client/Assets/_UI/Tests/EditMode/` | testes NUnit do núcleo |
| `client/Assets/_UI/Resources/` | sprites e dados carregados em tempo de execução |
| `client/tools/` | ferramentas fora do Unity (testes `dotnet`, scripts de arte, relatório de playtest) |
| `arte/` | arte-fonte; `arte/tripo/` e `arte/mixamo/` ficam fora do git |

Como contribuir: [`CONTRIBUTING.md`](CONTRIBUTING.md). Histórico: [`CHANGELOG.md`](CHANGELOG.md).

## Repositório e licença
© V-STACK / Vinicius Souza. **Todos os direitos reservados.** Código, documentos e arte visíveis para acompanhamento, sem licença de uso, cópia ou redistribuição.
