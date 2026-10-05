# Etapa 5 Matriz de síntese e organização da revisão

## Solicitação

Compare os artigos e organize a revisão por temas ou eixos. Não produza apenas uma sequência de resumos.

## Eixos da revisão

1. `Eficiência Energética e Otimização de Infraestrutura (Virtualização e Arrefecimento)`
2. `Impactos Econômicos e Relação Custo-Benefício em Médias Empresas`
3. `Barreiras Operacionais, Culturais e Gargalos de Implementação`

## Matriz de síntese

|Eixo|Artigos relacionados|Convergências|Divergências|Limitações|Lacunas|
|-|-|-|-|-|-|
|`Eixo 1: Eficiência Energética e Otimização`|`Ormeño Ramos et al. (2026); Maciel (2025)`|`Ambos apontam a virtualização de servidores e o ajuste térmico como as estratégias mais diretas para cortar o consumo de energia e baixar o PUE.`|`Ormeño Ramos foca em métricas globais e algoritmos de controle térmico em data centers, enquanto Maciel analisa o impacto direto na infraestrutura corporativa nacional.`|`Trabalhos focam em métricas puramente técnicas sem detalhar o custo financeiro das ferramentas de gestão.`|`Pouco detalhamento sobre como a virtualização afeta sistemas legados que exigem alta disponibilidade constante.`|
|`Eixo 2: Impactos Econômicos em Médias Empresas`|`Maciel (2025); Pushpakumari et al. (2023)`|`Concordam que a redução na quantidade de nós físicos alivia a conta de luz e diminui custos recorrentes de manutenção.`|`Maciel destaca o ganho financeiro a médio prazo, enquanto Pushpakumari ressalta o peso do custo de capital inicial como freio para PMEs.`|`Amostras abrangem realidades empresariais distintas, variando conforme o nível de maturidade digital do país ou região.`|`Falta de dados comparativos padronizados sobre o tempo exato de retorno do investimento (ROI) em médias empresas brasileiras.`|
|`Eixo 3: Barreiras e Desafios Operacionais`|`Pushpakumari et al. (2023); Ormeño Ramos et al. (2026)`|`Apontam que a falta de capacitação técnica da equipe e a resistência cultural travam a transição para práticas mais limpas.`|`Pushpakumari foca em gargalos financeiros e de gestão em PMEs, enquanto Ormeño Ramos foca em limitações de arquitetura de hardware e simulação.`|`Grande parte da literatura prioriza grandes corporações, tratando PMEs de forma genérica.`|`Ausência de roteiros ou metodologias simplificadas para equipes enxutas de TI aplicarem TI Verde sem consultoria externa.`|


## Roteiro da revisão da literatura

### Eixo 1

* Ideia principal: `A consolidação de servidores por meio da virtualização, aliada ao controle do arrefecimento, é o meio mais rápido e eficiente para reduzir o consumo energético e melhorar o PUE na infraestrutura de TI.`
* Evidências que serão usadas: `Dados do estudo sistemático de Ormeño Ramos et al. (2026) sobre a queda nas métricas de emissão/PUE e análises de Maciel (2025) sobre a redução de carga térmica e racionalização do uso do hardware.`
* Comparação entre estudos: `Ormeño Ramos et al. (2026) fundamentam a eficácia técnica do ponto de vista sistêmico em data centers, enquanto Maciel (2025) aproxima esses conceitos da realidade das salas de servidores corporativas, validando que a diminuição de hardware físico alivia diretamente os sistemas de climatização.`
* Ligação com o problema: `Responde à primeira parte da pergunta de pesquisa, provando tecnicamente como o uso de virtualização e refrigeração adequada reduz a demanda de energia elétrica.`

### Eixo 2

* Ideia principal: `Embora a TI Verde traga economia financeira sustentada na conta de energia e na manutenção, a percepção do custo inicial e a limitação técnica de equipes em médias empresas atrasam a sua adoção.`
* Evidências que serão usadas: `Levantamento de Pushpakumari et al. (2023) sobre restrições orçamentárias e falta de especialização em PMEs, confrontados com as projeções de eficiência e cortes de custos de operação apresentados por Maciel (2025).`
* Comparação entre estudos: `Enquanto Maciel (2025) enfatiza os benefícios econômicos resultantes da otimização operacional, Pushpakumari et al. (2023) contrapõem mostrando que, na prática, a barreira financeira inicial e o desconhecimento dos gestores impedem que esses benefícios sejam alcançados no curto prazo.`
* Ligação com o problema: `Conecta diretamente a viabilidade financeira e os desafios de execução ao contexto de médias empresas, respondendo aos objetivos específicos sobre custos e gargalos operacionais.`


## Síntese crítica provisória

`Olhando para o que a literatura recente mostra, fica bem claro que a TI Verde realmente entrega o que promete quando o assunto é cortar gasto com energia — principalmente se a empresa focar em virtualizar servidores e organizar a refrigeração do ambiente. O problema é que existe uma distância grande entre o que a teoria prega e o que acontece no dia a dia. De um lado, os estudos mais técnicos só mostram as vantagens e a economia que vem com o tempo. Do outro, as pesquisas focadas no ecossistema de pequenas e médias empresas escancaram que a realidade é bem mais complicada: o preço para começar a mudança é alto e a maioria das equipes não tem braço nem conhecimento técnico para tocar isso sozinha. O que falta no mercado hoje é justamente um meio-termo — um passo a passo prático e números reais que mostrem para o dono de uma média empresa em quanto tempo esse investimento se paga na prática, sem precisar gastar uma fortuna com consultoria externa.`

## Checklist

* \[X] Os artigos foram agrupados por ideias.
* \[X] Há comparações entre estudos.
* \[X] As divergências foram registradas.
* \[X] As lacunas são específicas e sustentadas pelas leituras.

