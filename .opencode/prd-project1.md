# PRD — HELIO 2.0
## O sistema operacional da sua energia solar

> *Veja o sol trabalhando na sua casa antes de comprar um único painel. Depois, deixe que ele trabalhe por você.*

| | |
|---|---|
| **Documento** | PRD completo e autônomo (não depende de nenhum outro documento) |
| **Versão** | 2.0 |
| **Mercado inicial** | Brasil — residências, condomínios, pequenos comércios |
| **Idioma** | pt-BR (arquitetura pronta para en / es) |
| **Stack inicial** | TanStack Start (React) + Router + Query + Table + Form + Virtual; Store, DB e AI sob avaliação em spike |
| **Plataformas** | Web (PWA) primeiro; WhatsApp, widgets e Live Activities como extensões |
| **Estado das premissas** | Metas, números e prazos são **hipóteses** a calibrar; itens regulatórios e de integração exigem validação jurídica e com parceiros |

### Como ler este documento

| Se você tem… | Leia |
|---|---|
| 2 minutos | O TL;DR logo abaixo |
| 10 minutos | Partes 1 e 2 (por que existe, o que é) |
| 30 minutos | Partes 3 e 4 (experiência e telas) |
| Papel de engenharia | Partes 5 e 6 (arquitetura, dados, IA, qualidade) |
| Papel de negócio | Parte 7 (modelo, crescimento, métricas, roadmap, riscos) |

---

## TL;DR

**O que é:** uma plataforma que acompanha a pessoa em **cinco atos** da vida solar: **Descobrir → Decidir → Instalar → Viver → Compartilhar**.

**A ideia central:** o HELIO não vende painéis. Ele vende **certeza**. Certeza do que vai gerar, do que está gerando, de quanto vai economizar e de quem está dizendo a verdade.

**Seis apostas que o tornam diferente:**

1. **Gêmeo Solar:** uma maquete 3D viva da *sua* casa, com sol, nuvens e produção reais, que é a tela inicial do produto.
2. **Auditoria de Proposta:** envie a proposta que você já recebeu e saiba em 2 minutos se ela está inflada.
3. **Arena de Lances:** instaladores verificados disputam, às cegas e padronizados, o seu projeto.
4. **Piloto Automático Solar:** o HELIO move boiler, ar-condicionado, bomba de piscina e carro elétrico para as horas de sol, e economiza mais do que o painel sozinho.
5. **Promessa vs Realidade:** o produto publica, abertamente, o quanto suas próprias estimativas erram.
6. **Palco Persistente:** uma única cena 3D viaja entre todas as páginas, então o mesmo sol que abre o site é o que ilumina o seu telhado.

**Linguagem visual:** *Fotônica*, um sistema de design em que a luz do sol real controla cor, contraste, atmosfera e som. Onze **Mundos** visuais distintos (do cinema da landing ao terminal financeiro, do atlas cartográfico ao papel editorial) compartilham a mesma gramática de movimento, tipografia e interação.

**Compromisso de qualidade:** toda experiência espetacular tem versão leve, acessível e completa. Beleza que exclui não conta.

---

# PARTE 1 — POR QUE O HELIO EXISTE

## 1.1 Comunicado de imprensa do futuro (*working backwards*)

> *Texto de trabalho para alinhar ambição e narrativa. Os números são fictícios e servem apenas para dar forma à visão; não são metas comprometidas.*

**HELIO passa de 250 mil casas e provou que energia solar pode ser vendida com a verdade**

*São Paulo, 14 de março de 2028.* O HELIO, plataforma brasileira de energia solar, anunciou hoje que acompanha 250 mil sistemas e que, nos últimos 12 meses, suas estimativas de geração ficaram dentro de ±6% do que os telhados realmente produziram. O número é público, atualizado todo dia, e qualquer pessoa pode verificá-lo na página "Promessa vs Realidade".

Quem abre o HELIO vê sua própria casa em miniatura, dentro de uma cúpula de vidro, com o céu real do bairro. Quando uma nuvem cruza o telhado, a sombra passa pelos painéis e a curva de geração cai ao mesmo tempo. Arrastando o dedo, a pessoa viaja do nascer do sol ao fim da tarde, do verão ao inverno, de hoje até 2051.

"A gente cansou de ver gente ser enganada por planilha de vendedor", diz a equipe fundadora. "Então colocamos a verdade em cima da mesa, em 3D, e deixamos o sol falar."

**O que as pessoas mais usam:**
- **Auditoria de Proposta:** mais de 400 mil propostas analisadas; uma em cada três tinha geração prometida acima do que o modelo considera plausível.
- **Piloto Automático Solar:** em média, famílias que ativam o recurso aumentam a economia mensal em 18% sem trocar nenhum equipamento.
- **Arena de Lances:** o preço médio por Wp nas compras feitas pela plataforma ficou abaixo da média das propostas diretas.
- **Vila Solar:** 3 mil comunidades compartilham créditos entre vizinhos, e inquilinos agora também têm acesso à energia solar.
- **Seu Ano Solar:** o resumo anual foi compartilhado por 1 em cada 4 usuários.

**Depoimento (fictício):** "Eu achava que painel solar era coisa de rico e de vendedor. Mandei a proposta que recebi, o HELIO mostrou que estavam prometendo 22% a mais do que o telhado entrega. Fiz a Arena, economizei R$ 7 mil e hoje meu boiler esquenta com o sol do meio-dia." — *Marina, proprietária*

## 1.2 Perguntas difíceis (FAQ interno)

**1. Por que alguém confiaria num site de energia solar?**
Porque a confiança é construída com prova, não com promessa: a precisão do próprio modelo é pública (Promessa vs Realidade); ranking de instaladores não é comprável; toda estimativa mostra premissas, faixa e fonte; e o usuário pode ativar o "Modo Auditoria" para ver cada fórmula.

**2. Experiência 3D pesada não vai excluir quem tem celular modesto?**
Não, porque o 3D é uma camada, nunca o conteúdo. Há quatro níveis de fidelidade, detecção automática de capacidade, qualidade adaptativa por FPS e uma versão completa sem 3D. Toda decisão e todo número existem em HTML acessível.

**3. Como ganhar dinheiro sem virar mais um vendedor de leads?**
Priorizando receitas atreladas a resultado: assinatura de monitoramento e otimização (valor contínuo), comissão sobre a Arena (só se o projeto fecha), garantia de geração (só paga quem entrega), e serviços B2B. Instaladores pagam para competir, nunca para ranquear melhor.

**4. O HELIO é distribuidora, comercializadora ou instalador?**
Não. É a camada de **inteligência, transparência e experiência**. Contratos de compensação seguem as regras da distribuidora e da ANEEL; instalação é feita por parceiros verificados; energia compartilhada em escala usa parceiros regulados.

**5. Por que não usar o app do fabricante do inversor?**
Apps de fabricante só existem **depois** da compra, falam apenas de uma marca e mostram números sem contexto. O HELIO é agnóstico de marca, acompanha antes e depois, explica o "porquê" e **age** (Piloto Automático).

**6. A estimativa de telhado será imprecisa?**
Toda estimativa vem com faixa de incerteza e a pessoa pode melhorar a precisão com a Captura Guiada (escaneamento pelo celular). A calibração usa dados reais de geração, e a taxa de erro é publicada.

**7. IA em tudo não vai custar uma fortuna e inventar números?**
Números **nunca** vêm do modelo de linguagem: vêm de ferramentas determinísticas (`energy-core`). A IA explica, compara e conversa. Há orçamento de custo por usuário, cache, roteamento de modelos e avaliações contínuas.

**8. O que torna o HELIO difícil de copiar?**
Os ativos que se acumulam com o tempo: o maior conjunto aberto de **geração real vs prevista** do país, a rede de instaladores com reputação verificada por performance, a engine de cenas persistente (Palco), a comunidade (efeito de rede entre vizinhos) e a marca da honestidade.

## 1.3 O problema (seis falhas estruturais)

| # | Falha | Como se manifesta | Quem sofre |
|---|---|---|---|
| 1 | **Assimetria de informação** | Propostas inflacionadas, premissas escondidas, sem forma justa de comparar | Todo comprador |
| 2 | **Invisibilidade** | O comprador não *enxerga* o que está comprando nem como o telhado se comporta no ano | Proprietários |
| 3 | **Pós-venda cego** | Falhas passam semanas sem detecção; ninguém sabe se está gerando o esperado | Donos de sistemas |
| 4 | **Burocracia opaca** | Vistoria, parecer de acesso, troca de medidor e ativação sem previsibilidade | Quem está instalando |
| 5 | **Desperdício de valor** | O consumo (chuveiro às 19h, ar-condicionado à noite) briga com a geração (10h–15h) | Quem já tem solar |
| 6 | **Exclusão** | Inquilinos, apartamentos e telhados ruins ficam fora | Milhões de pessoas |

## 1.4 O insight central

> O sol é previsível. A conta é previsível. A casa é programável. O que falta é uma **camada de inteligência e confiança** entre os três.

Essa camada precisa ser **vista** (para a pessoa entender), **verificável** (para a pessoa confiar) e **ativa** (para a pessoa economizar mais). Esses três verbos definem o produto.

## 1.5 Por que agora

| Driver | O que mudou |
|---|---|
| **WebGPU em todo lugar** | Chrome, Firefox e Safari (iOS/macOS 26) suportam WebGPU; computação de GPU no navegador permite simular insolação anual em segundos |
| **Ecossistema TanStack maduro** | Router, Query, Table, Form e Virtual estáveis; Start em Release Candidate; Table v9 anunciada como estável em ago/2026 *(estado a reconfirmar no spike)* |
| **IA multimodal com tool use** | Extrair faturas e propostas de PDF/foto e conversar com ferramentas tipadas deixou de ser pesquisa e virou engenharia |
| **Marco legal da GD** | A Lei 14.300/2022 gerou dúvida e demanda por clareza sobre Fio B, compensação e geração compartilhada |
| **Casa programável barata** | Tomadas, relés e carregadores inteligentes (Matter, Tuya, Shelly, OCPP) estão ao alcance de qualquer bolso |
| **Imagens de satélite abertas** | Dados de nuvens em alta cadência permitem *nowcasting* de geração por telhado |
| **Base instalada enorme e mal servida** | Milhões de sistemas já instalados sem monitoramento decente |
| **WhatsApp e Pix universais** | Canais conhecidos por todos, inclusive quem não instala apps |

## 1.6 Alternativas e posicionamento

| Alternativa | O que faz bem | Onde falha | Como o HELIO vence |
|---|---|---|---|
| Integrador tradicional | Conhece instalação | Proposta opaca, visita demorada, sem comparação | Auditoria + Arena + Proposta Viva |
| Marketplace de leads | Volume | Incentivo errado (vende lead, não verdade) | Ranking por performance verificada, sem pay-to-rank |
| Simuladores genéricos | Rápidos | Rasos, sem telhado real, sem pós-venda | Gêmeo Solar e ciclo completo |
| App do fabricante | Telemetria | Uma marca, sem contexto, sem ação | Agnóstico, explicativo, Piloto Automático |
| Distribuidoras | Dados oficiais | Experiência burocrática | Rastreio de homologação transparente |
| Planilhas e YouTube | Grátis | Exigem expertise e tempo | Experiência guiada e confiável |

## 1.7 Vantagens competitivas acumuláveis (moats)

1. **Dataset de performance:** pares (previsão × geração real) por telhado, clima e equipamento. Melhora o modelo, o ranking e a Garantia.
2. **Reputação verificada por dados:** instaladores avaliados pelo que *entregaram*, não pelo que disseram.
3. **Efeito de rede local:** Vila Solar e Mutirão tornam cada novo vizinho mais valioso.
4. **Engine de cenas (Palco):** investimento técnico em experiência que é caro de replicar bem.
5. **Marca da honestidade:** consequência de publicar o próprio erro.
6. **Integrações e adaptadores:** rede de conectores de inversores e casa inteligente.

## 1.8 Visão, missão e princípios

**Visão:** ser o lugar onde todo brasileiro entende, decide e vive melhor com energia solar.
**Missão:** transformar luz em certeza, e certeza em economia.

### Dez princípios (com o teste prático de cada um)

| # | Princípio | Na prática | Teste |
|---|---|---|---|
| 1 | **Mostrar, não explicar** | Todo conceito vira algo que se manipula | "Dá para mexer nisso em vez de ler?" |
| 2 | **Honestidade verificável** | Faixa, premissa e fonte em todo número; erro do modelo é público | "O usuário consegue conferir de onde veio?" |
| 3 | **Beleza com propósito** | Efeito só existe se comunicar dado ou emoção | **Teste do Porquê:** "O que o usuário perde se tirarmos isso?" |
| 4 | **Orçamento de Uau** | No máximo **um** efeito-herói por viewport | "Há dois efeitos competindo pela atenção?" |
| 5 | **Rápido primeiro, espetacular depois** | HTML e conteúdo em SSR; 3D chega progressivamente | "O CTA funciona antes de o 3D carregar?" |
| 6 | **Paridade sensorial** | Todo visual tem equivalente textual, sonoro e tátil | "Alguém sem ver a tela entende o mesmo?" |
| 7 | **Agir, não só informar** | Sempre que possível, o produto executa a economia | "Isso poupa tempo ou dinheiro sem esforço?" |
| 8 | **Respeito ao tempo** | Cada fluxo tem meta de tempo e cortes de atrito | "Dá para fazer em menos passos?" |
| 9 | **Os dados são do usuário** | Exportar, apagar, auditar acessos, nunca vender | "Dá para ir embora levando tudo?" |
| 10 | **Humor sem deboche** | Voz amiga, humana, às vezes divertida, nunca infantil nem alarmista | "Um engenheiro simpático diria isso?" |

### Anti-princípios (o que o HELIO se recusa a ser)
- Um site "genérico bonito": vidro fosco em fundo roxo com ilustração de banco de imagens.
- Parallax e partículas "porque sim".
- Um marketplace que vende posição.
- Um painel de 40 gráficos que ninguém entende.
- Um chatbot que inventa número.
- Uma experiência que só funciona em notebook potente.

---

# PARTE 2 — O PRODUTO

## 2.1 Personas e trabalhos a serem feitos (JTBD)

| Persona | Quem é | *Job to be done* | Momento de verdade | Canal e modo preferidos |
|---|---|---|---|---|
| **Marina, 34, a Cautelosa** | Proprietária de casa, conta de R$ 480/mês, já recebeu duas propostas | "Quando eu receber uma proposta, quero saber se posso confiar, para não ser enganada." | Ver a proposta dela auditada, com o telhado em 3D | Web mobile; modo Noite/Dia |
| **Seu Antônio, 61, o Dono Desligado** | Instalou há 2 anos; só descobre problema na conta | "Quando algo estiver errado com meu sistema, quero ser avisado de forma simples, sem aprender nada novo." | Mensagem no WhatsApp: "Tá tudo certo hoje ☀️" | **WhatsApp** + **Modo Simples** |
| **Condomínio Jardim das Acácias** | Síndico e 80 unidades | "Quando eu levar uma proposta à assembleia, quero números claros e rateio justo." | Relatório de assembleia com simulação de rateio | Web desktop; Console para o síndico |
| **Rafa, 27, a Inquilina** | Mora de aluguel em apartamento | "Quando minha conta chegar, quero pagar menos mesmo sem ter telhado." | Ver a cota solar reduzir a conta | Web mobile; app instalado (PWA) |
| **Solis, o Integrador** | Empresa de 12 pessoas | "Quando surgir um lead, quero responder rápido com uma proposta profissional e crível, sem perder horas." | Proposta enviada em 15 min com 3D embutido | Web desktop; modo Oficina |
| **Dani, 41, a Dona de Padaria** | Consumo diurno alto | "Quando eu investir, quero saber o retorno e a melhor linha de crédito." | Gráfico mostrando o mês em que a economia supera a parcela | Web; Terminal |
| **Beto, 38, o Entusiasta** | Tem Home Assistant, carro elétrico, planilhas | "Quero extrair o máximo do meu sistema e integrar com tudo." | Piloto Automático com regras próprias e API | Web desktop; Console |

## 2.2 Os cinco atos

| Ato | Pergunta do usuário | Experiência-herói | Resultado |
|---|---|---|---|
| **1. Descobrir** | "Isso serve pra mim?" | **Simulador Gêmeo** | Entender o potencial do próprio telhado em 90 segundos |
| **2. Decidir** | "Em quem e em quê confiar?" | **Auditoria de Proposta** e **Arena de Lances** | Escolher com segurança, pelo melhor preço justo |
| **3. Instalar** | "O que está acontecendo com a minha obra?" | **Rastreio de Obra** e **O Primeiro Raio** | Previsibilidade da burocracia e celebração da ativação |
| **4. Viver** | "Estou economizando? Dá para economizar mais?" | **Cúpula** e **Piloto Automático** | Certeza diária e economia crescente |
| **5. Compartilhar** | "Como isso ajuda quem está perto de mim?" | **Vila Solar** e **Seu Ano Solar** | Efeito de rede, inclusão e orgulho |

## 2.3 Mapa de Mundos × Atos

Cada área do produto é um **Mundo**: uma direção de arte e uma técnica de renderização próprias, unidas por uma gramática comum (Parte 3).

