# Prompt para Claude Code - Apresentação de Meningioma Gigante

Crie uma página HTML completa para uma apresentação de slides interativa com o seguinte layout e especificações:

## CONFIGURAÇÕES PERSONALIZÁVEIS:

### Cores e Tema:
- Cor principal do gradiente: #4a90e2
- Cor secundária do gradiente: #7b68ee
- Cor de hover/destaque: #4a90e2
- Cor do texto principal: #333

### Informações da Apresentação:
- Título principal: MENINGIOMA GIGANTE DO HEMISFÉRIO ESQUERDO
- Subtítulo/Descrição: Cirurgia Guiada por Fluoresceína Sódica - Relato de Caso | Liga Acadêmica de Neurocirurgia
- Informações do rodapé: Baseado em: Cui J, et al. Front Oncol. 2024 | Apresentação Acadêmica

### Conteúdo dos Slides:
1. Capa - Identificação e Título
2. Introdução - Conceitos de Meningioma
3. Definição de Meningioma Gigante
4. Apresentação do Caso - Identificação
5. Exame Físico Inicial
6. Neuroimagem Prévia (2021)
7. Neuroimagem Atual (2024)
8. Planejamento Cirúrgico
9. Técnica com Fluoresceína Sódica
10. Ressecção Tumoral
11. Análise Anatomopatológica
12. RM Pós-operatória
13. Complicações Pós-operatórias
14. Evolução Neurológica
15. Discussão - Crescimento Atípico
16. Discussão - Casos Históricos
17. Discussão - Fluoresceína
18. Discussão - Embolização
19. Conclusões do Caso
20. Mensagem Final
21. Referências Bibliográficas

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
  1. "▶ Iniciar Apresentação Completa" (gradiente alternativo: #28a745 para #20c997)
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
- Cada slide deve linkar para: slide[numero].html (ex: slide1.html, slide2.html, etc.)
- Botão "Iniciar Apresentação Completa" deve linkar para: apresentacao-completa.html
- Botão "Visualizar Slides Individualmente" deve linkar para: slide1.html

### Arquivos e Recursos:
- O conteúdo completo dos slides está disponível em markdown no arquivo: document.md
- As imagens do artigo estão na pasta figures/ com os nomes: figure1.png, figure2.png, figure3.png, figure4.png
- Integrar as imagens nos slides correspondentes conforme indicado no document.md

### Observações Adicionais:
- Adicionar um pequeno badge ou indicador "CASO CLÍNICO" no canto superior direito do container
- Incluir ícone de cérebro (🧠) antes do título principal, se possível
- Garantir que o gradiente de fundo transmita uma sensação médica/científica com as cores azuis escolhidas

Gere o código HTML completo, inline CSS incluído, sem necessidade de arquivos externos, pronto para ser salvo como index.html.