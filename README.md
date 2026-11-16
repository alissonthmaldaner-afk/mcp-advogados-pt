# mcp-advogados-pt — direito português no Claude e noutros assistentes de IA

**Legislação, jurisprudência e Citius num só conector. Só para advogados.**

O mcp-advogados-pt liga o Claude, e outros assistentes de IA compatíveis com MCP (Model Context Protocol), às fontes do direito português. Com ele, o assistente pode ir buscar o artigo, o acórdão ou a portaria à fonte, no momento do pedido, em vez de citar de memória, e indica o endereço para conferir. No Citius, na área reservada do mandatário, recolhe as notificações, os movimentos e os integrais dos processos do próprio advogado.

**[Comprar — 29 € a cada 30 dias](https://buy.stripe.com/00wbJ1eml1UQ1E37Si9ws02)** · [Termos de serviço](https://azevedoemaldaner-adv.pt/termos-mcp-advogados-pt.html) · [Contacto](mailto:licencas@azevedoemaldaner-adv.pt)

## O que faz

São três conectores, cobertos por uma só licença.

### Legislação — `legislacao-pt`

- **PGD Lisboa.** Pesquisa no título, no sumário e no texto dos artigos. Texto em vigor de cada artigo, com o diploma que lhe deu a redação atual e as versões anteriores. Leitura de um regime inteiro de uma vez, com a localização sistemática.
- **Diário da República.** Portarias, despachos, decretos e os demais atos. O ato tal como foi publicado e o texto consolidado, na redação em vigor à data pedida, com a redação futura à parte.
- **Direito da União Europeia.** Regulamentos, diretivas e decisões, no texto do Jornal Oficial e na versão consolidada. Acórdãos do TJUE que interpretam um ato e medidas de transposição notificadas por Portugal.
- **Custas.** As tabelas do Regulamento das Custas Processuais, na versão em vigor.

Pedidos de exemplo:

- «Mostra-me o artigo 1287.º do Código Civil e as redações anteriores.»
- «Procura no Diário da República as portarias sobre apoio judiciário e mostra o texto consolidado da mais recente.»
- «Qual é a versão em vigor do Regulamento (UE) 2016/679 e que acórdãos do TJUE o interpretam?»
- «Mostra-me a tabela de taxas de justiça em vigor.»

### Jurisprudência — `jurisprudencia-pt`

- **dgsi.pt.** Supremo Tribunal de Justiça, Relações de Lisboa, Porto, Coimbra, Évora e Guimarães, Supremo Tribunal Administrativo, Tribunais Centrais Administrativos Norte e Sul, Tribunal dos Conflitos, Julgados de Paz, pareceres do Conselho Consultivo da PGR e cláusulas contratuais gerais abusivas. Pesquisa por texto livre e por campo (relator, processo, descritores, datas), com o sumário e o inteiro teor.
- **Tribunal Constitucional.** Pesquisa por texto, número, processo, espécie, secção, relator e datas, com o inteiro teor.
- **CAAD.** Decisões arbitrais tributárias, por texto, tema, artigos, processo, imposto e datas, com o texto integral.

Pedidos de exemplo:

- «Procura acórdãos do Supremo Tribunal de Justiça sobre usucapião, de 2023 em diante, e resume os sumários.»
- «Que acórdãos do Tribunal Constitucional deste ano tratam de proteção de dados?»
- «Procura decisões do CAAD sobre mais-valias em IRS.»

### Citius — `processos-pt`

Atua na área reservada do mandatário, com a sessão que o próprio advogado abre:

- lista as notificações eletrónicas sem abrir nenhuma e sem mudar o estado de leitura;
- guarda um PDF por notificação, deixando as não lidas por abrir, salvo pedido expresso;
- lê os processos movimentados nos últimos 30 dias e a lista dos processos do mandatário;
- junta num só PDF o integral de cada processo, indo buscar só os atos que ainda faltam;
- gera uma cópia para impressão, com uma etiqueta lateral em cada página.

Pedidos de exemplo:

- «Abre o Citius.»
- «Que notificações recebi esta semana?»
- «Descarrega as notificações novas.»
- «Atualiza o integral do processo 1234/25.0BELSB, com cópia para impressão.»

## Fontes

| Fonte | Endereço | O que se obtém |
|---|---|---|
| PGD Lisboa | pgdlisboa.pt | Legislação consolidada, artigo a artigo, com as versões anteriores |
| Diário da República | diariodarepublica.pt | Atos publicados e textos consolidados |
| Serviço das Publicações da UE | publications.europa.eu | Atos da UE, versões consolidadas, acórdãos do TJUE e transposição |
| Bases jurídico-documentais | dgsi.pt | Acórdãos dos tribunais judiciais e administrativos, pareceres da PGR, cláusulas abusivas |
| Tribunal Constitucional | tribunalconstitucional.pt | Acórdãos |
| CAAD | caad.org.pt | Decisões arbitrais tributárias |
| Citius | citius.tribunaisnet.mj.pt | Notificações, movimentos e integrais dos processos do advogado |

As fontes são consultadas no momento do pedido, diretamente a partir do computador do advogado, e cada resposta traz o endereço da fonte.

## As 30 ferramentas

### Legislação (12)

| Ferramenta | O que faz |
|---|---|
| `pesquisar_legislacao` | Pesquisa diplomas na PGD Lisboa, no título, no sumário e no texto dos artigos. |
| `obter_diploma` | Dados de um diploma: designação, sumário, número de artigos e de versões, e os diplomas que o alteraram. |
| `obter_artigo` | Texto em vigor de um artigo, com a nota de alteração e as versões anteriores. |
| `obter_articulado` | Vários artigos seguidos de um diploma, com a localização sistemática (livro, título, capítulo, secção). |
| `rcp_tabelas` | Tabelas I a V do Regulamento das Custas Processuais, na versão em vigor à data. |
| `dre_pesquisar` | Pesquisa atos no Diário da República, incluindo portarias, decretos e despachos. |
| `dre_obter_ato` | Um ato tal como foi publicado: sumário, texto integral com as tabelas dos anexos e ligação ao PDF. |
| `dre_obter_consolidado` | Texto consolidado de um diploma, na redação em vigor à data indicada; a redação futura vem à parte. |
| `ue_pesquisar` | Pesquisa atos da UE, acórdãos do TJUE e tratados, pelo título em português ou pelo número. |
| `ue_obter_ato` | Texto em português de um ato da UE tal como publicado no Jornal Oficial, ou de um acórdão do TJUE. |
| `ue_obter_consolidado` | Versão consolidada de um ato da UE à data indicada, com a indicação da versão usada. |
| `ue_jurisprudencia_e_transposicao` | Acórdãos do TJUE que interpretam um ato e, nas diretivas, as medidas de transposição notificadas por Portugal. |

### Jurisprudência (7)

| Ferramenta | O que faz |
|---|---|
| `listar_tribunais` | Lista as bases de jurisprudência do dgsi.pt disponíveis. |
| `pesquisar_acordaos` | Pesquisa numa base do dgsi.pt por texto livre, relator, processo, descritores e datas, e devolve os sumários. |
| `obter_acordao` | Inteiro teor e metadados de um acórdão do dgsi.pt. |
| `tc_pesquisar` | Pesquisa acórdãos do Tribunal Constitucional por texto, número, processo, espécie, secção, relator e datas. |
| `tc_obter_acordao` | Inteiro teor de um acórdão do Tribunal Constitucional, com processo, secção e relator. |
| `caad_pesquisar` | Pesquisa decisões arbitrais tributárias do CAAD por texto, tema, artigos, processo, imposto e datas. |
| `caad_obter_decisao` | Uma decisão do CAAD: processo, data, impostos, valor do pedido, tema, ligação ao PDF e texto integral. |

### Citius (11)

| Ferramenta | O que faz |
|---|---|
| `iniciar_sessao` | Abre o Chrome ou o Edge na página de entrada do Citius, para o advogado entrar pessoalmente. |
| `estado_sessao` | Diz se a sessão está ativa, a tarefa em curso e a fila, e a pasta onde ficam os ficheiros. |
| `terminar_sessao` | Cancela as tarefas, sai do Citius e fecha o browser. |
| `listar_notificacoes` | Lista as notificações eletrónicas sem abrir nenhuma e sem mudar o estado de leitura. |
| `recolher_notificacoes` | Guarda um PDF por notificação e atualiza o índice; as não lidas ficam por abrir, salvo pedido expresso. |
| `listar_movimentos` | Processos movimentados nos últimos 30 dias: processo, data e ato. |
| `listar_processos` | Árvore de tribunais, juízos e processos do mandatário, com os findos e as cartas precatórias. |
| `atualizar_integral` | Atualiza o integral de cada processo num só PDF, indo buscar só os atos que ainda não estão em disco. |
| `gerar_impressao` | Gera a cópia para impressão a partir do que já está em disco, em A4, com etiqueta lateral em cada página. |
| `estado_tarefa` | Estado, progresso e resultado de uma tarefa em segundo plano. |
| `cancelar_tarefa` | Cancela uma tarefa em curso ou na fila; o que já foi gravado fica. |

## Para quem

O mcp-advogados-pt é vendido apenas a advogados com inscrição em vigor na Ordem dos Advogados, para uso profissional. Na compra é pedido o número da cédula profissional, que é conferido na pesquisa pública de advogados da Ordem antes de a chave de ativação ser enviada. Cada advogado só pode ter uma licença ativa.

## Requisitos

- **Um assistente de IA que aceite servidores MCP locais.** Foi testado no Claude Desktop e no Claude Code. Noutros assistentes compatíveis com MCP deve funcionar da mesma forma, mas não foi testado. As versões que só funcionam no browser não servem, porque os conectores correm no computador do advogado. A conta do assistente não está incluída na licença.
- **Windows.** É o sistema em que foi testado. No macOS ainda não foi testado.
- **Ligação à Internet.**
- **Google Chrome ou Microsoft Edge**, para o Citius.
- No Claude Desktop não é preciso instalar mais nada. No Claude Code e noutros assistentes é preciso o Node.js 22 ou superior.

## Comprar e instalar

### Preço e licença

- 29 € por cada período de 30 dias, cobrados antecipadamente. A subscrição renova-se sozinha até ser cancelada.
- Pode ser cancelada a qualquer momento. A licença mantém-se até ao fim do período já pago; o período iniciado não é reembolsado.
- A licença é pessoal e vale para um computador de cada vez. Para mudar de computador basta instalar no novo e usar a mesma chave, uma vez a cada 7 dias.
- De cada pagamento é emitida fatura.

As condições completas estão nos [termos de serviço](https://azevedoemaldaner-adv.pt/termos-mcp-advogados-pt.html).

### Passos

1. **Comprar.** Na [página de pagamento](https://buy.stripe.com/00wbJ1eml1UQ1E37Si9ws02) indica-se o nome do titular da licença e o número da cédula profissional, e aceitam-se os termos de serviço.
2. **Receber a chave.** Conferida a cédula, o que em regra acontece logo a seguir ao pagamento, seguem por email a chave de ativação, o endereço para descarregar o conector e as instruções de instalação.
3. **Instalar no Claude Desktop.** Descarregar o ficheiro `mcp-advogados-pt.mcpb`, abrir Configurações → Extensões → Configurações avançadas → Instalar extensão, escolher o ficheiro e colar a chave de ativação.
4. **Usar.** Pedir, por exemplo, «mostra-me o artigo 1287.º do Código Civil». A licença ativa-se sozinha na primeira utilização e fica ligada a esse computador.

No Claude Code e noutros assistentes a instalação faz-se a partir de um ficheiro zip, com as instruções que seguem no email.

A extensão para o Claude Desktop atualiza-se sozinha: procura versões novas, no máximo uma vez a cada 6 horas, e só as aceita com assinatura digital.

O ficheiro da versão atual é público e pode ser descarregado aqui: [mcp-advogados-pt.mcpb](https://github.com/alissonthmaldaner-afk/licencas-estado/releases/latest/download/mcp-advogados-pt.mcpb). Só funciona com uma chave de ativação.

## O que não é

- Não substitui a consulta do Citius e das fontes oficiais nem o controlo de prazos, e não calcula prazos.
- É uma ferramenta de pesquisa e de recolha. Os textos vêm com o endereço da fonte e devem ser confirmados nela antes de serem usados em peças ou em pareceres.
- Não é um serviço jurídico.
- Não é oficial. Não tem ligação ao Ministério da Justiça, aos tribunais, às entidades que mantêm as fontes consultadas nem a fornecedores de IA. As marcas referidas pertencem aos respetivos titulares.
- As fontes pertencem a terceiros e podem mudar sem aviso. Se mudarem, os conectores podem deixar de funcionar, no todo ou em parte, até serem adaptados.

## Privacidade

- **No Citius entra o advogado, pessoalmente**, na janela do browser que o conector abre. O conector não pede, não lê e não guarda senhas, e não contorna CAPTCHA nem bloqueios: se o Citius os apresentar, pára e avisa.
- O conector faz um pedido de cada vez, a ritmo fixo, e só na área reservada do próprio advogado.
- **Os documentos recolhidos ficam só no computador do advogado.** Não passam pelo prestador, que não tem acesso a eles.
- As pesquisas e as recolhas são feitas diretamente do computador do advogado às fontes. Não passam pelo prestador nem são registadas por ele.
- A confirmação da licença leva apenas o número da licença. A ativação leva um código derivado da chave e um código do computador. Não seguem o nome do advogado, documentos nem o que este pesquisa.
- O que os conectores devolvem ao assistente entra na conversa e fica sujeito, como o resto dela, aos termos do fornecedor desse assistente.

A informação completa sobre dados pessoais está nos [termos de serviço](https://azevedoemaldaner-adv.pt/termos-mcp-advogados-pt.html).

## Contacto e prestador

O mcp-advogados-pt é prestado por Álisson Thiago Maldaner. A identificação completa do prestador e as condições da licença constam dos [termos de serviço](https://azevedoemaldaner-adv.pt/termos-mcp-advogados-pt.html).

Dúvidas e pedidos: [licencas@azevedoemaldaner-adv.pt](mailto:licencas@azevedoemaldaner-adv.pt).

## English summary

mcp-advogados-pt is a paid MCP (Model Context Protocol) server bundle that connects Claude and other MCP-capable AI assistants to Portuguese legal sources: legislation (PGD Lisboa, Diário da República and EU law), case law (dgsi.pt, the Constitutional Court and CAAD tax arbitration) and Citius, the Portuguese courts' portal, in the lawyer's own reserved area. It provides 30 tools and runs locally, as a Claude Desktop extension (.mcpb) or as stdio servers for other clients. It is sold only to lawyers registered with the Portuguese Bar Association, at 29 € per 30-day period. The tools, the documentation and the support are in Portuguese. It is not an official service and is not affiliated with the Portuguese courts, the Ministry of Justice or any AI provider.