| Mundo | Natureza | Atos onde aparece |
|---|---|---|
| **Alvorada** | Cinema, céu volumétrico, scroll como câmera | Descobrir |
| **Ateliê** | Arquitetura da luz, planta técnica de luxo | Descobrir, Decidir |
| **Biblioteca** | Editorial, papel, tinta, explicadores | Descobrir |
| **Terminal** | Densidade financeira, mono, ticker | Decidir |
| **Arena** | Disputa transparente, placar ao vivo | Decidir |
| **Cúpula** | Diorama vivo da casa, clima real | Viver |
| **Orbe** | Assistente como luz viva | Viver |
| **Aurora** | Noite, fitas de luz entre casas | Compartilhar |
| **Floresta** | Natureza pintada, impacto | Compartilhar |
| **Atlas** | Cartografia e arte de dados | Descobrir, Compartilhar (público) |
| **Oficina** | Ferramenta profissional (instalador e admin) | Transversal (B2B) |

## 2.4 Catálogo de funcionalidades

**Legenda:** Prioridade P0 (essencial), P1 (importante), P2 (desejável). Release: **R1 Nascer**, **R2 Zênite**, **R3 Crepúsculo**, **R4 Aurora** (detalhes em 7.5).

### Ato 1 — Descobrir
| ID | Funcionalidade | Descrição | Rel. | Prio |
|---|---|---|---|---|
| F-101 | **Landing cinematográfica** | Narrativa em scroll, sol 3D, endereço como CTA | R1 | P0 |
| F-102 | **Simulador Gêmeo** | Endereço → telhado 3D → sol/sombra → consumo → resultado | R1 | P0 |
| F-103 | **Conta Raio-X** | Fatura (PDF/foto) explicada linha a linha, com "conta com solar" | R1 | P0 |
| F-104 | **Atlas Solar** | Mapa público de potencial e geração real, com página para cada município | R1 (base) / R2 | P1 |
| F-105 | **Captura Guiada** | Escaneamento do telhado pelo celular (LiDAR/fotogrametria) para precisão | R3 | P2 |
| F-106 | **Biblioteca (Aprender)** | Artigos com explicadores interativos | R1 | P0 |
| F-107 | **Widget "Quanto rende a minha rua?"** | Calculadora embutível em sites parceiros e imprensa | R2 | P1 |

### Ato 2 — Decidir
| ID | Funcionalidade | Descrição | Rel. | Prio |
|---|---|---|---|---|
| F-201 | **Auditoria de Proposta** | Upload da proposta recebida; extração, comparação com o modelo e relatório de coerência | R1 | P0 |
| F-202 | **Brief Único** | Descrever o projeto uma vez, em formato padronizado, para todos os instaladores | R2 | P1 |
| F-203 | **Arena de Lances** | Instaladores verificados dão lances cegos e padronizados em até 72 h | R2 beta / R3 | P1 |
| F-204 | **Proposta Viva** | Proposta interativa com 3D, premissas obrigatórias e promessa rastreável | R2 | P1 |
| F-205 | **Terminal de Financiamento** | Fluxo de caixa, CET e comparação de linhas | R2 | P1 |
| F-206 | **Garantia de Geração** | Cobertura contratual (com instalador e seguradora) se a geração ficar abaixo do P90 prometido | R3 | P2 |
| F-207 | **Perfil verificado do instalador** | Performance real (previsto × gerado) de projetos concluídos | R1 (básico) | P0 |
| F-208 | **Mutirão** | Compra coletiva de bairro com desconto por volume | R3 | P1 |
| F-209 | **Revisão técnica humana** | Engenheiro do HELIO revisa um projeto sob demanda (serviço pago) | R2 | P2 |

### Ato 3 — Instalar
| ID | Funcionalidade | Descrição | Rel. | Prio |
|---|---|---|---|---|
| F-301 | **Rastreio de Obra e Homologação** | Etapas (vistoria, projeto, parecer de acesso, instalação, troca de medidor, ativação) com prazos e avisos | R2 | P1 |
| F-302 | **Cofre de Documentos** | Contratos, ART, notas, laudos, garantias, com busca e validade | R2 | P1 |
| F-303 | **O Primeiro Raio** | Celebração da primeira geração, com cartão compartilhável | R2 | P1 |
| F-304 | **Vistoria remota** | Fotos e vídeo guiados com validação por visão computacional | R3 | P2 |

### Ato 4 — Viver
| ID | Funcionalidade | Descrição | Rel. | Prio |
|---|---|---|---|---|
| F-401 | **Cúpula** | Gêmeo vivo da casa: sol, nuvens, produção, consumo | R2 | P0 |
| F-402 | **Previsão de geração** | Próximas horas e dias, com *nowcasting* por satélite | R2 | P0 |
| F-403 | **Saúde do sistema** | Nota explicável, detecção de anomalias, alertas | R2 | P0 |
| F-404 | **Piloto Automático Solar** | Move cargas flexíveis para as horas de sol, com regras e limites do usuário | R2 básico / R3 completo | P0 |
| F-405 | **Fatura Prevista** | Estimativa da próxima fatura com antecedência e decomposição | R2 | P1 |
| F-406 | **Otimizador de Créditos** | Gestão de créditos por UC, vencimentos e redistribuição | R2 | P1 |
| F-407 | **Manutenção Preditiva** | "Vale limpar?" com custo × recuperação estimada | R3 | P1 |
| F-408 | **Copiloto Hélio** | Texto, voz e UI generativa, com ferramentas tipadas | R2 | P0 |
| F-409 | **Boletim do Sol** | Resumo diário em WhatsApp, push e áudio de 20 s | R2 | P0 |
| F-410 | **Modo Simples** | Interface de 3 informações, grande e calma | R2 | P0 |
| F-411 | **Sol de Parede** | Modo ambiente para tablet/TV antigos | R2 | P1 |
| F-412 | **Widgets e Live Activities** | Tela de bloqueio, widgets, relógio | R3 | P2 |
| F-413 | **Passaporte do Sistema** | Histórico verificável e transferível, que valoriza o imóvel na revenda | R3 | P1 |
| F-414 | **Zoom Cósmico** | Pinça do telhado à rede nacional e ao Sol | R2 | P1 |

### Ato 5 — Compartilhar
| ID | Funcionalidade | Descrição | Rel. | Prio |
|---|---|---|---|---|
| F-501 | **Vila Solar** | Rede de vizinhos que compartilham créditos, com visualização em Aurora | R3 | P1 |
| F-502 | **Cotas solares** | Acesso para inquilinos e apartamentos via parceiros regulados | R3/R4 | P2 |
| F-503 | **Condomínio Solar** | Gestão de usina compartilhada, rateio e votações | R3 | P1 |
| F-504 | **Seu Ano Solar** | Retrospectiva anual cinematográfica e compartilhável | R3 | P1 |
| F-505 | **Floresta e Conquistas** | Impacto visualizado, metas e conquistas | R3 | P2 |
| F-506 | **Indicação transparente** | Recompensas claras por indicação, sem multinível | R2 | P1 |
| F-507 | **Relatório de assembleia** | PDF e link público de leitura | R3 | P1 |

### Transversais
| ID | Funcionalidade | Rel. | Prio |
|---|---|---|---|
| F-601 | **Palco Persistente** (cena 3D contínua entre rotas) | R1 | P0 |
| F-602 | **Central de Privacidade** (exportar, apagar, auditar acessos) | R1 | P0 |
| F-603 | **Command Bar** com linguagem natural (Ctrl/Cmd+K) | R1 | P1 |
| F-604 | **Modos de experiência** (Noite, Dia, Simples, Calmo, Contraste, Console) | R1 | P0 |
| F-605 | **Promessa vs Realidade** (página pública de precisão) | R2 | P0 |
| F-606 | **Autenticação** (passkeys, magic link, social, MFA) | R1 | P0 |
| F-607 | **Portal do Instalador** (leads, Arena, editor 3D, propostas, reputação) | R2 | P1 |
| F-608 | **Admin e operação** | R1 | P1 |
| F-609 | **Orquestrador de notificações** (push, e-mail, WhatsApp, quiet hours inteligentes) | R2 | P1 |
| F-610 | **Internacionalização** (en, es) | R4 | P2 |

## 2.5 Momentos da verdade por ato

| Ato | Momento | Emoção-alvo | Como medimos |
|---|---|---|---|
| Descobrir | O telhado aparece em 3D e o sol começa a andar | Encantamento e confiança | Conclusão do simulador; tempo até o 1º "uau" (interação com o sol) |
| Decidir | O relatório da Auditoria diz "prometeram 22% a mais" | Alívio e poder | Compartilhamento do relatório; conversão para Arena |
| Instalar | A etapa "troca de medidor" muda para concluída | Previsibilidade | Contatos de suporte por projeto; NPS da obra |
| Viver | A primeira nuvem cruza o telhado e a curva reage | Fascínio e vínculo | Retorno em 7 e 30 dias; abertura do Boletim |
| Viver | O Piloto Automático economiza R$ 63 no mês | Satisfação concreta | % usuários com Piloto ativo; R$ economizados |
| Compartilhar | O Ano Solar aparece com a música do seu sol | Orgulho | Compartilhamentos; novos usuários por indicação |

---

# PARTE 3 — SISTEMA DE DESIGN "FOTÔNICA"

## 3.1 Conceito: a luz como matéria

O HELIO não *tem* tema; ele *tem* luz. O sistema se organiza em três camadas que se influenciam:

| Camada | O que é | Quem controla |
|---|---|---|
| **Luz** | Sol real do local e da hora, mais cobertura de nuvens | **Motor de Luz Global** (3.2) |
| **Matéria** | Superfícies e materiais que reagem à luz | Tokens, shaders e CSS (3.5) |
| **Movimento** | Física, ritmo e coreografia | Motion tokens e físicas (3.7) |

**Frase-guia para designers:** *"Se o sol estiver se pondo, a interface deveria parecer que o sol está se pondo."*

## 3.2 Motor de Luz Global (*Sun Engine*)

**Entradas:** latitude/longitude (aproximada, opt-in; sem permissão usa a região), data e hora, cobertura de nuvens (previsão ou nowcasting), preferência do usuário (Noite/Dia/Automático).

**Saídas** (variáveis CSS e uniforms de shader, atualizadas a 1 Hz; 60 Hz apenas enquanto o usuário arrasta o tempo):

| Variável | Significado |
|---|---|
| `--sun-e` | Elevação normalizada (0 = abaixo do horizonte, 1 = zênite) |
| `--sun-az` | Azimute em graus |
| `--sun-warmth` | Temperatura de cor (0 = azul frio, 1 = âmbar quente) |
| `--cloud` | Cobertura de nuvens (0–1) |
| `--sky-top`, `--sky-horizon` | Gradiente de céu derivado |
| `--ambient` | Luz ambiente (influencia contraste de superfícies) |
| `--shadow-angle`, `--shadow-len` | Direção e comprimento de sombras de elementos flutuantes |
| `--glow` | Intensidade do halo em CTAs e números-chave |

**Fases do dia (paleta e atmosfera):**

| Fase | Sol | Atmosfera |
|---|---|---|
| Noite | < −12° | Índigo profundo, estrelas esparsas, brilho de aurora |
| Hora azul | −12° a −2° | Azul-petróleo, horizonte magenta |
| Nascer | −2° a 8° | Âmbar e rosa, sombras longas, névoa dourada |
| Manhã | 8° a 35° | Branco-quente, azul limpo |
| Meio-dia | > 35° | Azul nítido, sombras curtas, alto contraste |
| Tarde | 35° a 8° | Dourado crescente |
| Pôr do sol | 8° a −2° | Laranja-coral, raios crepusculares |
| Crepúsculo | −2° a −12° | Violeta, retorno ao índigo |

**Garantias não negociáveis:**
1. **Contraste:** o texto sempre tem ≥ 4,5:1 (≥ 3:1 para texto grande e elementos de interface), independente da fase. Um *scrim* adaptativo ajusta opacidade e luminância por camada.
2. **Estabilidade:** transições de fase duram minutos, nunca saltam; nada pisca.
3. **Controle:** o usuário pode fixar Noite, Dia ou "Luz estática" (sem variação ao longo do dia).
4. **Custo:** o motor não pode causar *layout* nem *repaint* global; usa apenas variáveis com `@property` aplicadas a propriedades baratas (cor, opacidade, transform).

## 3.3 Cor

Tudo em `oklch()` (percepção uniforme), com `color-mix()` e `light-dark()`.

| Família | Papel | Valor-âncora (oklch) |
|---|---|---|
| **Sol** | Marca, energia, CTAs primários | `0.82 0.17 75` (âmbar-ouro) |
| **Silício** | Estrutura, UI base escura | `0.20 0.04 265` |
| **Aurora** | Sucesso, economia, "bom" | `0.86 0.18 165` (verde-menta elétrico) |
| **Brasa** | Alerta, atenção | `0.72 0.18 35` (coral) |
| **Papel** | Biblioteca e documentos | `0.96 0.015 85` |
| **Carbono** | Texto e neutros | escala de 12 passos |

**Paletas de dados (todas testadas para daltonismo):**
- **Sequencial "Insolação":** índigo → magenta → âmbar → branco-quente (mapas de calor, sombra, geração).
- **Divergente "Esperado":** coral (abaixo) ← neutro → menta (acima).
- **Categórica:** 8 matizes distintos em luminância e matiz, com redundância por forma/padrão.

**Regra:** cor nunca é o único portador de significado; sempre há ícone, padrão, texto ou posição.

## 3.4 Tipografia

| Papel | Família (open-source) | Uso |
|---|---|---|
| **Display emocional** | *Instrument Serif* (itálico para ênfase) | Manchetes, números-herói, Wrapped |
| **UI e texto** | *Geist* (ou *Inter Tight*) variável | Interface, navegação, formulários |
| **Números e dados** | *Geist Mono* | Valores, tabelas, Terminal, código |
| **Editorial** | *Newsreader* (ou *Source Serif 4*) com eixo óptico | Biblioteca |

**Regras:**
- Escala fluida com `clamp()` entre 14 px (mobile) e 20 px (desktop) na base; escala modular 1,25.
- Números sempre tabulares (`font-variant-numeric: tabular-nums`), vírgula decimal brasileira (`1.234,56`), unidades em cinza com espaço fino (`18,2 kWh`).
- **Tipografia viva:** eixos variáveis (`wght`, `opsz`, `wdth`) respondem a contexto: números-chave engordam levemente com a geração do momento; manchetes afinam no scroll. Sempre sutil, sempre desligável por "Modo Calmo".
- Fontes locais (*self-hosted*) com `font-display: swap`, subsetting para latim estendido e pré-carregamento só do corte crítico.

## 3.5 Matéria (materiais)

| Material | Onde | Como se faz | Fallback |
|---|---|---|---|
| **Vidro Solar** | Painéis de Cúpula, Orbe, Alvorada | `backdrop-filter` + borda especular em gradiente cônico + refração por shader opcional | Cor sólida translúcida |
| **Silício** | Base escura do app | Preto-azulado com padrão sutil de célula solar (grade com chanfro), brilho dependente do `--sun-az` | Cor sólida |
| **Papel** | Biblioteca | Grão procedural, fibras, sombra de dobra; tinta com leve *misregistration* nos títulos (estética de risografia) | Cor sólida + textura PNG leve |
| **Metal escovado** | Oficina, Console | Realce anisotrópico controlado por ponteiro | Gradiente linear |
| **Névoa** | Alvorada, Aurora | Gradientes volumétricos em camadas com ruído animado | Gradiente estático |
| **Terminal** | Terminal, Arena | Grade tipográfica nítida, ticker, realce de varredura sutil | Mesmo layout, sem varredura |

## 3.6 Forma, grade e densidade

- **Motivo "célula solar":** cantos chanfrados (um canto cortado a 45°) em cartões-chave e botões primários; implementado com `clip-path` e, onde houver suporte, `corner-shape`. Raios arredondados para o restante.
- **Grade:** 12 colunas com *container queries*; blocos se reorganizam por largura do **contêiner**, não da tela.
- **Espaçamento:** base 4 px; escala 4/8/12/16/24/32/48/72/112.
- **Densidade:** **Conforto** (padrão), **Compacto**, **Console** (instalador/admin, alta densidade) e **Simples** (poucos itens, alvos de 56 px).
- **Elevação:** 5 níveis combinando sombra projetada na direção do sol (`--shadow-angle`), desfoque e borda especular.

## 3.7 Movimento

**Princípios:** movimento explica (causa → efeito), é físico (inércia, não curvas arbitrárias) e é econômico (um protagonista por vez).

| Token | Natureza | Parâmetros-guia | Uso |
|---|---|---|---|
| `snap` | Rígido e direto | rigidez 520, amortecimento 38 | Botões, toggles |
| `glide` | Suave | rigidez 260, amortecimento 30 | Painéis, trocas de estado |
| `float` | Flutuante | rigidez 120, amortecimento 20 | Elementos de Cúpula, orbes |
| `heavy` | Peso e importância | rigidez 180, amortecimento 28, massa 2 | Revelar resultados-chave |
| `narrative` | Roteirizado (linha do tempo) | 1,2 a 3 s, curvas custom | Landing, Wrapped |

**Durações:** micro 120 ms · UI 220 ms · cena 600 ms · narrativa 1,2 s+.

**Mecanismos por ordem de preferência:**
1. **CSS nativo** (`animation-timeline: scroll()/view()`, `@starting-style`, transições discretas).
2. **View Transitions** (mesmo documento e entre documentos) com *shared elements*.
3. **Motion** (springs) para interação direta.
4. **GSAP + ScrollTrigger** apenas para cenas roteirizadas complexas.
5. **Shader/GPU** para tudo o que for massa de partículas ou luz.

