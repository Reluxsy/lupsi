# Projeto de Landing Page para profissional de Psicanálise

Página com fundo na cor #fbfaf7 e fonte Montserrat como principal.
Utilize o padrão mobile first, com breakpoints para celular e tablet
Objetivo é ter uma landing page clean, acolhedora e sofisticada.

## Seção HEADER:

Logo no canto esquerdo
- A logo é o arquivo /assets/img/logotipo-lusinele-psicanalista.svg

Menu no canto direito
- no mobile será utilizado o menu hamburger que está  em /assets/img/menu.svg
- quado clicar no icone de  hamburger, deverá aparecer um menu lateral, com os textos um abaixo do outro.
- o menu é composto pelos textos (links) : Início, Sobre, abordagem, histórias, Atendimentos, Contato
- Cor dos textos #4e4947, e quando passar o mouse  a cor #B8860B.
- No desktop o menu ficará um ao lado do outro.


## Seção HERO:

Imagem no canto direito
- a imagem é o arquivo /assets/img/lusineleferraz-psicanalista.png

Título, texto descritivo e botão do lado direito.
- o cabeçalho da seção Hero terá a font-size de 1rem, a cor é #b8860b
- o título principal terá o H1 com as seguintes configurações:
    font-family: 'Playfair Display', serif, font-size 1.55rem, com a cor #4e4947
- a profissional Lusinele Ferraz tera seu texto destacado, na cor #b8860b, um font-size de 1.25rem, e a font-family 'Montserrat', sans-serif.
-  botão na cor #806090, com bordas arredondadas, o texto na cor branca, font-size 13.5px e font-family 'Montserrat', sans-serif.

## Seção HELP:

Está seção terá 1 título, 1 subtítulo e 6 cards

- Título: Como posso caminhar ao seu lado?
- Subtítulo: Por trás do sofrimento que se repete, existe uma história que merece ser escutada.
- Título e subtítulo centralizado, fonte em negrito na cor #4e4947 e font-family Playfair Display
- o título terá o tamanho da fonte de 38px e o subtítulo 23px para desktop

Os cards terá 1 icone, 1 título e uma descrição de 2 parágrafos, referente ao título, na qual quem leia, tenha uma interpretação de um texto acolhedor e confortante, que prenda sua ateção.

- os cards terão os seguintes títulos: ANSIEDADE, SOLIDÃO, LUTO, DEPENDÊNCIA EMOCIONAL, RELACIONAMENTOS ABUSIVOS, BAIXA AUTOESTIMA.
- todos os icones tem o mesmo nome dos títulos e os arquivos estão na pasta \assets\img\icon

- Os títulos e subtítulos dos cards terão a font-family Playfair
- na versão para desktop, coloque 3 cards por linha
- os cards terão bordas levemente arredondadas, com um borda superior na cor #b8860b, e uma leve sombra ao redor.  
- Quando o mouse entrar em qualquer área do card, quero que ele de a impressão de vir para frente,a sobra fique um pouco mais forte, a cor do card de uma leve escurecida, e o título fique na cor #b8860b.

## Seção TRANSFORMATIONS

Está seção terá 1 título, 1 texto descritivo, 1 imagem, 4 cards e 1 Botão.

Título e texto descritivo.

Título: Pequenas compreensões, grandes mudanças
Texto descritivo: O processo terapêutico cria um espaço para reflexão e escuta. Com o tempo, aquilo que antes parecia confuso ganha novos significados, permitindo uma relação mais leve com suas emoções, decisões e vínculos.
Configurações:
- usará a font-family: 'Playfair Display', color #4e4947
- o título principal terá font-size 1.55rem 
- O texto descritivo ficará logo abaixo do Título 

Imagem e 4 cards abaixo do texto desritivo

- a imagem, usar o arquivo /assets/img/ambiente-relaxante-terapia-autocuidado.webp e ficará do lado esquerdo.

- cards: Os quatro cards dispostos um embaixo do outro ocupando toda linha. 
Cada card deve conter:
Um título curto 
Um breve texto descritivo.
terão bordas levemente arredondadas, com um borda esquerda na cor #b8860b, e uma leve sombra ao redor. 

- titulos e texto descritivo dos cards

Título: Protagonismo na Vida 
Texto descritivo: Desenvolva a autonomia para ser protagonista da sua própria história. Na terapia, você conquista a clareza necessária para tomar decisões mais alinhadas com quem você é e com o futuro que deseja construir.

Título: Vínculos Autênticos
Texto descritivo: Cultive laços mais profundos e verdadeiros. O processo terapêutico ajuda a transformar a maneira como você se conecta com os outros, tornando suas relações mais maduras, saudáveis e autênticas.

