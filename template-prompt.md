Crie uma página HTML completa para uma apresentação de slides interativa com o seguinte layout e especificações:

## CONFIGURAÇÕES PERSONALIZÁVEIS:

### Cores e Tema:
- Cor principal do gradiente: [INSERIR COR 1, ex: #667eea]
- Cor secundária do gradiente: [INSERIR COR 2, ex: #764ba2]
- Cor de hover/destaque: [INSERIR COR HOVER, ex: #667eea]
- Cor do texto principal: [INSERIR COR TEXTO, ex: #333]

### Informações da Apresentação:
- Título principal: [INSERIR TÍTULO]
- Subtítulo/Descrição: [INSERIR SUBTÍTULO]
- Informações do rodapé: [INSERIR INFO RODAPÉ]

### Conteúdo dos Slides:
[INSERIR LISTA DE SLIDES NO FORMATO:]
1. Título do Slide 1
2. Título do Slide 2
3. Título do Slide 3
(continue conforme necessário)

## ESPECIFICAÇÕES TÉCNICAS OBRIGATÓRIAS:

### Layout Geral:
- Página responsiva com fundo gradiente diagonal (135deg)
- Container central com fundo branco semi-transparente (rgba 255,255,255,0.95)
- Bordas arredondadas (20px) e sombra elegante
- Padding interno de 40px
- Máxima largura de 800px centralizada

### Grid de Slides:
- Cada slide deve ser um link clicável com:
  - Número do slide em um quadrado com gradiente
  - Título do slide ao lado
  - Efeito hover que move o item para direita
  - Borda que aparece no hover
  - Fundo cinza claro (#f8f9fa)
  - Padding de 15px 20px
  - Bordas arredondadas de 10px

### Estilo dos Números:
- Quadrados de 40x40px
- Gradiente nas cores principais
- Texto branco centralizado
- Fonte bold
- Bordas arredondadas de 10px

### Botões de Ação:
- 2 botões principais no final:
  1. "▶ Modo Apresentação Completo" (gradiente alternativo opcional)
  2. "▶ Visualizar Slides Individualmente"
- Largura total (100%)
- Padding de 18px
- Gradiente com as cores principais
- Efeito hover que eleva o botão
- Bordas arredondadas de 10px

### Responsividade:
- Breakpoint em 600px
- Ajustes de padding e tamanho de fonte para mobile

### Tipografia:
- Font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif
- Título principal: 32px (26px mobile)
- Subtítulo: 18px
- Texto dos slides: 16px (14px mobile)
- Botões: 18px, font-weight 600

### Interações:
- Transições suaves de 0.3s em todos os elementos interativos
- Hover effects nos links dos slides (movimento lateral de 5px)
- Hover effects nos botões (elevação com translateY(-2px))
- Mudança de cor de borda no hover

### Estrutura dos Links:
- Cada slide deve linkar para: [nome-do-slide].html
- Links dos botões para: apresentacao.html e [primeiro-slide].html

Gere o código HTML completo, inline CSS incluído, sem necessidade de arquivos externos, pronto para ser salvo como index.html.