**Respiro:** quando ocioso, a interface "respira" (pulso de luz de ~0,1 Hz). Nunca chama atenção, apenas diz "está vivo".

**Mapa de redução de movimento (`prefers-reduced-motion` e Modo Calmo):**
parallax → estático; partículas → pontos fixos; sol percorrendo → troca por fade entre estados; números morphing → troca direta; sons e háptica mantêm-se conforme escolha do usuário.

## 3.8 Som

Opt-in, desligado por padrão, com convite elegante ("Quer ouvir seu sol?").

- **Identidade:** harmônica de vidro, pad suave e marimba. Sem jingles; só texturas e harmonia.
- **Sonificação:** a geração atual controla a harmonia do pad (mais potência = mais camadas e brilho); o pôr do sol muda gradualmente a tonalidade para modo menor suave.
- **Sons de interface (12):** toque, confirmar, erro gentil, notificação, alternar, arrastar sol (glissando contínuo), alcançar meta, primeiro raio, alerta, abrir cúpula, fechar cúpula, compartilhar.
- **Regras:** *ducking* automático sob voz do Copiloto; volume independente; respeita silêncio do sistema; toda informação sonora tem equivalente visual e textual.
- **Técnica:** Web Audio API com nós sintetizados e amostras curtas (< 150 KB no total), carregadas sob demanda.

## 3.9 Háptica
Padrões curtos e reconhecíveis (confirmar, erro, "nascer do sol" crescente, meta atingida) quando a plataforma oferece suporte; jamais obrigatória.

## 3.10 Gramática de visualização de dados

1. **Toda estimativa mostra incerteza** (`ConfidenceBand`) e premissas a um toque.
2. **Visuais-assinatura**, cada um com semântica própria:
   - **Relevo:** séries longas como paisagem (25 anos de economia).
   - **Rio:** fluxos de energia entre fontes e destinos.
   - **Relógio Solar:** dia circular, com sol, geração esperada e real.
   - **Calendário de calor:** 365 dias.
   - **Cascata:** composição de economia ou de fatura.
   - **Reservatório:** créditos e baterias.
   - **Constelação:** redes de vizinhos.
3. **Anotações inteligentes:** o gráfico destaca o que importa ("dia mais nublado do mês") em linguagem natural.
4. **Tabela equivalente e resumo textual** em todo gráfico.
5. **Formatos brasileiros:** `R$ 1.234,56`, `kWh`, datas `dd/mm/aaaa`, fuso e horário de verão quando houver.

## 3.11 Iconografia, 3D e personagem

- **Ícones:** traço de 1,5 px, chanfro característico, ~200 ícones próprios; animações nos de estado (sol que nasce, nuvem que passa).
- **Estilo 3D:** realismo estilizado, materiais PBR simples, mapeamento tonal cinematográfico suave, geometria legível e limpa. Maquetes de casas generalizadas por tipologia + telhado real.
- **Hélio, o Orbe:** o assistente não tem rosto, tem **luz**. Estados controlados por shader: *ocioso* (respira), *ouvindo* (ondula na voz), *pensando* (órbitas), *alegre* (halo expande), *alerta* (coral, pulso curto), *calmo* (noite). Nunca antropomórfico demais.

## 3.12 Voz e microcopy

**Personalidade:** o amigo engenheiro: competente, caloroso, bem-humorado, honesto até quando dói.

| Situação | Não | Sim |
|---|---|---|
| Geração baixa | "ALERTA! Queda de desempenho!" | "O sol deu uma folga depois das 15h. Mesmo assim você chegou a 84% da meta. 🌤️" |
| Erro de upload | "Erro 422" | "Não consegui ler essa foto. Tenta com mais luz? Ou me manda o PDF." |
| Estado vazio | "Nenhum dado" | "Seu telhado ainda não me contou nada. Assim que o inversor se conectar, eu começo a anotar." |
| Estimativa | "Você economizará R$ 350" | "Entre R$ 310 e R$ 390 por mês. O meio do caminho é R$ 350." |
| Urgência | "Últimas vagas!" | (Nunca. Sem escassez artificial.) |

**Regras:** frases curtas; verbos de ação; explicar o "porquê" antes do "o quê"; unidades sempre; humor leve, nunca sobre dinheiro perdido, saúde ou falhas graves; nunca medo como alavanca; acessível (nível de leitura ~8º ano).

## 3.13 Modos de experiência

| Modo | Para quem | O que muda |
|---|---|---|
| **Noite** (padrão) | Maioria | Silício escuro, luz do sol como protagonista |
| **Dia** | Ambiente claro, preferência | Papel/quente, sombras reais, contraste preservado |
| **Simples** | 60+, baixa familiaridade digital | 3 informações, fonte grande, ícones claros, alvos 56 px, sem animação ornamental |
| **Calmo** | Sensibilidade a movimento, foco | Sem movimento contínuo, saturação reduzida, sem partículas |
| **Alto contraste** | Baixa visão | Contraste ≥ 7:1, bordas fortes, sem transparência |
| **Console** | Instalador, admin, entusiasta | Densidade máxima, teclado em primeiro lugar |

## 3.14 Orçamento de Uau e Barra de Qualidade Visual

**Orçamento de Uau:** por viewport, **um** efeito-herói. Efeitos secundários só existem se estiverem em repouso ou dependentes de interação.

**Barra de Qualidade (revisão obrigatória de design antes de qualquer lançamento):**

1. Passa no **Teste do Porquê** (cada efeito tem função).
2. Existe **um** efeito-herói por viewport.
3. Contraste ≥ 4,5:1 em **todas** as fases do dia.
4. Versão sem animação, sem 3D e sem som é **completa**.
5. 60 fps em Tier 2; qualidade adaptativa funciona.
6. Estados cobertos: carregando, vazio, erro, offline, permissão, parcial.
7. Texto equivalente de cada gráfico e cena.
8. Sem *layout shift* na transição 2D → 3D.
9. Microcopy revisada pela voz.
10. Funciona em tela de 360 px e em 4K.
11. Teclado completo, foco visível, ordem lógica.
12. Rodou no dispositivo de referência mais modesto.

## 3.15 Biblioteca de componentes (inventário)

| Grupo | Componentes |
|---|---|
| **Fundamentos** | Botão, Campo, Seletor, Switch, Slider físico, Tabs, Popover (anchor positioning), Dialog (popover API), Toast, Tooltip, Skeleton, Avatar |
| **Dados** | `ConfidenceBand`, `NumberMorph`, `SunDial`, `HeatCalendar`, `Waterfall`, `Reservoir`, `Sparkline`, `EnergyRiver`, `Constellation`, `TimeScrubber` |
| **Cenas** | `Stage` (palco persistente), `Dome` (Cúpula), `RoofScene`, `SkyDome`, `Forest`, `Orb`, `GlobeAtlas`, `ZoomCosmic` |
| **Interação** | `CommandBar`, `GestureLayer`, `Sheet` (bottom sheet), `Stepper cinematográfico`, `DragDropKanban`, `LayoutEditor3D` |
| **Conteúdo** | `Explainer` (MDX interativo), `Glossary`, `ShareCard`, `WrappedStory`, `ProofBadge` (selo com proveniência) |
| **Transversais** | `ModeSwitch`, `MotionBudget`, `AuditMode` (mostra fórmulas), `SoundToggle` |

## 3.16 Tokens em código (exemplo)

```css
/* tokens/light-engine.css — camada de luz */
@property --sun-e      { syntax: "<number>"; inherits: true; initial-value: 0.4; }
@property --sun-warmth { syntax: "<number>"; inherits: true; initial-value: 0.5; }
@property --cloud      { syntax: "<number>"; inherits: true; initial-value: 0; }

:root {
  /* matiz do céu: 255 (azul) → 55 (âmbar) conforme o calor da luz */
  --sky-hue:     calc(255 - var(--sun-warmth) * 200);
  --sky-top:     oklch(calc(0.16 + var(--sun-e) * 0.50) 0.08 var(--sky-hue));
  --sky-horizon: oklch(calc(0.30 + var(--sun-e) * 0.45) 0.12 calc(var(--sky-hue) - 20));
  --glow:        calc(0.25 + var(--sun-e) * 0.6 - var(--cloud) * 0.3);

  --surface:     color-mix(in oklch, oklch(0.20 0.04 265) 82%, var(--sky-top));
  --text:        light-dark(oklch(0.25 0.02 265), oklch(0.96 0.01 85));
  --accent-sun:  oklch(0.82 0.17 75);
  --accent-go:   oklch(0.86 0.18 165);
}

/* transições suaves entre fases sem tocar em layout */
body { transition: --sun-e 60s linear, --sun-warmth 60s linear; }

/* Modo Calmo / reduced motion */
@media (prefers-reduced-motion: reduce) {
  :root { --glow: 0.3; }
  .particles, .parallax { display: none; }
}
```

```ts
// sun-engine.ts — saídas do motor (simplificado)
export function applySun(root: HTMLElement, s: SunState) {
  root.style.setProperty('--sun-e',      String(s.elevationNorm));
  root.style.setProperty('--sun-warmth', String(s.warmth));
  root.style.setProperty('--cloud',      String(s.cloudCover));
}
```

---

# PARTE 4 — OS MUNDOS E AS TELAS

> **Como ler cada tela:** *Papel* (por que existe) · *Conteúdo e layout* · *Interações* · *Momento Uau* (referência ao catálogo em 4.12) · *Tecnologia* · *Estados e acessibilidade* · *Métrica.* Estados mínimos em toda tela: carregando (esqueleto coerente com o Mundo), vazio, erro com recuperação, offline, permissão negada e dado parcial.

## 4.0 Mapa de rotas

```
PÚBLICO
/                          Landing (Alvorada)
/como-funciona   /para-instaladores   /planos
/simular                   Simulador Gêmeo  →  /simular/resultado/$id
/auditar                   Auditoria de Proposta  →  /auditar/$id
/conta-de-luz              Conta Raio-X        /captura  Captura Guiada
/aprender  /aprender/$slug  /aprender/glossario   (Biblioteca)
/financiamento             Terminal de Financiamento
/propostas/$id             Comparador          /p/$token  Proposta Viva
/instaladores  /instaladores/$slug             (Arena: vitrine)
/brief/$id     /arena/$id  /mutirao  /mutirao/$id
/atlas  /atlas/$uf/$municipio   /promessa-vs-realidade   /metodologia
/entrar  /cadastro  /onboarding
/passaporte/$id            Passaporte do Sistema (link compartilhável)
/ano-solar/$ano            Seu Ano Solar
/status  /privacidade  /termos  /api

ÁREA LOGADA (/app)
/app                       Cúpula (home)       /app/previsao
/app/piloto                Piloto Automático   /app/helio  Copiloto
/app/sistemas/$id          Sistema             /app/creditos  /app/fatura
/app/obra/$id              Rastreio de obra    /app/documentos
/app/impacto               Floresta            /app/configuracoes
/parede                    Sol de Parede (modo ambiente)
/vila/$id   /condominio/$id                    (Aurora)

PROFISSIONAL
/instalador/leads  /instalador/arena  /instalador/editor/$id
/instalador/propostas  /instalador/obras  /instalador/reputacao  /instalador/financeiro
/admin/*                   Operação interna
```

---

## 4.1 MUNDO ALVORADA — cinema e primeira impressão

**Intenção:** em 5 segundos fazer a pessoa sentir "isto é diferente" e dar o primeiro passo.
**Direção de arte:** cinema. Céu atmosférico com nuvens volumétricas, raios crepusculares, grão de filme discreto, lens flare anamórfico controlado, tipografia serif gigante, câmera em *dolly* guiada pelo scroll. Paleta inteira vem do Motor de Luz.
**Tecnologia do Mundo:** React Three Fiber com WebGPU/TSL (fallback WebGL2); espalhamento atmosférico (estilo Hosek-Wilkie/Hillaire); nuvens por *raymarch* em meia resolução com *upsample* temporal; raios de luz em espaço de tela; Lenis (scroll suave); GSAP ScrollTrigger para mapear scroll → hora do dia → câmera; vídeo AV1/H.264 com a mesma coreografia como fallback.

### 4.1.1 Landing — `/`
**Papel:** gerar fascínio e levar ao Simulador ou à Auditoria.

**Storyboard (a página é um dia inteiro que passa conforme se rola):**

| Scroll | Cena | O que acontece | Mensagem |
|---|---|---|---|
| 0–12% | **Nascer** | Tela escura; o sol sobe e a cidade acende | "Seu telhado já trabalha de graça. Falta você ver." + campo de endereço |
| 12–30% | **Seu telhado** | Câmera desce até uma maquete; é possível arrastar o sol | Contador "kWh por ano na sua região" |
| 30–48% | **A verdade** | Duas barras: "Prometido" × "Realizado" com **dados reais** da página Promessa vs Realidade | "Nós publicamos até quando erramos." |
| 48–62% | **O que a conta esconde** | A fatura se desmonta em camadas luminosas | "Você paga por mais coisas do que imagina." |
| 62–78% | **O sol trabalha por você** | Cargas da casa acendem uma a uma quando o sol passa pelo zênite | "Piloto Automático" |
| 78–90% | **Sua rua** | Câmera sobe e mostra casas conectadas por fitas de luz | "Vizinhos compartilhando sol." |
| 90–100% | **Pôr do sol** | Céu laranja; CTA final; FAQ honesto; rodapé com metodologia | "Comece pelo seu telhado. Leva 90 segundos." |

**Interações:** arrastar o sol altera a hora e a cor de toda a página (M-01); o campo de endereço faz o campo se transformar na cena do Simulador (transição compartilhada, M-02); passar o cursor em partículas revela "fótons" como kWh; botão "Pular a animação" sempre visível.
**Tecnologia:** o elemento de LCP é a **manchete + campo de endereço** (texto e HTML), nunca o canvas; a cena 3D carrega após *idle* e *prefetch por intenção*; orçamento de JS inicial ≤ 170 KB gzip, cena ≤ 600 KB adicionais (carregada tardiamente).
**Estados e acessibilidade:** Tier 0/1 recebem vídeo ou CSS; narrativa completa em texto semântico; pausa global de movimento; zero informação só no canvas.
**Métrica:** CTR do campo de endereço; envio de endereço; profundidade de scroll; distribuição por Tier; taxa de rejeição por Tier.

### 4.1.2 Como funciona — `/como-funciona`
Fluxo interativo de 3 minutos que percorre os cinco atos com mini-demos (arrastar o sol, ver uma Auditoria de exemplo, ver a Arena revelando lances). Termina em CTA duplo: "Simular meu telhado" e "Auditar uma proposta".

### 4.1.3 Para instaladores — `/para-instaladores`
Pitch com **calculadora honesta** ("quanto você economiza de tempo e quanto custa um lead que não fecha"), demonstração da Arena e do Editor 3D, selo de Performance Verificada, e as regras de ouro (não vendemos posição).

### 4.1.4 Planos — `/planos`
Planos do usuário (Gratuito, Plus) com **calculadora de retorno** ("o Plus se paga em X meses com o Piloto Automático, estimado para a sua casa"), sem escassez artificial e com cancelamento em um clique. Planos do instalador (Essencial, Pro) com custos de Arena e comissão por sucesso explicitados.

---

## 4.2 MUNDO ATELIÊ — arquitetura da luz

**Intenção:** converter curiosidade em compreensão profunda e precisa do próprio telhado.
**Direção de arte:** planta de arquiteto de luxo. Linhas finas, cotas, anotações manuscritas digitais, superfícies iluminadas pelo sol real. Em Noite: wireframe luminoso sobre silício. Em Dia: papel vegetal quente.
**Tecnologia do Mundo:** MapLibre GL (satélite, relevo) + camadas 3D (3D Tiles / deck.gl) para o entorno; Three.js (WebGPU) para o telhado; **computação de GPU** para insolação anual: discretização do céu em 145 segmentos (Tregenza) com *ray casting* contra o modelo via BVH (`three-mesh-bvh`), resultado por ponto a cada 0,25 m; fallback em Worker + WASM; posição solar por algoritmo de alta precisão (tipo SPA/NREL) em `energy-core`; estado do simulador na URL.

### 4.2.1 Simulador Gêmeo — `/simular`
**Papel:** o produto-porta. Em 90 segundos, a pessoa vê o telhado, o sol e o número.

**Seis passos (com barra de progresso "solar" que vai do nascer ao meio-dia):**