Título: Clareza Emocional
Texto descritivo: Amplie o olhar sobre si mesmo. Ao compreender as raízes das suas emoções e os conflitos internos que muitas vezes agem no silêncio, você ganha ferramentas poderosas para lidar com seus desafios diários.

Título: Equilíbrio e Bem-Estar
Texto descritivo: Encontre leveza no seu dia a dia. Ao dar novo sentido aos traumas e padrões que se repetem, o peso emocional diminui, tornando sua jornada mais tolerável, compreensível e serena.

- Botão
-  botão na cor #806090, com bordas arredondadas, o texto na cor branca, font-size 13.5px e font-family 'Montserrat', sans-serif.
- usar o mesmo padrão de hover do botão da seção Hero.
- texto do botão: iniciar meu processo

## Seção HOW-IT-WORKS

Está seção terá o nome descritivo da seção, 1 título, 1 texto descritivo e lista de 3 etapas com uma estrutura de 'timeline' (linha do tempo) vertical.

A descrição da seção ficará no canto esquerdo
O Título, o texto descritivo e a lista centralizada.
os títulos e os textos descritivo da lista iniciam do lado esquero dos cards.

Quando não for especificado, use os mesmos padrões de fonte, espaçamentos e demais configurações usadas nas outras seções que já foram criadas.

- Descritivo da seçao

    Nome: COMO FUNCIONA 
    características:
    posicionado no canto esquerdo
    color: var(--accent);
    font-size: 1rem;
    font-weight: 700;
    letter-spacing: 0.08em;


- Título e texto descritivo

    Use as mesmas características do título e texto descritivo usado na seção TRANSFORMATIONS.

    Título: Entenda o processo em 3 passos
    Texto descritivo: Atendimento por videochamada, em um ambiente reservado e acolhedor, para que você saiba exatamente como funciona antes de começar.

- lista de 3 etapas

    a lista terá 1 título e 1 texto descritivo

    1 - Primeiro contato
        Você entra em contato via WhatsApp e compartilha brevemente sua necessidade, contexto e disponibilidade.

    2 - Conversa inicial
        É feita uma conversa para entender seu momento, alinhar expectativas e definir o melhor caminho.

    3 - Início do acompanhamento
        Com tudo alinhado, o acompanhamento começa de forma prática, respeitando seu ritmo e sua rotina.

    Características

        Título:
        font-family: "Playfair Display", serif
        font-size: 1.35rem
        line-height: 1.2

        Texto descritivo:
        font-size: 0.95rem
        line-height: 1.7

        Cada item deve ser um card com sombra suave, cantos arredondados e um ícone ou número em destaque.
        Animação: Adicione um efeito de animação suave (fade-in com leve movimento de subida) para que os elementos apareçam conforme o usuário rola a página. Utilize a API 'Intersection Observer' via JavaScript para controlar essa entrada de forma performática.

## Seção about-me

Está seção terá o nome descritivo da seção, 1 título, 1 subtítulo, 1 texto descritivo, 1 lista e uma imagem.

A seção será divido em 2 colunas, usando grid, de um lado a imagem e do outro os textos.

A descrição da seção ficará no canto esquerdo, acima e fora da configuração do Grid, usando o mesmo padrão da seção HOW-IT-WORKS

Quando não for especificado, use os mesmos padrões de fonte, espaçamentos e demais configurações usadas nas outras seções que já foram criadas.

O Título, o subtítulo, o texto descritivo e a lista, ficaram do lado esquerdo e iniciando na margem esquerda.

A imagem ficara no lado direito.

a imagem utilizada está em  /assets/img/psicanalista-atendimento-psicanalitico.webp

- Descritivo da seçao

    Nome: SOBRE MIM
    características:
    posicionado no canto esquerdo
    color: var(--accent);
    font-size: 1rem;
    font-weight: 700;
    letter-spacing: 0.08em;

- Título, subtítulo e texto descrito e lista
    
    Use as mesmas características do título e texto descritivo usado nas seções já criadas.
    O subtítulo, pode ter um font-size um pouco menos que o título e um pouco maior que o texto descritivo. 

    Título: Lusinele Ferraz da Silva
    Subtítulo: Psicanalista Clínica e Contoterapeuta | CBPC 2022-5973
 
    Texto descritivo: Sou Psicanalista Clínica e Contoterapeuta, formação continuada em Neurociências, Mediação Judicial.

    Atuo com escuta ética e acolhedora, dedicada ao desenvolvimento humano e ao cuidado emocional.

    Lista:
    
    1 - Contoterapia – NPI 

    2 - Psicanálise – NPI 

    3 - Recuperação Emocional por Estratégias Terapêuticas

    4 - Pós-graduação em Neurociências – CM 

    5 - Escuta psicanalítica e acolhimento emocional

    6 - Manejo Clínico para Vítimas de Manipulação Psicológica (Gaslighting)

    7 - Expositora de Oficinas de Comunicação Não Violenta (CNV) – Tribunal de Justiça do RJ

    8 - Atuação voluntária em escuta ativa e acolhimento emocional em grupo de convivência

    9 - Facilitadora da justiça restaurativa - Tribunal de Justiça do RJ

    Na lista em vez de colocar números, opte por colocar o Check

