# Plano — Portfólio Zander

## Escopo
Página única, responsiva e em português brasileiro para posicionar Zander como desenvolvedor especializado em Discord e Python. O site apresenta serviços, forma de trabalho e uma chamada clara para conversa, com texto específico e tom humano.

## Direção de design
- **Movimento:** terminal editorial / brutalismo digital refinado — uma mistura de interface de ferramenta de desenvolvimento com portfólio autoral.
- **Princípios:** precisão sem frieza; contraste alto com respiros generosos; conteúdo direto; detalhes de interface que sugerem bastidores de produto real.
- **Filosofia de cor:** fundo quase preto azulado para dar profundidade e foco; branco quente para leitura; verde-lima como assinatura de energia técnica e ação; azul elétrico como apoio para comunicar infraestrutura e conexão.
- **Paradigma de layout:** composição assimétrica em trilhos, com hero dividido entre manifesto e painel de console; serviços em blocos de tamanhos variados; processo em linha contínua em vez de uma grade centralizada.
- **Elementos de assinatura:** marca `Z/` em caixa técnica, etiquetas de status com pontos pulsantes e linhas finas de circuito conectando seções.
- **Interação:** navegação por âncoras com rolagem suave; hover revela intenção e profundidade sem exagero; menu móvel compacto; elementos entram em cena apenas quando necessários.
- **Animação:** pulse lento em indicadores; reveal vertical discreto ao entrar no viewport; brilho de borda curto nos CTAs; nenhuma animação decorativa constante que prejudique a leitura.
- **Tipografia:** Space Grotesk para títulos e frases de posicionamento; IBM Plex Mono para labels, metadados, números e linguagem de interface.
- **Essência da marca:** “Construo a parte invisível que faz uma comunidade funcionar melhor.” Personalidade: técnico, próximo, inventivo.
- **Voz:** direta, específica, sem promessa vazia. Exemplos: “Ideia boa merece sistema à altura.” e “Do primeiro fluxo ao deploy, sem caixa-preta.”
- **Wordmark / logo:** `Z/` como monograma inclinado, remetendo a terminal e caminho de execução; o nome Zander aparece como assinatura ao lado.
- **Cor proprietária:** verde-lima `#b8ff5a`, usada com parcimônia em ações, status e marca.

## Implementação
- `index.html`: estrutura sem framework, semântica, SEO básico, navegação e todas as seções da página.
- `styles.css`: sistema visual responsivo, tokens de cor, layout assimétrico, estados de interação e breakpoints mobile.
- `script.js`: menu mobile, ano dinâmico e reveal on-scroll com fallback acessível.
- `public/manus-routes.json`: manifesto da rota única `/` exigido pelo Webdev.
- `logo.svg` + `app.config.ts`: assinatura visual e metadado de logo do projeto.
- `package.json`: servidor estático simples em `0.0.0.0:3000` para Preview.

## Estrutura
O site é deliberadamente leve e estático. Não há backend, autenticação ou banco, pois a solicitação é um portfólio institucional de uma página. O runtime serve os arquivos diretamente e mantém a experiência rápida em desktop e mobile.