| Passo | O que acontece | Detalhe |
|---|---|---|
| **1. Endereço** | Autocomplete com normalização brasileira (CEP, logradouro, complemento) | Da visão do globo, a câmera **voa** até o imóvel (M-02) |
| **2. Telhado** | Detecção automática do contorno e das águas; edição de vértices, inclinação e azimute; marcação de obstáculos (caixa d'água, chaminé, árvores, vizinhos altos) | O telhado "nasce" extrudado do contorno (M-03). Exibe **Confiança da geometria** (alta/média/baixa) e sugere Captura Guiada se baixa |
| **3. Sol e sombra** | Slider de hora, dia e ano; sombras reais; mapa de calor de insolação anual por água do telhado; solstícios e equinócios | M-01, M-04, M-09. Destaca "melhor e pior dia do ano" |
| **4. Consumo** | Quatro caminhos: valor da conta, kWh, **upload da fatura** (Conta Raio-X) ou **"Monte sua casa"**, arrastando aparelhos (chuveiro, ar, geladeira, carro elétrico…) e informando hábitos | Mostra a **curva de consumo × curva do sol** sobrepostas, revelando quanto da energia gerada será usada na hora |
| **5. Preferências** | Meta (economia, independência, menor payback), orçamento, bateria, financiamento, planos de 5 anos (carro elétrico, ampliação, piscina) | Sem pergunta obrigatória além de endereço e consumo |
| **6. Prévia** | Resultado resumido; "Ver o resultado completo" | Salvar sem login; login só para compartilhar ou receber propostas |

**Painel de Resumo Vivo (sempre visível):** potência sugerida (kWp), geração anual, economia mensal e payback, todos com `ConfidenceBand` e `NumberMorph`.
**Interações:** desfazer/refazer; atalhos (setas movem a hora, `R` reseta a câmera, `Espaço` anima o dia); gestos de pinça e rotação; modo "comparar cenários" lado a lado.
**Estados e acessibilidade:** sem cobertura 3D → desenho 2D manual; sem WebGL/WebGPU → formulário guiado com estimativa regional e mapa 2D; descrição textual da geometria ("telhado de duas águas, 38 m², orientação norte e leste"); teclado completo no editor de vértices.
**Métrica:** conclusão por passo; tempo até a primeira interação com o sol; % de ajuste manual do telhado; erro médio de geometria vs Captura Guiada.

### 4.2.2 Resultado — `/simular/resultado/$id`
**Papel:** transformar a simulação em decisão com confiança.

**Conteúdo:**
1. **Manchete honesta:** "Entre R$ 310 e R$ 390 por mês. O meio do caminho é R$ 350."
2. **Relevo de 25 anos:** paisagem de economia acumulada com três cenários (conservador, base, otimista), considerando reajuste tarifário, degradação, troca de inversor e regras de transição da Lei 14.300.
3. **Cascata da conta:** o que **desaparece** da fatura, o que **permanece** (custo de disponibilidade, iluminação pública, componentes não compensáveis) e o que é **pedágio** (Fio B).
4. **Custo de esperar:** "e se eu esperar um ano?", com a variação das regras e das tarifas.
5. **Premissas e fontes:** todas editáveis; `AuditMode` mostra a fórmula de cada número.
6. **Próximos passos:** Auditar uma proposta, Criar um Brief e abrir a Arena, ver o Terminal de Financiamento, compartilhar.

**Interações:** `TimeScrubber` altera o horizonte; sliders de premissa recalculam com suavização elástica; "Explique para mim" abre o Hélio com todo o contexto.
**Tecnologia:** visx + Canvas, springs, cartão social por Satori, PDF por renderização no servidor.
**Métrica:** edição de premissas; clique em "Auditar"/"Arena"; compartilhamentos.

### 4.2.3 Conta Raio-X — `/conta-de-luz`
**Papel:** reduzir atrito e aumentar a precisão a partir da fatura real.

**Fluxo:** arrastar PDF/foto → "scanner" animado varre a conta → extração com **confiança por campo** → **Raio-X** que acende cada linha (consumo, TUSD, TE, bandeira, impostos, iluminação pública, créditos) com explicação ao toque (M-05) → *diff slider* "sua conta hoje" × "sua conta com solar" → "o que dá para reduzir mesmo sem solar".
**Privacidade:** arquivo criptografado, mascaramento de CPF e endereço, exclusão automática em 30 dias (configurável) e botão "apagar agora".
**Tecnologia:** upload resumível, fila de jobs, extração multimodal com validação por regras (soma de linhas, faixas plausíveis, coerência de bandeira), máscaras SVG e `clip-path` para o efeito.
**Estados e acessibilidade:** baixa confiança → tela de conferência campo a campo; leitura por leitor de tela da fatura estruturada; fallback manual por formulário.
**Métrica:** precisão da extração por campo (alvo ≥ 98% em campos críticos); % que conferem; conversão para o Simulador.

### 4.2.4 Captura Guiada — `/captura` *(R3)*
PWA com câmera guiada ("caminhe devagar ao redor da casa; aponte para o telhado"), sobreposições de AR que indicam cobertura e falta de ângulo, uso de LiDAR quando disponível e fotogrametria em nuvem quando não. Gera malha/*Gaussian splat* do telhado e do entorno em 3 a 6 minutos e atualiza o Simulador com margem de erro menor. Rostos e placas são desfocados antes do upload.

---

## 4.3 MUNDO BIBLIOTECA — educar com prazer

**Intenção:** educar sem "aula chata", construir confiança e captar tráfego orgânico qualificado.
**Direção de arte:** revista independente. Papel quente, tinta com leve desalinhamento (estética de risografia), tipografia editorial grande, colagens vetoriais, margens generosas, o app *desacelera*.
**Tecnologia do Mundo:** MDX com componentes `Explainer`; animações guiadas por scroll em CSS; textura de papel por ruído procedural leve; Motion para microinterações; geração estática com revalidação; JSON-LD, OG dinâmico, "Ouvir o artigo" (síntese de voz opcional).

### 4.3.1 Hub — `/aprender`
Capa de revista com destaque do mês; trilhas: **Comece aqui**, **Entenda sua conta**, **Vivendo com solar**, **Lei e burocracia**, **Para condomínios**. Busca instantânea; progresso salvo; "Pergunte ao Hélio sobre este tema".

### 4.3.2 Artigo — `/aprender/$slug`
Coluna editorial com **notas de margem do engenheiro** (comentários curtos e opinativos), citações de fonte, selo "Revisado por [engenheiro] e [advogado] em [data]", histórico de atualizações (importante para regras que mudam), e explicadores interativos embutidos. Modo leitura focado e sumário flutuante.

### 4.3.3 Glossário — `/aprender/glossario`
Cada termo é um cartão com definição em uma frase, exemplo e mini-animação; também aparece como popover em todo o produto (ancoragem nativa).

### 4.3.4 Explicadores-âncora (primeira onda)
| # | Explicador | Mecânica | Momento |
|---|---|---|---|
| E1 | **Como a compensação funciona** | Arrastar curvas de produção e consumo; créditos viram um "banco de luz"; o Fio B aparece como pedágio proporcional | M-22 |
| E2 | **Por que o inverno rende menos (e tudo bem)** | Globo inclina; trajetória do sol sobre o telhado muda mês a mês; comparação regional | M-22 |
| E3 | **Bandeira tarifária por dentro** | A escada de preços sobe e a conta em reais se reconfigura | M-22 |
| E4 | **Quanto vale o seu sol da tarde** | Mostra o descompasso entre geração e consumo e o ganho de deslocar carga | M-22 |

**Métrica:** tempo de leitura engajada; conclusão de explicadores; conversão para Simulador; posição orgânica.

---

## 4.4 MUNDO TERMINAL — densidade com clareza

**Intenção:** decisões técnicas e financeiras densas, rápidas e sem medo.
**Direção de arte:** terminal de mercado elegante. Mono, grade rígida, ticker, verde/âmbar/coral semânticos, números que *respiram*; "dados como respeito".
**Tecnologia do Mundo:** TanStack Table (colunas fixas, agrupamento, ordenação) + TanStack Virtual; gráficos em Canvas (uPlot/visx); cálculos em Web Workers; SSE para atualização; atalhos estilo `j/k`.

### 4.4.1 Auditoria de Proposta — `/auditar` *(porta de entrada de maior potencial viral)*
**Papel:** dar poder a quem já tem uma proposta na mão.

**Fluxo:**
1. **Entrada:** PDF, foto, *print do WhatsApp* ou texto colado.
2. **Leitura:** "Estou lendo sua proposta…" com extração e confiança por campo; a pessoa confirma ou corrige.
3. **Relatório com Pontuação de Coerência (0–100)**, explicável por fatores:

| Fator | O que verifica |
|---|---|
| Geração prometida | Compara com P50/P90 do modelo para aquele telhado; sinaliza acima do plausível |
| Preço por Wp | Percentil frente à referência regional (de propostas e da Arena, agregadas) |
| Equipamentos | Marcas, eficiência, garantia, degradação anual, vida do inversor |
| Dimensionamento | Coerência com o consumo e com o espaço |
| Premissas escondidas | Reajuste tarifário otimista, Fio B ignorado, sem degradação, "100% de economia" ignorando custo de disponibilidade |
| Cláusulas | Prazo, quem faz a homologação e a obra civil, troca de medidor, garantia de serviço |
| Financiamento | Juros embutidos e CET implícito |

4. **"Verdade em Vermelho" (M-06):** barras *Prometido* × *Plausível*; as divergências "rasgam" a barra de forma discreta e legível.
5. **Ações:** gerar lista de perguntas para o vendedor (copiar para WhatsApp); abrir Brief e Arena; compartilhar o relatório (dados pessoais mascarados).

**Salvaguardas:** o relatório é um **sinal, não um veredito**; o instalador **não é nomeado publicamente**; agregados só anônimos; canal de contestação; linguagem juridicamente revisada.
**Métrica:** propostas auditadas; % com divergência > 15%; conversão para Arena; compartilhamento do relatório; NPS.

### 4.4.2 Comparador — `/propostas/$id`
Tabela normalizada de 2 a 5 propostas (do cliente, da Arena ou da Auditoria): kWp, módulos, inversor, garantia, preço por Wp, prazo, pagamento, e **Custo total em 25 anos** (inclui degradação e troca de inversor). Destaque automático de "diferenças que importam" e anotações; "Perguntar ao Hélio sobre esta proposta".

### 4.4.3 Proposta Viva — `/p/$token`
Proposta interativa criada pelo instalador: 3D do layout, curva de geração, premissas **bloqueadas e obrigatórias** (não podem ser removidas), perguntas e respostas embutidas e aceite digital.
**Promessa Registrada:** a geração anual prometida (P50) é **selada com data e *hash***. Ao longo dos anos, vira a base de Promessa vs Realidade e da Garantia de Geração.

### 4.4.4 Terminal de Financiamento — `/financiamento`
**Layout:** à esquerda parâmetros; ao centro **fluxo de caixa mensal** (parcela × economia) com o **ponto de virada**; à direita tabela de linhas (bancos, fintechs, cooperativas, linhas verdes) com CET, prazo, carência e garantias; abas: à vista, financiado, consórcio, assinatura de energia.
**Interações:** sliders com resistência física e "ímãs" em valores comuns; curvas que morfam entre cenários; benchmark "estou pagando juros demais?"; M-16 no instante do ponto de virada; `Ticker` mostra taxa de referência do dia.
**Regulatório:** CET e avisos legais sempre visíveis; parceiros e comissões identificados.

---

## 4.5 MUNDO ARENA — disputa transparente

**Intenção:** transformar a escolha do instalador numa disputa justa pelo melhor para o cliente.
**Direção de arte:** placar esportivo com elegância de leilão. Ritmo, contagem regressiva, cores quentes, tipografia de placar, *microtipografia* de resultado.
**Tecnologia do Mundo:** SSE/WebSocket para lances; View Transitions e animações de *layout* (FLIP) para reordenação; TanStack Virtual; coreografia de "Revelação" em Motion.

### 4.5.1 Marketplace — `/instaladores`
Mapa (deck.gl com hexágonos H3 de área de atendimento) + lista virtualizada. Filtros por nota, **performance verificada**, projetos, marcas, tempo de resposta, financiamento. Cada cartão tem **"Por que está aqui?"** explicando a fórmula do ranking (sem pay-to-rank). Comparar até 3.
**Transição compartilhada** do cartão ao perfil (M-27).

### 4.5.2 Perfil do instalador — `/instaladores/$slug`
Selos, **Performance Real** (previsto × gerado em projetos concluídos, anonimizados), tempo médio de homologação, galeria com mini-3D, reclamações e respostas, equipe e certificações. Botão "Pedir proposta" ou "Convidar para a Arena".

### 4.5.3 Brief Único — `/brief/$id`
Pré-preenchido pela simulação. Define faixa de kWp, marcas aceitas (ou "sem preferência"), itens inclusos (obra civil, homologação, troca de medidor), prazo desejado, forma de pagamento e orçamento. O cliente escolhe o número de convidados (3 a 7, sugeridos por afinidade) e pode excluir empresas. **Regras da Arena** visíveis em linguagem simples.

### 4.5.4 Arena — `/arena/$id`
**Papel:** o coração do Decidir.

| Fase | Duração | O que acontece |
|---|---|---|
| **1. Lances cegos** | até 72 h | Instaladores enviam propostas em **formato padronizado** (preço, equipamentos, prazo, garantia, geração P50, pagamento). Geração prometida acima do P90 do modelo é sinalizada |
| **2. Revelação** | cerimônia | Lances aparecem anonimizados (Instalador A…E), um a um, com animação e **Placar HELIO** explicável (M-15) |
| **3. Perguntas** | 48 h | Perguntas do cliente são visíveis para todos (justiça entre instaladores) |
| **4. Melhor e final** | 24 h | Os 3 melhores podem melhorar a oferta |
| **5. Escolha** | — | Identidades reveladas; Proposta Viva assinada |

**Regras:** instaladores não veem dados pessoais até a escolha; prevenção de conluio e de *low-ball* (preço absurdo para ganhar e depois renegociar) por monitoramento e sanção; cobrança de **sucesso** do instalador (cliente não paga); cancelamento sem custo para o cliente.
**Métrica:** tempo até a escolha; economia vs proposta direta; satisfação do cliente e do instalador; taxa de renegociação pós-escolha.

### 4.5.5 Mutirão — `/mutirao` e `/mutirao/$id` *(R3)*
Vizinhos da mesma região agrupam compras para obter desconto por volume. Anel de progresso até degraus de desconto; pinos de telhados participantes **desfocados ao nível de quadra** (privacidade); convite por WhatsApp; um instalador vencedor por lote via Arena de grupo; logística por rua.

---

## 4.6 MUNDO CÚPULA — o diorama vivo da sua casa

**Intenção:** responder em 3 segundos: "Estou gerando bem? Estou economizando? Preciso fazer algo?"
**Direção de arte:** uma maquete da *sua* casa dentro de uma cúpula de vidro, sobre uma base de silício. Dentro da cúpula vive o céu real do seu bairro. Iluminação cinematográfica suave, profundidade de campo estilo *tilt-shift*, reflexos no vidro.
**Tecnologia do Mundo:** Three.js/R3F (WebGPU/WebGL2) no Palco Persistente; casa generalizada por tipologia + geometria real do telhado e orientação; céu dinâmico a partir do Motor de Luz; nuvens animadas por vetores de movimento derivados de satélite; chuva e vento por partículas em GPU; vidro com refração simples; renderização em `OffscreenCanvas` num Worker quando possível (a thread principal fica livre para interação).

### 4.6.1 Cúpula (Home) — `/app`
**Layout:** a cúpula ocupa o centro; ao redor, três instrumentos:

| Instrumento | Mostra | Componente |
|---|---|---|
| **Agora** | Potência instantânea e fluxo sol → casa → rede → bateria | `EnergyRiver` (M-12) |
| **Hoje** | Geração real × esperada ao longo do dia, com sol e faixa de confiança | `SunDial` |
| **Mês** | Economia acumulada, meta e projeção | `NumberMorph` + `Reservoir` |

**Interações:**
- **Tocar num painel** abre a string/módulo (desempenho relativo).
- **Tocar no medidor** mostra o fluxo com a rede e os créditos.
- **Tocar num aparelho** (chuveiro, ar, carro, piscina) mostra o estado e a regra do Piloto.
- **Arrastar na horizontal** viaja no tempo (M-09); **pinçar para fora** ativa o Zoom Cósmico (M-10); **pressionar e segurar** pergunta ao Hélio "o que aconteceu aqui?" naquela hora.
- **Inclinar o aparelho** (giroscópio, opt-in) move a luz e cria paralaxe; **Cúpula Viva** (M-07) reage ao clima real; **sombra de nuvem** (M-08) cruza os painéis em sincronia com a curva.

**Interface por intenção:** a ordem dos cartões se adapta ao momento — **manhã:** Previsão do dia e janela de ouro; **meio-dia:** Piloto em ação; **fim de tarde:** resumo do dia; **fim de mês:** Fatura Prevista. Um cartão **"Hélio sugere"** aparece só quando há algo de valor (limite de frequência por regra).
**Estados:** *recém-instalado* ("aguardando o primeiro raio", animação de nascer do sol, M-11); *inversor offline* (última leitura com selo de idade e guia de reconexão); *dados parciais* (medidor sem leitura → valores marcados como estimados); *noite* (cúpula iluminada por dentro, resumo do dia).
**Acessibilidade:** resumo textual falado/lido ("Agora você gera 3,2 kW, 12% acima do esperado"); modo sem cena (apenas instrumentos); atalhos de teclado; alvo de toque 44 px.
**Métrica:** retorno D7/D30; tempo até a primeira interação; ações iniciadas pelos cartões; cobertura de "dado em tempo real".

### 4.6.2 Zoom Cósmico — gesto na Cúpula *(M-10)*
Zoom semântico contínuo, onde cada nível troca dados e escala:

| Nível | O que aparece |
|---|---|
| Casa | Sua geração e consumo |
| Rua | Vizinhos com solar (agregado, desfocado) |
| Bairro | Geração agregada × consumo, Vila Solar |
| Cidade | Participação de GD, preço médio, instaladores |
| Rede | Carga e geração regional (dados abertos do setor elétrico, a validar) |
| Brasil | Atlas Solar |
| Planeta | Linha de dia e noite |
| Sol | "Essa luz saiu do Sol há 8 minutos e 20 segundos." |

Acessível por lista de níveis com resumo textual, teclado (`+`/`−`) e preferência "Calmo" (troca por cortes suaves).

### 4.6.3 Sistema — `/app/sistemas/$id`
Esquema 3D do telhado com cada módulo ou *string* colorido pela **performance relativa** (identifica a *string* fraca); lista de dispositivos (inversor, medidor, bateria, carregador); **Esperado × Real** sobreposto; manutenção e garantias com contagem regressiva; ficha de cada equipamento (degradação esperada, vida útil) e histórico de eventos.

### 4.6.4 Previsão — `/app/previsao`
Próximas 6 horas com **nowcasting** (atualização a cada ~10 min) e próximos 7 dias; **Janela de Ouro** (melhores horas para consumo); faixa de incerteza; perspectiva da bandeira tarifária; e prestação de contas: **"Previsão de ontem × realizado"** sempre visível.

### 4.6.5 Piloto Automático Solar — `/app/piloto`
**Papel:** passar de *informar* para *agir*. É o recurso que mais aumenta a economia depois da instalação.

**Princípio de honestidade:** nem tudo é deslocável. O **chuveiro elétrico**, por exemplo, aquece na hora do banho e **não** é deslocável; para ele o HELIO apenas orienta hábitos e, se fizer sentido financeiro, sugere alternativas (boiler elétrico de acumulação, bomba de calor).

**Cargas deslocáveis típicas:** bomba de piscina, carro elétrico (OCPP), máquinas de lavar/secar/lava-louças (tomadas inteligentes, com janela escolhida), boiler/aquecedor de acumulação, pré-resfriamento do ar-condicionado em 1–2 °C antes do fim do sol, bomba d'água, irrigação, desumidificador.

**Interface:** linha do tempo do dia com o **orçamento de sol** (excedente previsto) desenhado como uma área de céu; o Hélio "encaixa" cada carga nessa área (M-14). Para cada carga: prioridade, janela permitida, **conforto mínimo** (ex.: temperatura da casa ≥ X às 19 h) e limites de potência.
**Modo Sombra:** antes de ativar, o Piloto **simula por 7 dias** e mostra quanto teria economizado, sem controlar nada.
**Segurança (inegociável):**
- Consentimento por dispositivo e **botão de pânico** (tudo volta ao manual).
- **Lista de bloqueio** de cargas críticas (equipamentos médicos, refrigeração de alimentos essenciais, alarmes).
- *Fail-safe*: se o HELIO ficar offline, o dispositivo segue o agendamento local.
- Registro de auditoria de cada ação; reversão com um toque.
- **Atribuição honesta de economia**, comparando com a linha de base contrafactual e explicando o método.
**Integrações:** Matter, Home Assistant, Tuya/Smart Life, Shelly, SmartThings, Google Home, OCPP (carregadores). Preferência por controle **local** quando possível.
**Métrica:** % de usuários com Piloto ativo; R$ economizados atribuídos; intervenções manuais (taxa de "desfazer"); incidentes de segurança (meta zero).

### 4.6.6 Créditos — `/app/creditos`
Cada UC é um **Reservatório** com nível animado; vencimentos (créditos expiram em 60 meses); simulação "e se eu redistribuir 30% para a UC B?"; alerta de crédito prestes a vencer; "quanto de Fio B estou pagando".

### 4.6.7 Fatura Prevista — `/app/fatura`
Estimativa da próxima fatura com antecedência (consumo + geração + bandeira + tarifa), em **Cascata**; alavancas "se eu fizer X" (deslocar cargas, ajustar tarifa); comparação com o mês anterior em linguagem natural.

### 4.6.8 Rastreio de Obra — `/app/obra/$id`
Linha do tempo estilo "rastreio de pedido": **Contrato → Vistoria → Projeto → Parecer de acesso → Instalação → Troca de medidor → Ativação → Primeiro Raio**. Cada etapa tem prazo estimado (calibrado com dados reais da distribuidora e do instalador), responsável, documentos e "o que preciso fazer agora". Alertas de atraso e canal com o instalador. Informação da distribuidora por integração, e-mail parseado ou atualização assistida (viabilidade a validar por distribuidora).

### 4.6.9 O Primeiro Raio — celebração *(M-11)*
Na primeira geração: o sol da Cúpula "acende" a casa; cartão compartilhável; convite a vizinhos; ativação do Boletim do Sol.

### 4.6.10 Documentos — `/app/documentos`
Cofre com contratos, ART, notas fiscais, laudos e garantias; busca por conteúdo; vencimentos; compartilhamento temporário com instalador ou comprador do imóvel.

### 4.6.11 Passaporte do Sistema — `/passaporte/$id`
Histórico **verificado** e transferível: geração mensal real, equipamentos, manutenções, documentos, selo HELIO com *hash* de integridade e QR. Fluxo "transferir para o comprador" e PDF de **Certificado de Desempenho** que valoriza o imóvel na venda. Dados pessoais sempre mascarados e sob consentimento.

### 4.6.12 Modo Simples — `/app?modo=simples`
Três informações, enormes e calmas: **status** (☀️ "Tá tudo certo" / ⚠️ "Precisa de atenção"), **economia do mês** e **botão grande "Falar com o Hélio"**. Sem gráficos, sem menus escondidos. Espelhado no WhatsApp (Boletim do Sol).

### 4.6.13 Sol de Parede — `/parede` *(F-411)*
Modo ambiente em tela cheia para tablet/TV antigos: sol e céu reais em movimento lento, um número grande, e o **Semáforo da Casa** (verde, âmbar, vermelho): "bom momento para ligar cargas pesadas?" (M-30). Usa *Wake Lock*, desloca elementos pixel a pixel contra *burn-in*, escurece automaticamente à noite.

---

## 4.7 MUNDO ORBE — o Hélio

**Intenção:** ser o "engenheiro de bolso" que explica, antecipa e executa, com personalidade.
**Direção de arte:** **luz viva**. O Orbe é um volume de luz controlado por shader; não tem rosto. Cenário mínimo; o conteúdo é o protagonista.
**Tecnologia do Mundo:** streaming por SSE; **UI generativa** com registro de componentes permitido (o modelo emite *tool calls* tipadas e validadas por schema; o cliente renderiza **apenas** componentes da lista branca); API do Claude com *tool use*; voz por Web Speech/WebRTC; shader do Orbe por estados.

### 4.7.1 Copiloto Hélio — `/app/helio`
**Formato:** não é um chat de bolhas, é um **fluxo de cartões** compostos por blocos: texto curto, número-chave, gráfico, ação. O Orbe ocupa o topo e reage (M-13).
**Capacidades:** "por que gerei menos ontem?", "vale a pena a tarifa branca?", "posso ligar o ar mais cedo sem pagar mais?", "explica minha última fatura", "analisa esta proposta", **foto do display do inversor com um código de erro** (diagnostica e orienta), geração de relatório mensal.
**Entradas:** texto, voz (aperte-e-fale ou mãos livres), foto/PDF.

**Ferramentas tipadas (exemplos):** `get_production`, `get_forecast`, `simulate_roi`, `explain_bill_line`, `compare_proposals`, `schedule_load` (com confirmação), `open_ticket_with_installer`, `get_tariff_info`, `show_chart`, `show_table`, `show_action`.

**Regras de ouro:**
1. **Números só vêm de ferramentas determinísticas.** O modelo nunca "calcula de cabeça".
2. **Citar a origem:** cada resposta indica que dados do usuário e quais fontes usou, com o botão **"Ver como calculei"** (abre a decomposição).
3. **Sem aconselhamento jurídico/financeiro definitivo**; indica profissional quando apropriado.
4. **Ações exigem confirmação** e são reversíveis.
5. **Memória sob controle:** painel "O que o Hélio sabe sobre mim", editável e apagável.
6. **Proatividade com freios:** o Hélio só inicia contato por regra (anomalia, crédito prestes a vencer, oportunidade acima de R$ X), com teto de frequência e *quiet hours*.
**Qualidade:** primeiro token < 1,2 s; conjunto de avaliações dourado (perguntas reais anonimizadas); tolerância de alucinação numérica ≈ 0; orçamento de custo por usuário/mês com cache e roteamento de modelo.
**Segurança:** conteúdo de faturas, propostas e e-mails é tratado como **dado não confiável** (defesa contra *prompt injection*), com isolamento de instruções e filtragem de saída.
**Estados e acessibilidade:** modo texto puro; compatível com leitores de tela; transcrição de voz visível; velocidade de fala ajustável.

### 4.7.2 Command Bar — `Ctrl/Cmd + K` *(M-28)*
Busca e ações globais com **linguagem natural**: "quanto gerei em março?" responde inline com mini-gráfico; "ativar modo férias" executa com confirmação; "abrir simulação da casa da praia" navega. Teclado em primeiro lugar, histórico e favoritos.

### 4.7.3 Boletim do Sol — WhatsApp, push e áudio *(M-25)*
Resumo diário (padrão 7 h) com previsão, **janela de ouro** e uma dica; resumo opcional da noite; semanal aos domingos. **Áudio de 20 segundos** com a voz do Hélio. No WhatsApp, o usuário responde "gerei quanto hoje?" e o Hélio responde dentro do escopo; mensagens proativas usam modelos aprovados; **opt-in explícito**, opt-out em um toque e respeito à janela de atendimento da plataforma.

---

## 4.8 MUNDO AURORA — a rede de vizinhos

**Intenção:** tornar visível e justo o compartilhamento de energia entre pessoas.
**Direção de arte:** noite profunda. Casas como estrelas; créditos como **fitas de luz** (aurora) que viajam entre elas, acompanhando as ruas. Trilha sonora ambiente opcional.
**Tecnologia do Mundo:** partículas de fita em *compute shader*; mapa noturno estilizado; posições aproximadas por privacidade; `d3-force` para layout quando não há geografia; livro-razão de apenas anexar (append-only) para trilha de auditoria.

### 4.8.1 Vila Solar — `/vila/$id` *(R3)*
- **Constelação:** casas como estrelas, tamanho = capacidade, brilho = geração atual (M-17).
- **Aurora de créditos:** a cada transferência, uma fita percorre a rua (M-18); clicar mostra quem deu e quem recebeu.
- **Regras de rateio** editáveis e **simuláveis**: "se mudarmos para 40/40/20, veja o impacto individual e coletivo" *antes* de votar.
- **Livro-razão aberto** (auditável e exportável); votações com quórum e trilha.
- **Assistente de formalização:** explica em linguagem simples as formas jurídicas possíveis (autoconsumo remoto, geração compartilhada via consórcio/cooperativa/condomínio) e gera **minutas** (estatuto/ata) *a validar com assessoria jurídica*.
**Salvaguardas:** o HELIO é camada de gestão e transparência; a compensação segue regras da distribuidora e da ANEEL; avisos claros de responsabilidade.

### 4.8.2 Condomínio Solar — `/condominio/$id` *(R3)*
Modo **Console** para o síndico: rateio por fração ideal, por consumo ou igualitário; áreas comuns; simulações para assembleia; **relatório de assembleia** (PDF e link público de leitura); votações com quórum e atas; visão simples para cada morador (sua parte, sua economia).

### 4.8.3 Cotas solares *(R3/R4)*
Vitrine de cotas de usinas de **parceiros regulados** para inquilinos e apartamentos: desconto garantido (com a base de cálculo explicada), prazos, saída sem multa abusiva, comparação entre ofertas e acompanhamento do abatimento na conta.

---

## 4.9 MUNDO FLORESTA — impacto e orgulho

**Intenção:** gerar hábito e compartilhamento sem *greenwashing*.
**Direção de arte:** natureza pintada. Volumes suaves, luz quente, vento visível; estações mudam no tempo real da conta.
**Tecnologia do Mundo:** *GPU instancing* para milhares de árvores, shader de vento, ciclo dia/noite pelo Motor de Luz, Rive para conquistas e mascote, vídeo renderizado para o Ano Solar.

### 4.9.1 Impacto — `/app/impacto`
**Floresta Solar:** cada árvore equivale a uma quantidade fixa de CO₂ evitado, com **metodologia a um toque** (fator de emissão da rede brasileira por ano, fonte oficial a validar). **A árvore cresce quando o dia fecha** (M-19). Conquistas (Rive), metas mensais e **Missões do Sol** (família). Comparações só entre amigos que aceitarem; nunca punitivas.
**Ética:** sempre rotulado como **estimativa**; sem compensações simbólicas; sem pressão social.

### 4.9.2 Seu Ano Solar — `/ano-solar/$ano` *(R3)*
História vertical de 8 a 10 cartões, estilo *stories*, com trilha gerada pela geração do ano (M-20): *seu dia mais luminoso*, *a noite que não gerou nada (e tudo bem)*, *quanto você economizou*, *o que o Piloto fez por você*, *seu vizinho mais próximo*, *suas árvores*, *seu sol em 12 meses (relevo)*, *uma frase do Hélio*. Vídeo 9:16 para compartilhar; **valores ocultos por padrão** (opção de mostrar). Lançado no fim do ano.

---

## 4.10 MUNDO ATLAS — o Brasil visto do sol

**Intenção:** dados abertos úteis, motor de confiança e de aquisição orgânica.
**Direção de arte:** cartografia e arte de dados. Fundo escuro de mapa náutico, tipografia mono nos rótulos, colunas extrudadas luminosas, linhas finas.
**Tecnologia do Mundo:** globo → mapa por transição contínua; deck.gl (H3, colunas extrudadas, arcos); *time slider* animado; páginas municipais geradas com dados originais; privacidade por **k-anonimato** (agregados só com ≥ 20 sistemas por célula).

### 4.10.1 Atlas — `/atlas`
Camadas: potencial (kWh/kWp·ano), geração real agregada, tarifas por distribuidora, preço médio por Wp (agregado da Arena), adoção de GD. Voo de câmera do globo ao município (M-23).

### 4.10.2 Página municipal — `/atlas/$uf/$municipio`
Gerada para os 5.570 municípios **somente quando há dados originais suficientes** (senão `noindex`): potencial, tarifa, adoção, preço médio, instaladores verificados, FAQ local e um mini-mapa. Conteúdo único, não "página fina".

### 4.10.3 Promessa vs Realidade — `/promessa-vs-realidade`
Página pública que mostra o **erro real das estimativas do HELIO**: viés e erro médio por mês, região e tecnologia; gráfico de calibração (previsto × real, em WebGL quando há muitos pontos); histórico de versões do modelo com *changelog*; "onde mais erramos e o que fizemos"; **download dos dados agregados**. É o maior ativo de marca do produto.

### 4.10.4 Metodologia — `/metodologia`
Fórmulas, fontes, premissas, versões, limitações e auditorias independentes (planejadas). Todo número do produto tem link para cá.

---

## 4.11 MUNDO OFICINA — ferramentas profissionais

**Intenção:** produtividade e densidade para instaladores e equipe interna.
**Direção de arte:** ferramenta profissional (metal escovado, neutros, alta densidade); **Console** como padrão.
**Tecnologia do Mundo:** TanStack Table/Virtual, `cmdk`, dnd-kit, Three.js com *picking* por GPU, multiplayer (R4).

### 4.11.1 Portal do Instalador
| Tela | Função |
|---|---|
| **Leads** (`/instalador/leads`) | Kanban (Novo → Contatado → Visita → Proposta → Ganho/Perdido); cada cartão traz mini-3D do telhado, consumo e orçamento; **SLA** em anel de contagem; pontuação de qualidade do lead **explicável**; atalhos; respostas-modelo; integração com WhatsApp |
| **Arena** (`/instalador/arena`) | Arenas abertas na sua área; **compositor de lance** com validação ao vivo (geração vs P90, equipamentos do catálogo, dicas de faixa de preço agregadas, cálculo de margem); contagem regressiva; **"por que perdi"** anônimo e acionável (preço 12% acima da mediana, prazo longo etc.) |
| **Editor 3D** (`/instalador/editor/$id`) | Importa o telhado do cliente; módulos arrastáveis com grade **magnética** (M-29); afastamentos normativos; strings, escolha de inversor, sombreamento por módulo em GPU; lista de materiais; exporta planta (PDF/DXF); desfazer/refazer; colaboração multiusuário (R4) |
| **Propostas** (`/instalador/propostas`) | Modelos com a marca da empresa; premissas obrigatórias; **Promessa Registrada**; rastreio de visualização |
| **Obras** (`/instalador/obras`) | Pipeline de instalações com checklists de homologação; **Kit de Homologação** gerado automaticamente (memorial descritivo, diagrama unifilar, formulários) |
| **Reputação** (`/instalador/reputacao`) | Avaliações, **Selo Performance Verificada**, metas de qualidade, resposta pública |
| **Financeiro** (`/instalador/financeiro`) | Comissões, repasses, notas fiscais |

### 4.11.2 Admin — `/admin/*`
Moderação e verificação de instaladores, filas (OCR de baixa confiança, disputas), *feature flags* e experimentos, monitor de integrações, monitor de **deriva do modelo** e painel de precisão interno, CMS da Biblioteca, auditoria, "ver como usuário" **somente leitura e auditado**, e **Sala de Crise** para incidentes. Densidade máxima e `Command Bar`.

### 4.11.3 Páginas de sistema
- **Entrar/Cadastro:** *passkeys* como primeira opção, link mágico, Google/Apple; cena de fundo calma (shader lento).
- **Onboarding:** quatro telas curtas com transições cinematográficas e o Orbe reagindo às respostas (M-13).
- **Status e Privacidade:** página pública de saúde dos serviços; Central de Privacidade (exportar tudo, apagar, ver quem acessou).
- **404/500 "Eclipse" (M-24):** a lua cobre o sol; a pessoa "devolve a luz" arrastando a lua; links úteis em destaque.

---

## 4.12 Catálogo de Momentos Uau

> Cada momento tem **gatilho**, **comportamento**, **técnica**, **fallback** e **equivalente acessível**. Nenhum pode violar o **Orçamento de Uau** (um por viewport).

| ID | Momento | Onde | Gatilho → Comportamento | Técnica | Fallback / Acessível |
|---|---|---|---|---|---|
| M-01 | **Sol arrastável** | Landing, Simulador | Arrastar o sol muda hora, céu, sombras e cor da página | Motor de Luz + shader de sombra | Slider de hora + texto "13h: 3,2 kW esperados" |
| M-02 | **Voo até o telhado** | Landing → Simulador | Enviar endereço → o campo vira o mapa e a câmera voa do globo ao imóvel | Transição compartilhada + câmera Bézier | Corte rápido para o mapa |
| M-03 | **Telhado nascendo** | Simulador | Contorno detectado "levanta" e vira o telhado 3D | Extrusão animada | Aparece direto |
| M-04 | **Sombra da árvore** | Simulador | Ao mover o slider, a sombra caminha pelo telhado e o mapa de calor anual preenche | *Compute* de insolação | Mapa de calor estático |
| M-05 | **Raio-X da fatura** | Conta Raio-X | Scanner varre; cada linha acende e explica ao toque | SVG mask + clip-path | Tabela anotada |
| M-06 | **Verdade em vermelho** | Auditoria | Barras Prometido × Plausível "rasgam" onde divergem | Canvas + springs | Tabela de divergências com ícones |
| M-07 | **Cúpula viva** | Cúpula | O céu dentro da cúpula espelha o clima real (sol, nuvem, chuva, noite) | Cena 3D + clima | Cartão de clima textual |
| M-08 | **Sombra de nuvem** | Cúpula, Previsão | Nuvem cruza o telhado; a curva de geração cai na mesma hora | Nowcasting + sincronização | Evento "nuvem passando: −18%" na linha do tempo |
| M-09 | **Viagem no tempo** | Cúpula, Resultado | Arrastar o tempo: hora → dia → ano → 2051 | `TimeScrubber` global | Seletor de data + resumo falado |
| M-10 | **Zoom Cósmico** | Cúpula | Pinça do telhado ao Sol | Zoom semântico em níveis | Lista de níveis com resumos |
| M-11 | **O Primeiro Raio** | Cúpula | A casa "acende" na primeira geração | Cena + partículas | Cartão de celebração + som opcional |
| M-12 | **Rio de energia** | Cúpula | Partículas fluem entre fontes e destinos proporcionais ao kW | *Compute* de partículas | Diagrama de fluxo estático com valores |
| M-13 | **Orbe responde** | Orbe, Onboarding | O Orbe respira, ouve, pensa e comemora conforme o estado | Shader parametrizado | Indicador textual de estado |
| M-14 | **Piloto em ação** | Piloto | O Hélio "encaixa" cargas na área de sol; ao ligar, o aparelho acende na casa | Animação de layout + Cúpula | Lista de ações com horários |
| M-15 | **Revelação de lances** | Arena | Lances surgem um a um, ordenados, com Placar HELIO | Animação coreografada + SSE | Tabela revelada de uma vez |
| M-16 | **Ponto de virada** | Financiamento | No mês em que a economia supera a parcela, a curva "acende" | Canvas + marco | Texto: "a partir do mês 7…" |
| M-17 | **Constelação de vizinhos** | Vila Solar | Casas brilham conforme geram | WebGL | Lista por brilho/geração |
| M-18 | **Aurora de créditos** | Vila Solar | Fitas de luz viajam entre casas a cada transferência | *Compute* de partículas | Linha do tempo de transferências |
| M-19 | **Árvore cresce** | Floresta | Ao fechar o dia, uma nova árvore brota | Instancing + animação | Contador "+0,3 árvore hoje" |
| M-20 | **Ano Solar** | Wrapped | História cinematográfica com trilha da sua geração | Vídeo + áudio generativo | Resumo em texto e imagens |
| M-21 | **Papel respira** | Biblioteca | O papel reage ao scroll com sutil variação de tinta e sombra de dobra | Shader leve | Fundo liso |
| M-22 | **Mão na massa** | Explicadores | O leitor manipula o conceito em vez de lê-lo | Componentes interativos | Passo a passo ilustrado |
| M-23 | **Voo do Atlas** | Atlas | Do globo ao município com câmera contínua | deck.gl + transições | Navegação por lista/hierarquia |
| M-24 | **Eclipse** | 404/500 | A lua cobre o sol; arrastar devolve a luz | Shader simples | Mensagem + links |
| M-25 | **Boletim em áudio** | WhatsApp/Push | Resumo falado de 20 s | Síntese de voz | Texto e imagem |
| M-26 | **Tick do Terminal** | Terminal | Números "teclam" para novos valores | NumberMorph tabular | Troca direta |
| M-27 | **Transição compartilhada** | Marketplace → Perfil | O cartão cresce até virar a página | View Transitions | Navegação padrão |
| M-28 | **Comando falado** | Command Bar | Pergunta em linguagem natural vira resposta inline | Tool use + UI generativa | Resultado em texto |
| M-29 | **Layout magnético** | Editor 3D | Módulos "encaixam" na grade com faísca de luz | Snapping + shader | Campos numéricos de posição |
| M-30 | **Semáforo da Casa** | Sol de Parede | Verde/âmbar/vermelho para cargas pesadas | Previsão + regras | Texto grande + som opcional |

---

# PARTE 5 — ARQUITETURA E ENGENHARIA

## 5.1 Princípios arquiteturais

1. **Conteúdo primeiro:** toda rota entrega HTML útil via SSR em streaming; cenas e mapas são camadas progressivas.
2. **A cena é uma camada, não uma página:** um único Palco 3D persistente serve todas as rotas.
3. **Núcleo puro e determinístico:** todo número vem de `energy-core`, uma biblioteca isomórfica, versionada e testada à exaustão.
4. **Tempo real por padrão:** SSE para telemetria, lances e fluxos; polling adaptativo como degradação.
5. **Local-first onde faz sentido:** cache offline de telemetria recente, edição do simulador e do editor sem rede.
6. **Adaptadores plugáveis:** inversores, casa inteligente, distribuidoras, dados de irradiação e crédito entram por interfaces estáveis.
7. **Observabilidade desde o dia 1:** traços, métricas de experiência e precisão do modelo são requisitos de produto.
8. **Custo é requisito:** orçamento por usuário para IA, renderização no servidor, armazenamento e telemetria.

## 5.2 Visão de componentes

```
                         ┌────────────────────────────────────────────┐
  Navegador / PWA        │  TanStack Start (SSR + server functions)   │
 ┌──────────────────┐    │  ┌──────────────┐  ┌────────────────────┐  │
 │ Rotas (Router)   │◄──►│  │ Loaders/Query│  │ Middleware: auth,  │  │
 │ UI (React)       │    │  │ (hidratação) │  │ rate-limit, tenant │  │
 │ ┌──────────────┐ │    │  └──────┬───────┘  └─────────┬──────────┘  │
 │ │ Palco (Stage)│ │    └─────────┼────────────────────┼─────────────┘
 │ │ WebGPU/WebGL │ │              │                    │
 │ │ Worker render│ │       ┌──────▼──────┐      ┌──────▼───────┐
 │ └──────────────┘ │       │ API interna │      │ SSE / WS     │
 │ Workers: insola- │       │ (domínio)   │      │ (tempo real) │
 │ ção, telemetria  │       └──────┬──────┘      └──────▲───────┘
 └──────────────────┘              │                    │
                        ┌──────────┼──────────┬─────────┴───────┐
                 ┌──────▼─────┐ ┌──▼───────┐ ┌▼───────────┐ ┌───▼─────────┐
                 │ Postgres   │ │ Filas e  │ │ Serviço de │ │ Serviço de  │
                 │ PostGIS +  │ │ workers  │ │ previsão   │ │ IA (Claude, │
                 │ Timescale  │ │ (OCR,    │ │ (Python:   │ │ extração,   │
                 └────────────┘ │ ingestão,│ │ física+ML) │ │ copiloto)   │
                                │ relat.)  │ └────────────┘ └─────────────┘
                                └────┬─────┘
              ┌──────────────┬───────┴────────┬─────────────────┐
        ┌─────▼─────┐ ┌──────▼──────┐ ┌───────▼───────┐ ┌───────▼────────┐
        │ Adaptadores│ │ Fontes de   │ │ Casa inteli-  │ │ Objetos (S3):  │
        │ de inversor│ │ clima, sat. │ │ gente (Matter,│ │ faturas, docs, │
        │            │ │ irradiação  │ │ HA, Tuya, OCPP)│ │ splats, vídeos │
        └────────────┘ └─────────────┘ └───────────────┘ └────────────────┘
```

## 5.3 Stack e maturidade

> *Estado do ecossistema em out/2026 segundo fontes públicas: Router, Query, Form e Virtual estáveis; **Start em Release Candidate (linha 1.168.x)**; Table v9 anunciada como estável em ago/2026; DB e AI em beta; Store em alfa. **Travar versões e reconfirmar o estado no spike da M0.***

| Camada | Escolha | Observação de risco |
|---|---|---|
| **Framework** | **TanStack Start** (React 19) | RC: travar versão, camada de abstração nos pontos críticos, plano B de hospedagem |
| **Roteamento** | TanStack Router | Estável; estado da experiência na URL |
| **Dados** | TanStack Query | Estável |
| **Tabelas/Listas** | TanStack Table + Virtual | Estável; avaliar migração para a v9 em release própria |
| **Formulários** | TanStack Form | Estável |
| **Estado local** | TanStack Store (alfa) com adaptador; alternativa: Zustand para cena | Isolar atrás de interface |
| **Utilitários** | TanStack Pacer (throttle/debounce/filas) | Avaliar em spike |
| **Local-first** | TanStack DB (beta) para cache de telemetria; alternativa: IndexedDB + Query persister | Spike com critérios de saída |
| **IA no cliente** | TanStack AI (beta) para streaming de chat; alternativa: SSE próprio | Spike |
| **Estilo** | Tailwind CSS v4 + CSS moderno (`@property`, container queries, scroll-driven, anchor positioning, `@starting-style`, view transitions, `light-dark()`) | *Progressive enhancement* com `@supports` |
| **Componentes base** | Radix/Base UI + componentes próprios | Acessibilidade |
| **Animação** | Motion (springs), GSAP+ScrollTrigger (cenas), Lenis (scroll), Rive (personagens), CSS nativo (primário) | Uma ferramenta por tipo de problema |
| **3D/GPU** | Three.js + R3F + drei; **WebGPU/TSL** com fallback WebGL2; `three-mesh-bvh`; KTX2/Basis, Draco/Meshopt | WebGPU disponível nos principais navegadores desde 2025–26 |
| **Mapas** | MapLibre GL + deck.gl (H3, 3D Tiles) | Código aberto |
| **Gráficos** | visx, D3 (escalas/force), uPlot, Canvas/WebGL | Foco em desempenho |
| **Banco** | PostgreSQL + PostGIS + TimescaleDB; Drizzle ORM | Séries temporais e geo |
| **Auth** | Better Auth (passkeys, OAuth, MFA) | Portabilidade |
| **Jobs** | Fila em Postgres (pg-boss) → fila gerenciada ao escalar | Simplicidade inicial |
| **Arquivos** | S3 compatível, URLs assinadas | Faturas, documentos, splats |
| **IA** | API do Claude (copiloto, extração multimodal) com *tool use* | Ver 6.2 |
| **Previsão** | Serviço Python (pvlib, GBM/redes leves) | Modelos versionados |
| **Tempo real** | SSE (padrão), WebSocket (quando bidirecional) | Simples e barato |
| **Qualidade** | Vitest, fast-check, Playwright, Storybook, Chromatic, axe-core, Lighthouse CI | Ver 6.6 |
| **Observabilidade** | OpenTelemetry, Sentry, RUM de Web Vitals | Diagnóstico ponta a ponta |
| **Hospedagem** | A decidir em spike (Cloudflare, Vercel ou Netlify; Nitro garante portabilidade) | Critérios: latência BR, custo, WebSocket/SSE |

## 5.4 Como o TanStack sustenta a experiência

| Peça | Uso no HELIO |
|---|---|
| **Router** | **Estado como URL:** `?t=2026-06-21T13:00&cam=roof&mundo=ateliê` reproduz exatamente o que a pessoa vê; links compartilháveis; *route masking* para modais; *pathless layouts* para o Palco; **pré-carregamento por intenção** (hover/viewport) de rotas e cenas |
| **Start** | SSR com *streaming* (o shell chega primeiro, dados pesados fluem depois); *server functions* validadas por schema; *middleware* (auth, rate limit, tenant, auditoria); rotas de servidor para webhooks (inversores, WhatsApp, pagamentos); `head` por rota para SEO e OG dinâmico |
| **Query** | `ensureQueryData` nos *loaders* (sem *waterfalls*); **polling adaptativo** (mais rápido com a aba ativa e Tier alto, mais lento em segundo plano); mutações otimistas (Piloto, Créditos); persistência offline |
| **Table + Virtual** | Terminal, Oficina e Admin: colunas fixas, agrupamento e linhas virtualizadas (100 mil linhas); telemetria bruta |
| **Form** | Wizard do Simulador e do Brief com campos dinâmicos, validação assíncrona, **autosave** e retomada em qualquer dispositivo |
| **Store** | Estado da cena (câmera, camada ativa, seleção) e **histórico para desfazer/refazer** do editor |
| **Pacer** | *Throttle* do fluxo cena → React (60 Hz na GPU, 4 Hz na UI), filas de gravação em lote |
| **DB (spike)** | Coleções reativas locais de telemetria recente para Cúpula offline |

## 5.5 Palco Persistente (*Stage*)

**Ideia:** um único `<canvas>` montado no *layout* raiz, **fora** do *outlet* do roteador. As rotas não criam cenas; elas **registram** uma cena e declaram o que querem do Palco. Resultado: o sol que abre a Landing é o mesmo que ilumina o seu telhado no Simulador e a sua Cúpula. Troca de rota vira **movimento de câmera**, não recarga.

**Contrato de cena:**

```ts
// packages/viz/stage/types.ts (ilustrativo)
export interface StageScene {
  id: 'alvorada' | 'atelie' | 'cupula' | 'aurora' | 'floresta' | 'atlas';
  /** carrega apenas o que a cena precisa (malhas, texturas, shaders) */
  load(ctx: StageContext, signal: AbortSignal): Promise<void>;
  /** transição de câmera e estado a partir da cena anterior */
  enter(from: StageScene | null, ctx: StageContext): Promise<void>;
  /** parâmetros reativos vindos da UI (hora, camada, seleção) */
  update(state: SceneState, dt: number): void;
  /** descarta recursos da GPU */
  dispose(): void;
  /** nível de fidelidade → custos */
  setQuality(tier: 0 | 1 | 2 | 3, dynamic: DynamicQuality): void;
  /** descrição textual equivalente (acessibilidade) */
  describe(state: SceneState): string;
}
```

**Regras do Palco:**
- **Renderização em Worker** (`OffscreenCanvas`) sempre que disponível; a UI mantém INP baixo.
- **Poster:** durante transições de rota e *view transitions*, o último *frame* vira imagem para evitar piscar.
- **Recuperação de perda de contexto** (GPU reset, aba em segundo plano) com restauração de estado.
- **Orçamento de memória:** alvo ≤ 250 MB de GPU em mobile; `dispose` obrigatório.
- **Pausa inteligente:** pausa fora da viewport, aba oculta, bateria baixa ou `prefers-reduced-motion`.
- **Fallback de camadas:** WebGPU → WebGL2 → imagem estática (poster do Motor de Luz).

## 5.6 Níveis de fidelidade (Tiers) e qualidade adaptativa

| Tier | Perfil de dispositivo | Entrega |
|---|---|---|
| **0** | Sem WebGL/WebGPU, `Save-Data`, `prefers-reduced-motion` forte, bateria crítica | Sem 3D: HTML, SVG e CSS; vídeo curto onde fizer sentido |
| **1** | Mobile modesto | 3D simplificado a 30 fps, sem pós-processamento, partículas ≤ 5 mil |
| **2** | Mobile bom / notebook comum | 3D completo (WebGL2), 60 fps, sombras suaves, partículas ≤ 50 mil |
| **3** | WebGPU + GPU capaz | *Compute shaders*, nuvens volumétricas, partículas em escala (≥ 500 mil), pós-processamento |

**Detecção:** `detect-gpu`, `navigator.gpu`, `deviceMemory`, `hardwareConcurrency`, `connection.saveData`, bateria, preferência do usuário e *benchmark* de 2 s em segundo plano.
**Qualidade dinâmica:** escala de resolução (DRS), número de partículas, resolução de sombra e passes de pós-processamento ajustam-se por FPS medido; **nunca** abaixo de 45 fps por mais de 2 s sem degradar.
**Controle manual:** "Efeitos: Automático / Reduzido / Completo".

## 5.7 Núcleo de energia (`energy-core`)

**Módulos:** posição solar; transposição de irradiância; temperatura e perdas (sujeira, cabos, *mismatch*, inversor, sombreamento); geração **P50/P90** (probabilística); degradação; tarifas e compensação (regras de **Lei 14.300** parametrizadas **como dados com vigência**, não como código); fatura e Cascata; ROI e fluxo de caixa; financiamento; rateio; piloto (simulação de deslocamento de cargas).

**Regras de engenharia:**
- **Funções puras e isomórficas** (cliente e servidor): a mesma conta dá o mesmo resultado em qualquer lugar.
- **Unidades tipadas** (kW, kWh, R$, graus), proibindo somar grandezas incompatíveis.
- **Versionamento semântico** do modelo; toda simulação guarda a versão que a gerou (`model_version`).
- **Testes de propriedade** (`fast-check`) e **conjuntos dourados** comparados com ferramentas de referência (ex.: PVGIS, pvlib) e com sistemas reais; meta de cobertura ≥ 95%.
- **Regulação como dados:** tabelas de tarifas, Fio B, bandeiras e vigências em formato versionado com revisão humana; mudança publicada em *changelog*.

```ts
// packages/energy-core/src/yield.ts (ilustrativo)
export interface YieldInput {
  geometry: RoofGeometry;          // faces, inclinação, azimute, obstáculos
  location: GeoPoint;
  tmy: HourlyWeatherSeries;        // irradiância e temperatura (multi-fonte)
  system: SystemSpec;              // módulos, strings, inversor, perdas
  uncertainty?: UncertaintyModel;
}