- Animação: 
    Adicione um efeito de animação suave o mesmo utilizado na seção HOW-IT-WORKS


## Seção FAQ

Está seção terá o nome descritivo da seção, 1 título, 1 texto descritivo, 1 botão, 1 lista de perguntas e respostas.

A seção será divido em 2 colunas, usando grid. De um lado o título, subtítulo e botão e do outro as listas de perguntas e respostas.

A descrição da seção ficará no canto esquerdo, acima e fora da configuração do Grid, usando o mesmo padrão da seção about-me.

Quando não for especificado, use os mesmos padrões de fonte, espaçamentos e demais configurações usadas nas outras seções que já foram criadas.

O Título, o texto descritivo e o botão, devem ficar no lado esquerdo.

A lista de perguntas e respostas do lado direito.

Use elementos semânticos. Utilize <details> e <summary> para o efeito de expansão/colapso das perguntas, pois isso é excelente para acessibilidade e SEO.

Garanta que o estilo visual separe claramente a pergunta da resposta quando aberta.

- Descritivo da seçao

    Nome: FAQ
    características:
    posicionado no canto esquerdo
    color: var(--accent);
    font-size: 1rem;
    font-weight: 700;
    letter-spacing: 0.08em;

- Título, texto descrito e Botão.
    Use as mesmas características do título e texto descritivo usado nas seções já criadas.
    
    Título: DÚVIDAS FREQUENTES
    O título deve ficar em duas linhas.

    Texto descritivo: Se restou alguma dúvida, este espaço é para você.  Aqui você encontra respostas objetivas sobre o processo terapêutico, formato das sessões e agendamento.

    Botão: AGENDAR MINHA PRIMEIRA SESSÃO
    Coloque o icone do whatsapp no canto esquerdo.
    icone do whatsapp /assets/img/icon/whatsapp.png
    Utiliza os mesmos padrões dos botôes já criados
    link do botão: https://wa.me/5521980325956?text=Olá, vim pelo site e gostaria de conversar sobre o atendimento.

Lista de perguntas e respostas.

    Pergunta: Como funciona a psicoterapia online?
    Resposta: A psicoterapia online acontece por videochamada, pela plataforma Google Meet. Para que a sessão seja tranquila e sigilosa, é importante que você esteja em um local reservado, sem interrupções, e use fones de ouvido.

    Pergunta: Sessão online funciona?
    Resposta: Sim, funciona muito bem. Na psicanálise, o que realmente importa é a fala de cada pessoa. Por isso, é totalmente possível realizar o acompanhamento online, com a mesma seriedade e profundidade do atendimento presencial. A escolha entre online ou presencial costuma ser uma questão de preferência e conforto.

    Pergunta: Para quem o atendimento é indicado?
    Resposta: Meu atendimento é voltado para adolescentes, adultos, casais e pessoas idosas que estejam passando por dificuldades emocionais, conflitos nos relacionamentos, questões de autoestima, ansiedade, depressão e outros desafios da vida. Também acompanho processos de mudança, autoconhecimento e desenvolvimento pessoal ou profissional.

    Pergunta: Quanto tempo dura cada sessão?
    Resposta: Cada sessão dura entre 50 e 60 minutos.

    Pergunta: Qual a frequência das sessões?
    Resposta: Geralmente, as sessões acontecem uma vez por semana. A frequência ideal será definida ao longo do processo terapêutico, sempre de acordo com suas necessidades e seu ritmo de evolução.

    Pergunta: Como agendar?
    Resposta: Você pode agendar sua sessão entrando em contato pelo WhatsApp. Será um prazer encontrar o melhor horário para você.

- Animação: 
    Adicione um efeito de animação utilizado na seção HOW-IT-WORKS


## Seção FOOTER

Configuração:

    1 - cor do  background: #806090
    2 - Fonte: Playfair Display
    3 - Tamanho da fonte, utilizar os tamanhos padrôes que vem sendo usado.
    4 - Cor da fonte: #F7EFE7.
    5 - Usar Grid no layout.

