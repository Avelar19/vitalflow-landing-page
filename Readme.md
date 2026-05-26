# VitalFlow

VitalFlow e uma landing page responsiva para uma plataforma ficticia de telemetria medica em tempo real, voltada a UTIs, hospitais e clinicas. A pagina apresenta a proposta do produto, seus recursos principais, uma simulacao visual de dashboard clinico, planos comerciais e um formulario de contato para solicitacao de demonstracao.

## Itens implementados

Estrutura HTML semantica: foi criada uma pagina completa em `index.html` com cabecalho, navegacao principal, conteudo central, secoes tematicas e rodape. A estrutura usa tags semanticas como `header`, `nav`, `main`, `section`, `article`, `footer`, listas e rotulos acessiveis para organizar o conteudo de forma clara e facilitar leitura por navegadores, buscadores e tecnologias assistivas.

Navegacao fixa e responsiva: o topo da pagina contem a marca VitalFlow, links internos para as secoes principais e um botao de chamada para acao. Em telas menores, a navegacao se transforma em menu hamburguer controlado por JavaScript, com atualizacao de `aria-expanded` e fechamento automatico ao selecionar um link.

Hero com identidade do produto: a primeira secao apresenta o posicionamento do VitalFlow como solucao de monitoramento vital em tempo real, incluindo selo de certificacao, titulo principal, texto de apoio, botoes de acao e indicadores de desempenho. Tambem foi criada uma visualizacao animada de ECG em SVG para reforcar visualmente o contexto de telemetria medica.

Secao de funcionalidades: foram implementados seis cards para destacar telemetria multi-canal, alertas inteligentes, central de leitos, analise preditiva, integracao FHIR/HL7 e conformidade regulatoria. Cada card possui icone SVG, descricao objetiva e etiquetas com recursos ou padroes relacionados.

Dashboard demonstrativo em bento grid: foi criada uma area visual que simula um painel clinico com ECG ao vivo, SpO2, pressao arterial, temperatura, frequencia respiratoria, alertas recentes e score NEWS2. O layout usa CSS Grid para organizar informacoes densas de forma escaneavel e se adapta entre mobile, tablet e desktop.

Fluxo "Como Funciona": a pagina inclui uma secao em tres etapas explicando a jornada do dado clinico, desde a captura multi-sensor ate o processamento em tempo real e a entrega de alertas no dashboard. Essa parte ajuda a conectar a interface de marketing com o funcionamento tecnico proposto para a solucao.

Planos comerciais: foram adicionados tres planos, Starter, Pro e Enterprise, com precos, limites de leitos, recursos incluidos e chamadas para contratacao ou solicitacao de proposta. O plano Pro recebe destaque visual para indicar a opcao principal da oferta.

Formulario de contato: a secao final permite solicitar uma demonstracao gratuita com campos de nome, e-mail institucional, instituicao e numero de leitos. O formulario usa validacao HTML nativa, atributos de autocomplete, mensagem de protecao de dados pela LGPD e um comportamento simples em JavaScript para confirmar o envio demonstrativo.

Rodape institucional: foi implementado um rodape com marca, frase de apoio, selos de certificacao e links de navegacao para produto, empresa e suporte. Ele fecha a experiencia mantendo consistencia visual com o restante da pagina.

Design system em CSS: o arquivo `style.css` define tokens de cor, tipografia, espacamento, raios, sombras, transicoes e estados. Essa base centralizada facilita ajustes futuros e mantem consistencia entre botoes, cards, formularios, navegacao e secoes.

Modo escuro automatico: foi adicionado suporte a `prefers-color-scheme: dark`, alterando cores de fundo, textos, bordas e sombras quando o usuario utiliza o sistema em modo escuro. A implementacao reaproveita as mesmas variaveis CSS, evitando duplicacao de regras visuais.

Responsividade mobile first: o layout foi construido inicialmente para telas pequenas e depois expandido com media queries para tablet, desktop e telas largas. Foram ajustados grids, menu, hero, cards, planos, formulario e rodape para manter leitura e usabilidade em diferentes tamanhos de tela.

Microinteracoes e animacoes: foram implementados efeitos de hover, transicoes suaves, entrada progressiva de elementos com Intersection Observer, animacoes de ECG, pulso, onda respiratoria, preenchimento circular de SpO2 e movimento do termometro. Tambem existe suporte a `prefers-reduced-motion` para reduzir animacoes quando essa preferencia esta ativa.

Acessibilidade: a pagina inclui link para pular ao conteudo principal, foco visivel, rotulos ARIA em regioes importantes, descricoes em botoes e formularios, uso de `aria-hidden` em elementos decorativos e estrutura de titulos por secao. Esses cuidados melhoram a navegacao por teclado e por leitores de tela.

Curadoria de codigo com IA: ferramentas de inteligencia artificial generativa foram utilizadas como apoio para planejar, revisar e refinar a estrutura da landing page, especialmente na organizacao semantica, na documentacao dos itens implementados e em pequenos ajustes de interface. O codigo final foi curado manualmente para manter coerencia visual, responsividade, acessibilidade e aderencia aos criterios do projeto.

## Como executar

Abra o arquivo `index.html` diretamente no navegador. Como o projeto usa apenas HTML, CSS e JavaScript nativo, nao ha necessidade de instalar dependencias ou iniciar servidor local.