export interface YieldResult {
  annual: { p50: kWh; p90: kWh; p10: kWh };
  monthly: Array<{ month: number; p50: kWh; p90: kWh }>;
  hourlyProfile: Float32Array;     // para curva do dia
  assumptions: AssumptionRef[];    // apontam para /metodologia
  modelVersion: string;
}

export function estimateYield(input: YieldInput): YieldResult { /* … */ }
```

## 5.8 Geoespacial e insolação

**Pipeline do telhado:** endereço → geocodificação → footprint (fontes abertas e provedores de cobertura 3D) → segmentação das águas (modelo de visão + regras geométricas) → edição pelo usuário → malha do telhado + entorno (prédios, árvores como volumes) → **insolação anual**.
**Cálculo:** 145 segmentos de céu × posições solares do ano; *ray casting* na GPU contra BVH; resultado por célula de 0,25 m; agregação por água e por módulo; **fallback** em Worker/WASM; alvo < 2 s em Tier 3 e < 8 s em Tier 1.
**Precisão-alvo:** erro de insolação por água ≤ 5% vs referência (a validar em campo) e geometria com **Confiança** declarada.

## 5.9 Previsão e *nowcasting*

- **Física:** modelo de geração com condições previstas (irradiância, temperatura).
- **Nuvens:** vetores de movimento a partir de imagens de satélite geoestacionário (cadência de minutos) para 0–3 h; modelos numéricos de previsão para 3 h–7 dias.
- **Resíduo por ML:** corrige viés específico de cada telhado (sujeira, sombras locais) usando histórico real.
- **Métricas:** viés, MAPE e nRMSE por horizonte (15 min, 1 h, 6 h, 24 h, 7 d) e por tipo de dia (claro, parcial, nublado).
- **Governança:** registro de modelos, *backtests* contínuos, implantação em **sombra** antes de promover, monitor de deriva; resultados alimentam a página **Promessa vs Realidade**.

## 5.10 Integrações e ingestão

**Interface de adaptador (estável):**

```ts
// packages/integrations/types.ts (ilustrativo)
export interface InverterAdapter {
  id: string;                                // 'growatt' | 'huawei' | 'fronius' | …
  authenticate(params: AuthParams): Promise<Credentials>;
  discover(creds: Credentials): Promise<DeviceDescriptor[]>;
  readSnapshot(device: DeviceDescriptor): Promise<TelemetryPoint>;
  readHistory(device: DeviceDescriptor, range: TimeRange): AsyncIterable<TelemetryPoint>;
  capabilities(): { realtime: boolean; perString: boolean; control: boolean };
  health(): Promise<AdapterHealth>;
}
```

**Fluxo:** adaptador → fila → normalização (unidades, fuso, *clamps* e tratamento de lacunas) → Timescale (*hypertable*) → agregados contínuos (5 min, hora, dia) → SSE para a Cúpula.
**Resiliência:** limites de taxa por fabricante, *backoff*, *circuit breaker*, *backfill* automático após falhas, importação manual por CSV como rota de escape, *health* público por integração (página `/status`).
**Segredos:** credenciais em cofre com criptografia de envelope e escopo mínimo (OAuth quando existir).
**Prioridade inicial:** as 3 marcas mais presentes na base de instaladores parceiros (decisão de dados na M0).

## 5.11 Tempo real
Canais SSE por usuário/sistema/arena/vila; *fan-out* com Redis ou equivalente; *backpressure* e coalescência (um valor por intervalo); reconexão com `Last-Event-ID`; degradação para polling; modo offline lê do cache local e marca "dados de há X min".

## 5.12 Estrutura do monorepo

```
helio/
├─ apps/
│  ├─ web/                  TanStack Start (rotas, server functions, PWA)
│  ├─ workers/              OCR, ingestão, relatórios, e-mails, vídeo do Ano Solar
│  └─ forecast/             Serviço de previsão (Python)
├─ packages/
│  ├─ ui/                   Design system Fotônica (tokens, componentes)
│  ├─ stage/                Palco Persistente, cenas, shaders (TSL/WGSL)
│  ├─ viz/                  Gráficos (SunDial, EnergyRiver, Waterfall…)
│  ├─ energy-core/          Núcleo de energia (puro, testado)
│  ├─ integrations/         Adaptadores (inversores, casa inteligente, fontes)
│  ├─ ai/                   Ferramentas, avaliações, componentes generativos
│  ├─ db/                   Schema, migrações, seeds
│  ├─ content/              MDX da Biblioteca, glossário
│  └─ config/               TS, ESLint, tokens, presets
├─ labs/
│  └─ scene-lab/            Playground de shaders e cenas (Storybook de Mundos)
└─ infra/                   IaC, CI/CD, observabilidade
```

## 5.13 Exemplo: rota que une estado, dados e cena

```tsx
// apps/web/src/routes/simular.resultado.$id.tsx (ilustrativo; sintaxe pode variar por versão)
export const Route = createFileRoute('/simular/resultado/$id')({
  validateSearch: zodValidator(resultSearchSchema),     // t, cenário, premissas
  loader: ({ context, params }) =>
    context.queryClient.ensureQueryData(simulationQuery(params.id)),
  head: ({ loaderData }) => ({ meta: buildOgMeta(loaderData) }),
  component: ResultPage,
});