Estrutura:
    1 - Usar 2 colunas, 1 para a logo e o texto descritivo e 1 para os contatos.
    2 - A logo ficará a esquerda, o texto descritivo logo abaixo.
    3 - Os contatos ficarâo a direita, terá um título, abaixo os icones com o texto descritivo.
    4 - No final do footer, teremos o texto dos direitos autorais à esquerda e a polítca de privacidade a direita que terá um link, para separar do conteúdo acima, coloque uma borda bem fina na parte superior, na cor #F7EFE7.

Informações dos itens da logo e textos descritivos:
    1 - Arquivo da logo: /assets/img/lusinele-logo.webp
    2 - Texto descritivo: Psicanalista | Contoterapeuta
    3 - Abaixo do texto descritivo, colocar a descrição: CBPC 2022-5973

Informações dos itens do contato:
    Título:
        1 - Nome do título: CONTATO
        2 - O tamanho da fonte do título, será de 15px.
        3 - O título deverá ter um letter-spacing: 0.2em
    Textos:
        1 - Icone do instagram: /assets/img/icon/icone-instagram.png 
            texto: @lusinele.terapeuta
            Inserir o link https://www.instagram.com/lusinele.terapeuta
        2 - Icone do whatsapp: /assets/img/icon/icone-whatsapp.png 
            texto: WhatsApp
            inserir o link https://wa.me/5521980325956?text=Ol%C3%A1%2C%20vim%20pelo%20site%20e%20gostaria%20de%20conversar%20sobre%20o%20atendimento.
          
        3 - Icone do telefone: /assets/img/icon/icone-telefone.webp 
            Texto: (21) 98032-5956
            quando alguém clicar no ícone de telefone em um celular, quero que o aparelho abra o discador já com o número pronto para ligar.

Informações dos itens Direitos autorais e política de privacidade.
    Direitos autorais:
        1 - simbolo e texto: &copy 2026 Lusinele Ferraz da Silva. Todos os direitos reservados.
        2 - texto da Politica de privacidade: Politica de privacidade, cria o link para a página politica-de-privacidade.html.


## PAGINA POLITICA-PRIVACIDADE

Configuração:

    1 - cor do fundo na cor #fbfaf7 e fonte Montserrat
    2 - Os títulos use a fonte Playfair Display
    3 - Tamanho da fonte, utilizar os tamanhos padrôes que vem sendo usado na página index.html.
    4 - Cor da fonte: #4e4947.

Estrutura:
    1 - No topo da página, do lado esquerdo colocar o icone /assets/img/icon/Icone-voltar.svg, com o link para voltar para a página index.html
    2 - Ao lado do icone colocar o texto Voltar ao Site.

Texto da política de privacidade:

    Política de Privacidade

1. Introdução  
Este site é mantido pelo consultório de psicanálise Lusinele Ferraz da Silva. A presente Política de Privacidade tem como objetivo informar de forma clara e transparente como os dados pessoais dos visitantes e pacientes são coletados, utilizados e protegidos.

2. Dados coletados  
Podemos coletar informações como:

Nome completo

E-mail

Telefone

Mensagens enviadas por formulários de contato ou whatsapp.

3. Finalidade do uso  
Os dados são utilizados exclusivamente para:

Agendamento de consultas

Comunicação com pacientes

Envio de informações relacionadas aos serviços oferecidos

4. Base legal  
O tratamento dos dados pessoais ocorre em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018), mediante consentimento do titular ou para tutela da saúde, conforme previsto na legislação.

5. Compartilhamento de dados  
Os dados não são compartilhados com terceiros, exceto quando necessário para a prestação dos serviços (ex.: plataformas de agendamento ou meios de pagamento), sempre respeitando a legislação vigente.

6. Armazenamento e segurança  
Os dados são armazenados de forma segura e protegidos contra acessos não autorizados. Permanecem guardados apenas pelo tempo necessário para cumprir as finalidades descritas.

7. Direitos do titular  
O paciente tem direito de:

Solicitar acesso aos seus dados

Corrigir informações incorretas

Solicitar exclusão dos dados

Revogar o consentimento a qualquer momento

8. Contato  
Para exercer seus direitos ou esclarecer dúvidas sobre esta Política de Privacidade, entre em contato pelo e-mail: lusinele.terapeuta@gmail.com.

9. Atualizações  
Esta Política de Privacidade pode ser atualizada periodicamente. A versão mais recente estará sempre disponível neste site

## ALTERAÇÕES

Na seção HEADER:
Quando o contato for clicado, colocar uma transição suave até o ponto de destino.

Na seção FAQ:
Quando estiver em Mobile, colocar o botão no final da lista de perguntas, no desktop manter a configuração original.