function ResultPage() {
  const { id } = Route.useParams();
  const { t, scenario } = Route.useSearch();
  const { data } = useSuspenseQuery(simulationQuery(id));

  // a cena é do Palco; a rota só declara o que quer
  useStage({ scene: 'atelie', focus: 'roof', time: t, heat: 'annual' });

  return <ResultLayout data={data} scenario={scenario} />;
}
```

---

# PARTE 6 — DADOS, IA, SEGURANÇA E QUALIDADE

## 6.1 Modelo de dados (núcleo)

| Entidade | Campos-chave | Relações / notas |
|---|---|---|
| `users` | id, nome, contato, perfil, **modo de experiência**, preferências de movimento/som | 1—N `properties` |
| `properties` | endereço, geometria (PostGIS), tipologia, distribuidora | 1—N `consumer_units`, `roofs` |
| `consumer_units` (UC) | número, grupo/subgrupo tarifário, modalidade (convencional/branca) | N—N `communities` |
| `roofs` | polígono, faces (inclinação, azimute), obstáculos, **confiança da geometria**, origem (auto/manual/captura) | 1—N `simulations` |
| `simulations` | inputs, premissas, resultado (P10/P50/P90), `model_version` | 1—N `audits`, `briefs` |
| `bills` | arquivo, campos extraídos, confiança por campo, status de conferência | N—1 `consumer_units` |
| `proposal_audits` | arquivo, campos extraídos, fatores e pontuação, versão do modelo | N—1 `users`; **não nomeia instalador publicamente** |
| `installers` | empresa, áreas H3, documentos, selos, métricas verificadas | 1—N `bids`, `projects` |
| `briefs` / `arenas` | escopo padronizado, fases, convidados, regras | 1—N `bids` |
| `bids` | preço, itens, prazo, garantia, geração P50 prometida, flags | N—1 `arenas`, `installers` |
| `promises` (**registro selado**) | proposta, geração prometida, `hash`, carimbo de tempo | base de Promessa vs Realidade e Garantia |
| `projects` | etapas, datas, garantias, documentos | liga proposta a sistema |
| `systems` | kWp, módulos, inversores, data de ativação | 1—N `devices` |
| `devices` | fabricante, modelo, credenciais (cifradas), capacidades, saúde | 1—N `telemetry` |
| `telemetry` (*hypertable*) | device_id, ts, potência, energia, tensão, temperatura | agregados contínuos |
| `pilot_rules` / `pilot_actions` | cargas, janelas, conforto, limites; ações com auditoria | reversíveis |
| `credits_ledger` (**append-only**) | UC origem/destino, kWh, validade, motivo | auditável |
| `communities` / `memberships` / `votes` | tipo, regras de rateio, quórum, resultados | trilha imutável |
| `achievements` / `goals` | tipo, progresso | N—1 `users` |
| `conversations` / `messages` / `memory_items` | contexto, ferramentas usadas, fontes, memória editável | N—1 `users` |
| `reviews` | nota, texto, vínculo de projeto verificado | N—1 `installers` |
| `forecast_runs` / `accuracy_daily` | modelo, horizonte, previsto, real, erro | alimentam a página pública |
| `audit_log` | ator, ação, alvo, ts, IP | transversal |

**Selagem de promessas e livro-razão (exemplo):**

```sql
-- promessas seladas: imutáveis após inserção
CREATE TABLE promises (
  id            uuid PRIMARY KEY,
  proposal_id   uuid NOT NULL,
  installer_id  uuid NOT NULL,
  yield_p50_kwh numeric NOT NULL,
  model_version text    NOT NULL,
  payload_hash  bytea   NOT NULL,           -- hash do conteúdo completo
  sealed_at     timestamptz NOT NULL DEFAULT now()
);
REVOKE UPDATE, DELETE ON promises FROM app_role;   -- apenas INSERT/SELECT

-- livro-razão de créditos: somente anexar
CREATE TABLE credits_ledger (
  id          bigserial PRIMARY KEY,
  from_uc     uuid, to_uc uuid NOT NULL,
  kwh         numeric NOT NULL CHECK (kwh > 0),
  valid_until date    NOT NULL,
  reason      text    NOT NULL,
  prev_hash   bytea,  entry_hash bytea NOT NULL,  -- encadeamento verificável
  created_at  timestamptz NOT NULL DEFAULT now()
);
```

## 6.2 Inteligência artificial

| Capacidade | Papel da IA | Quem calcula os números | Controles |
|---|---|---|---|
| **Extração de fatura e proposta** | Modelo multimodal lê PDF, foto e *print* e devolve campos estruturados | Validação por regras (somas, faixas, coerência) | Confiança por campo; conferência humana quando baixa |
| **Copiloto Hélio** | Conversa, explica, recomenda, redige relatórios | **Ferramentas determinísticas** (`energy-core`, telemetria) | Citação de origem, "ver como calculei", ações com confirmação |
| **UI generativa** | Escolhe componentes e parâmetros | Componentes só da lista branca; props validadas por schema | Nunca HTML arbitrário |
| **Diagnóstico por foto** | Lê código de erro e contexto do inversor | Base de conhecimento verificada por engenheiros | Escalonamento a humano |
| **Detecção de anomalias** | Explica em texto o que um modelo estatístico detectou | Modelo estatístico (esperado ajustado ao clima) | Limiar configurável; falso positivo reportável |
| **Coerência de propostas** | Resume divergências | Comparação com distribuição do modelo | Sinal, não veredito; direito de contestação |
| **Segmentação de telhado** | Modelo de visão propõe contornos | Geometria sempre editável pelo usuário | Confiança declarada |

**Contrato de UI generativa (exemplo):**

```ts
// packages/ai/ui-registry.ts (ilustrativo)
export const registry = {
  show_chart:  { schema: ChartSpec,  component: ChartBlock },
  show_table:  { schema: TableSpec,  component: TableBlock },
  show_action: { schema: ActionSpec, component: ActionCard },  // exige confirmação
  show_number: { schema: NumberSpec, component: KeyNumber },
} as const;
// O modelo emite tool calls; o servidor valida com o schema e o cliente
// renderiza apenas componentes deste registro.
```

**Avaliação contínua:**
- **Conjunto dourado** de perguntas reais anonimizadas e faturas/propostas reais (com consentimento).
- Metas: extração ≥ 98% em campos críticos; alucinação numérica ≈ 0 (qualquer número em resposta deve ter origem em ferramenta); recusa correta em temas jurídicos/financeiros definitivos.
- Revisão humana amostral semanal; *red teaming* de *prompt injection* via documentos.

**Custo:** orçamento por usuário/mês; cache de respostas determinísticas; roteamento por tarefa (modelos menores para classificação e extração simples); limite de contexto; processamento em lote fora do horário de pico.

## 6.3 Privacidade (LGPD) e ética de dados

- **Base legal por finalidade**, consentimento granular e revogável, DPO nomeado, RIPD (relatório de impacto) antes de cada recurso novo que trate dados pessoais.
- **Minimização:** fatura e proposta guardam o necessário; CPF e endereço mascarados; arquivos originais apagados em 30 dias por padrão.
- **Central de Privacidade:** exportar tudo em formato aberto, apagar a conta, ver **quem acessou** (instalador, suporte, parceiro) e quando.
- **Dados agregados:** apenas anonimizados com **k-anonimato (k ≥ 20)**; opt-out disponível; política pública.
- **Instaladores** só veem dados pessoais **após** a escolha do cliente.
- **Dados de residência sensíveis** (rotinas de consumo): tratados como dados que revelam hábitos; acesso restrito, criptografia, retenção limitada.
- **IA:** dados do usuário não são usados para treinar modelos de terceiros; envio minimizado e contratual.

## 6.4 Segurança

- **Identidade:** *passkeys* (WebAuthn), MFA opcional, sessões curtas com rotação.
- **Aplicação:** CSP rígida, SRI, proteção CSRF, validação de entrada com schema em **todas** as *server functions*, *rate limiting*, proteção contra abuso de upload (tipo, tamanho, varredura).
- **Dados:** criptografia em trânsito e em repouso; credenciais de dispositivos com criptografia de envelope e escopo mínimo; segregação por tenant; registro de auditoria imutável para ações sensíveis.
- **Controle de dispositivos (Piloto):** autenticação de ponta a ponta, assinatura de comandos, **limites duros** de potência e janelas, lista de bloqueio, *fail-safe* local, desfazer.
- **IA:** isolamento de instruções do sistema, filtragem de saída, validação de *tool calls*, limites de ações por sessão.
- **Cadeia de suprimentos:** *lockfiles*, SBOM, revisão de dependências, varredura contínua.
- **Programa:** *pentest* antes de cada release (R2, R3) e antes de ativar o Piloto, divulgação responsável, plano de resposta a incidentes treinado (exercícios semestrais).

## 6.5 Requisitos não funcionais

**Performance (orçamentos):**

| Métrica | Alvo (p75, 4G móvel de referência) |
|---|---|
| LCP | ≤ 2,5 s (elemento: texto/HTML, não canvas) |
| INP | ≤ 200 ms |
| CLS | ≤ 0,1 (zero na transição 2D → 3D) |
| JS inicial (Landing) | ≤ 170 KB gzip |
| Cena 3D (carga tardia, Landing) | ≤ 600 KB gzip adicionais |
| Simulador (insolação) | < 2 s Tier 3 · < 8 s Tier 1 |
| FPS | ≥ 60 (Tier 2/3) · ≥ 30 (Tier 1); nunca < 45 por > 2 s sem degradar |
| Memória de GPU (mobile) | ≤ 250 MB |
| Primeiro token do Hélio | < 1,2 s |
| Latência da Cúpula (telemetria → tela) | < 10 s no p95 |

**Acessibilidade (WCAG 2.2 AA):** teclado completo; foco visível; leitor de tela (NVDA, VoiceOver, TalkBack); equivalentes textuais, sonoros e táteis de visuais; contraste em **todas** as fases do dia; alvo mínimo de toque 24 px (padrão 44 px; 56 px no Modo Simples); sem *flash*; respeito a `prefers-*`; **auditoria externa** antes do lançamento e a cada release maior; **testes com pessoas reais** (baixa visão, cegos, 60+).

**Confiabilidade:** SLO 99,9% para leitura da Cúpula; degradação graciosa quando integrações falham; recuperação de desastre com RPO ≤ 15 min e RTO ≤ 2 h; filas idempotentes.

**SEO:** SSR/streaming, `head` por rota, JSON-LD (Article, FAQ, LocalBusiness), sitemap dinâmico, OG por rota, páginas do Atlas apenas quando há dados originais suficientes.

**Internacionalização:** textos externalizados desde o início (ICU), formatos por locale; pt-BR primeiro.

## 6.6 Estratégia de qualidade e testes

| Camada | O que cobre | Ferramentas |
|---|---|---|
| **Unidade e propriedade** | `energy-core` (≥ 95%), regras regulatórias, rateio | Vitest, fast-check |
| **Golden data** | Comparação com ferramentas de referência e sistemas reais | Notebooks de validação versionados |
| **Contrato** | Adaptadores de inversor e de casa inteligente | Testes de contrato com *mocks* gravados + sandbox quando houver |
| **Componentes** | Cada componente do design system em todos os modos | Storybook, axe-core |
| **Visual** | Cenas 3D e UI nos temas Noite/Dia/Simples/Calmo e 4 breakpoints | Playwright + Chromatic; **cenas determinísticas** (semente fixa, tempo congelado, tolerância por *pixel diff*) |
| **E2E** | Fluxos críticos: Simulador, Auditoria, Arena, Piloto, Cúpula | Playwright |
| **Performance** | Web Vitals por rota; FPS por Tier; memória de GPU | Lighthouse CI + bancada própria em **laboratório de dispositivos reais** (Android modesto, iPhone, notebook de 2019) |
| **Acessibilidade** | Automática + roteiro manual com leitor de tela e teclado | axe-core, NVDA/VoiceOver/TalkBack |
| **Segurança** | SAST/DAST, dependências, *pentest* | Ferramentas padrão + externo |
| **IA** | Conjuntos dourados, *red teaming*, regressão de prompts | Suíte de avaliação própria |
| **Caos** | Falha de integrações, perda de contexto GPU, rede instável | Injeção de falhas |

**Definition of Done (global):** (1) Barra de Qualidade Visual cumprida (3.14); (2) funciona nos 3 níveis — sem 3D, Tier 1/2 e Tier 3 — com testes de *fallback*; (3) orçamentos de performance cumpridos nos dispositivos de referência; (4) zero violações críticas de acessibilidade; (5) todo número exibe faixa, premissas e fonte; (6) estados cobertos; (7) eventos de analytics e SLOs configurados; (8) revisão de privacidade e segurança concluída; (9) microcopy revisada pela voz.

## 6.7 Analytics, experimentação e métricas

**Estrela-guia (*North Star*):** **MWh de geração solar monitorada e otimizada por mês** (com o *guardrail* de **erro de previsão** público).

**Estrutura HEART:**

| Dimensão | Métrica |
|---|---|
| **Happiness** | NPS geral e por ato; CSAT da Auditoria e da Arena |
| **Engagement** | Sessões/semana na Cúpula; uso do Hélio; abertura do Boletim |
| **Adoption** | Conclusão do Simulador; propostas auditadas; sistemas conectados |
| **Retention** | D7/D30 de Cúpula; retenção de Plus; churn de instaladores |
| **Task success** | Tempo até o 1º número crível; precisão da extração; economia atribuída ao Piloto |

**Taxonomia de eventos:** `objeto_ação` em português (ex.: `simulacao_concluida`, `auditoria_compartilhada`, `piloto_ativado`), com propriedades padronizadas (`tier`, `modo`, `fase_do_dia`, `versao_modelo`) e **sem PII**.
**Experimentação:** *feature flags* e testes A/B com guarda-corpos; **claims de economia não são testados sem revisão**; *holdouts* para medir o impacto real da camada visual (versão leve vs completa) em conversão e retenção.
**Privacidade:** analytics próprio ou *self-hosted*, sem cookies de terceiros por padrão.

---

# PARTE 7 — NEGÓCIO, CRESCIMENTO, ROADMAP E RISCOS

## 7.1 Modelo de negócio

**Princípio:** receita atrelada a **valor entregue**, nunca a posição comprada nem a escassez artificial.

| Fonte | Quem paga | Quando | Observação |
|---|---|---|---|
| **HELIO Plus** (assinatura) | Usuário | Mensal/anual | Piloto Automático completo, Hélio ilimitado, múltiplos imóveis, relatórios, Passaporte, Modo Parede avançado |
| **Taxa de sucesso da Arena** | Instalador | Só se o projeto fecha | Cliente nunca paga; taxa explícita e pública |
| **Plano Instalador Pro** | Instalador | Mensal | Editor 3D, Kit de Homologação, propostas ilimitadas, analytics, equipe |
| **Garantia de Geração** | Embutida no contrato (instalador/seguradora) | Na venda | Cobre geração abaixo do P90 prometido; paga quem entrega |
| **Comissão de crédito** | Parceiro financeiro | Na contratação | Divulgada ao usuário; ranking de linhas **não** é influenciado |
| **B2B Condomínios e PMEs** | Condomínio/empresa | Mensal | Gestão de usina compartilhada, relatórios, múltiplas unidades |
| **Revisão técnica humana** | Usuário | Avulso | Engenheiro revisa um projeto |
| **Dados agregados** | Terceiros (pesquisa, setor público) | Contrato | **Somente** anonimizados (k ≥ 20), opt-out e política pública |

**Regras éticas de receita:** ranking de instaladores é calculado por desempenho verificado; pagar **nunca** altera nota, selo ou ordem; parceiros financeiros são identificados; nenhuma venda de dados pessoais.

## 7.2 Preços e economia unitária (hipóteses para testar)

| Item | Hipótese inicial | Como validar |
|---|---|---|
| Plus (usuário) | R$ 19 a R$ 39 por mês; se paga com a economia do Piloto | Teste de preço por segmento; **calculadora de retorno** visível |
| Taxa de sucesso da Arena | 1,5% a 3% do valor do projeto | Pesquisa com instaladores; comparação com custo de aquisição atual deles |
| Plano Pro do instalador | R$ 299 a R$ 899 por mês | Testes com 20 instaladores-piloto |
| Custo de IA por usuário ativo | ≤ R$ 2 por mês (meta) | Medição desde a M0 com orçamento por usuário |
| Custo de renderização/armazenamento | ≤ R$ 1 por usuário ativo/mês (meta) | Monitoramento de FinOps |
| Taxa de conversão Auditoria → Arena | 15% a 25% | A/B no relatório |
| Retenção de Plus (12 meses) | ≥ 65% | Coortes |

> Todos os números desta seção são **hipóteses**; nenhum é compromisso.

## 7.3 Crescimento: seis ciclos que se alimentam

| # | Ciclo | Como funciona | Métrica de saúde |
|---|---|---|---|
| 1 | **Auditoria viral** | Quem recebeu proposta audita; o relatório (mascarado) é compartilhado com o cônjuge, amigos, grupos de bairro; cada compartilhamento traz novos auditados | Compartilhamentos por relatório; K-factor |
| 2 | **Atlas SEO** | Páginas municipais com dados originais respondem "quanto rende solar em [cidade]?"; levam ao Simulador | Tráfego orgânico qualificado; conversão |
| 3 | **Seu Ano Solar** | Retrospectiva anual compartilhada por usuários traz curiosos | Compartilhamentos; novos usuários |
| 4 | **Mutirão** | Vizinhos convidam vizinhos para ganhar desconto por volume | Convites aceitos; tamanho médio do lote |
| 5 | **Passaporte do Sistema** | Compradores de imóveis com sistema veem o selo HELIO e criam conta | Passaportes visualizados; novos usuários |
| 6 | **Indicação transparente** | Recompensas claras, sem multinível, só por projeto concluído | CAC por indicação |

**Canais complementares:** parcerias com cooperativas, associações de moradores e condomínios (B2B2C); mídia ganha com os dados do Atlas e da **Promessa vs Realidade**; criadores de conteúdo técnico; WhatsApp como canal de retenção.

**Entrada em mercado:** começar em **uma cidade-piloto** com alta irradiação e mercado maduro de GD (a escolher na M0 por dados de adoção, oferta de instaladores e distribuidora), depois **três regiões** e então escala nacional. Critérios de expansão: densidade mínima de instaladores verificados, cobertura de dados de telhado, acordos de dados com a distribuidora.

## 7.4 Parcerias e regulatório

| Frente | Ação | Dono |
|---|---|---|
| **Distribuidoras** | Acordos de dados/integração para Rastreio de Obra | Parcerias + Regulatório |
| **Fabricantes de inversor** | Acordos de API e suporte | Engenharia + Parcerias |
| **Financeiras** | Linhas verdes, CET transparente, contratos | Parcerias + Jurídico |
| **Seguradora** | Estrutura da Garantia de Geração | Jurídico + Atuária |
| **Energia compartilhada** | Parceiros regulados (usinas, cooperativas, consórcios) | Regulatório |
| **Jurídico/LGPD** | Revisão de claims, Termos, privacidade, minutas de Vila/Condomínio | Jurídico |
| **Mercado livre de energia** | Acompanhar abertura gradual a consumidores de baixa tensão e avaliar produto futuro | Estratégia |

## 7.5 Roadmap

### Fase M0 — Fundação e *spikes* (semanas 1–6)
**Objetivo:** reduzir os maiores riscos técnicos e de produto *antes* de construir.

| Spike | Pergunta | Critério de saída |
|---|---|---|
| S1 | Palco Persistente em Worker (WebGPU + WebGL2) com View Transitions funciona bem em Android modesto? | ≥ 45 fps Tier 1; sem CLS; troca de rota < 400 ms |
| S2 | Insolação anual em GPU atinge precisão e tempo alvos? | Erro ≤ 5% vs referência; < 2 s Tier 3 · < 8 s Tier 1 |
| S3 | Extração de fatura e proposta | ≥ 98% em campos críticos num conjunto real de 200 documentos |
| S4 | Adaptadores de 3 marcas de inversor | Leitura + histórico + saúde estáveis em sandbox/campo |
| S5 | TanStack Start (RC) com SSR em *streaming* e hospedagem com baixa latência no Brasil | Latência p75 e custo dentro do alvo; plano B definido |
| S6 | *Nowcasting* baseline | Superar persistência em 0–3 h por margem definida |
| S7 | Piloto com tomadas inteligentes e carregador em laboratório | Zero falhas de segurança; reversão < 3 s |
| S8 | Pesquisa: 20 entrevistas + teste de protótipo da Cúpula e da Auditoria | ≥ 70% entendem a proposta de valor em 30 s |

**Entregas:** monorepo, CI/CD, design system v0 (tokens, tipografia, Motor de Luz, 10 componentes), protótipo navegável da Landing e do Simulador (passos 1–3), medição de custos.

### R1 — **Nascer** (meses 2–6): Descobrir + base de Decidir
**Entregas:** F-101, F-102, F-103, F-104 (base), F-106, F-201, F-207 (básico), F-601, F-602, F-603, F-604, F-606, F-608.
**Critérios de saída:** conclusão do Simulador ≥ 30%; precisão de extração ≥ 98%; Web Vitals nos orçamentos; zero bloqueadores de acessibilidade; 5 mil simulações; 1.500 propostas auditadas.

### R2 — **Zênite** (meses 7–11): Viver + Instalar
**Entregas:** F-107, F-202, F-203 (beta), F-204, F-205, F-209, F-301, F-302, F-303, F-401, F-402, F-403, F-404 (básico), F-405, F-406, F-408, F-409, F-410, F-411, F-414, F-506, F-605, F-607, F-609.
**Critérios de saída:** 2 mil sistemas conectados; retorno D30 ≥ 45% na Cúpula; **erro de previsão (24 h) dentro da meta e publicado**; Piloto em Modo Sombra para 500 casas; NPS ≥ 50; 30 instaladores verificados.

### R3 — **Crepúsculo** (meses 12–17): Compartilhar + Arena completa
**Entregas:** F-105, F-203 (completa), F-206, F-208, F-304, F-404 (completo), F-407, F-412, F-413, F-501, F-503, F-504, F-505, F-507.
**Critérios de saída:** 10 mil sistemas conectados; 30 comunidades ativas; 15% das propostas via Arena; Garantia de Geração em piloto; primeira edição do **Seu Ano Solar**.

### R4 — **Aurora** (meses 18+): Escala e fronteira
**Entregas:** F-502 (cotas solares), F-610 (i18n), API pública, **AR/WebXR** de painéis no telhado, editor 3D multiusuário, Modo Campo (agro), produtos B2B.
**Critérios de saída:** parcerias reguladas assinadas; 50 mil sistemas; API com parceiros externos.

### Equipe inicial sugerida (~17 pessoas)
Produto (1), Design lead (1), Designers de produto (2), Artista 3D/motion (1), *Creative technologists* de shader/cena (2), Front-end (3), Back-end (2), Dados/ML — previsão e extração (2), Engenheiro de IA (1), QA/SDET (1), Engenheiro eletricista especialista (1), Editor de conteúdo (0,5) e Jurídico/regulatório (0,5, parcial).

## 7.6 Riscos e mitigações

| Risco | Prob. | Impacto | Mitigação |
|---|---|---|---|
| A experiência avançada pesa e exclui usuários de aparelhos modestos | Alta | Alto | Tiers, qualidade adaptativa, versão sem 3D completa, laboratório de dispositivos reais, **holdout** que mede o impacto real |
| Estimativas criam expectativa errada ou risco legal | Média | Alto | Faixas de incerteza, metodologia aberta, **precisão pública**, revisão jurídica de *claims*, calibração com dados reais |
| Mudanças regulatórias (Fio B, tarifas, mercado livre) | Alta | Médio | Regulação como **dados versionados**; monitoramento ativo; *changelog* público |
| Cobertura de telhado 3D insuficiente | Média | Médio | Captura Guiada, segmentação própria, desenho manual, parcerias |
| Integrações de inversor instáveis ou restritas | Alta | Alto | Adaptadores plugáveis, degradação graciosa, importação manual, parcerias diretas |
| Segurança do Piloto (controle de cargas) | Baixa | Muito alto | Consentimento por dispositivo, lista de bloqueio, *fail-safe*, limites duros, auditoria, *pentest*, **Modo Sombra** primeiro |
| Instaladores manipulam a Arena (conluio, *low-ball*) | Média | Alto | Padronização, monitoramento, sanções, reputação por desempenho, canal de denúncia |
| Auditoria de Proposta gera conflito com instaladores | Média | Médio | Relatório é sinal, não veredito; não nomeia publicamente; direito de contestação; linguagem revisada |
| Alucinação do Copiloto | Média | Alto | Números só por ferramentas; validação de saída; avaliações contínuas; "ver como calculei" |
| Vazamento de faturas/credenciais | Baixa | Muito alto | Minimização, criptografia, retenção curta, pentest, resposta a incidentes treinada |
| Complexidade técnica (WebGPU, mapas, IA, tempo real) | Alta | Médio | Spikes na M0, camadas progressivas, *ownership* claro, `scene-lab`, testes visuais determinísticos |
| Maturidade de partes do TanStack (Start RC, DB/AI beta, Store alfa) | Média | Médio | Travar versões, camadas de abstração, plano B (alternativas por peça), acompanhar *releases* |
| Custo de IA e renderização cresce mais que a receita | Média | Alto | Orçamento por usuário, cache, roteamento de modelos, FinOps desde a M0 |
| *Greenwashing* percebido na Floresta | Baixa | Médio | Metodologia pública, rótulo de estimativa, sem compensações simbólicas |
| Dependência de poucos provedores de dados (telhado, clima) | Média | Médio | Multi-fonte, cache, contratos, plano de substituição |

## 7.7 Questões em aberto (com dono e prazo sugeridos)

| # | Pergunta | Dono | Prazo |
|---|---|---|---|
| 1 | Qual provedor de dados de telhado dá melhor custo-benefício e cobertura 3D real nas cidades-piloto? | Dados + Engenharia | M0 |
| 2 | Quais 3 marcas de inversor priorizar (base dos instaladores parceiros)? | Produto + Parcerias | M0 |
| 3 | Estrutura jurídica recomendada para Vila e Condomínio (cooperativa, consórcio, condomínio) e responsabilidade da plataforma | Jurídico | antes de R3 |
| 4 | Estrutura da Garantia de Geração (seguradora, prêmio, exclusões) | Jurídico + Atuária | R2 |
| 5 | Referência de preço por Wp: como exibir sem enviesar nem permitir manipulação? | Dados + Produto | R2 |
| 6 | Qual nível de proatividade o usuário aceita do Hélio sem sentir vigilância? | Pesquisa + Design | R2 |
| 7 | Cidade-piloto e roteiro de expansão | Estratégia | M0 |
| 8 | Abrir o `energy-core` como código aberto (confiança e contribuição) | Engenharia + Jurídico | R2 |
| 9 | Hospedagem final (latência no Brasil, custo, SSE) | Engenharia | M0 (S5) |
| 10 | Direitos de uso e licenças de dados de satélite/irradiação em produto comercial | Jurídico + Dados | M0 |

## 7.8 Glossário

- **GD:** geração distribuída. **UC:** unidade consumidora. **kWp:** potência de pico instalada.
- **Fio B:** componente da tarifa de uso da rede cobrado, de forma gradual, sobre a energia injetada e compensada (Lei 14.300).
- **Compensação:** abatimento da energia injetada na rede do consumo posterior, em créditos.
- **P50 / P90:** geração que se espera superar em 50% / 90% dos anos.
- **Payback:** tempo para o investimento se pagar com a economia.
- **CET:** custo efetivo total de um financiamento.
- **Nowcasting:** previsão de curtíssimo prazo (minutos a poucas horas), baseada em observação.
- **Palco (Stage):** camada 3D persistente que atravessa as rotas.
- **Tier visual:** nível de fidelidade gráfica adaptado ao dispositivo.
- **TSL:** *Three Shading Language*, shaders portáveis entre WebGPU e WebGL.
- **k-anonimato:** garantia de que cada dado agregado representa pelo menos *k* indivíduos.
- **Modo Sombra:** simulação do Piloto Automático sem controle real de dispositivos.
- **Promessa Registrada:** geração prometida em proposta, selada com data e *hash*.

---

*Este PRD é um documento vivo e autônomo. Premissas numéricas (metas, preços, prazos, orçamentos) são hipóteses a calibrar com pesquisa, protótipos e dados reais; itens regulatórios, jurídicos e de integração devem ser validados com especialistas e parceiros antes de qualquer compromisso de escopo. O estado de maturidade de bibliotecas e navegadores citado reflete informações públicas de out/2026 e deve ser reconfirmado nos spikes da M0.*
