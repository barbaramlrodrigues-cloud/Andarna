# Projeto Integrador - Andarna (Entrega 1)

Repositório da Entrega 1 (Esqueleto Semântico) do Projeto Integrador de Sistemas de Informação.

## Sobre o Projeto
Construímos uma estrutura base de 4 páginas em HTML puro para a plataforma de catálogo de livros **Andarna**, focando em:
- Estruturação semântica com marcos (`header`, `nav`, `main`, `section`, `aside`, `footer`).
- Hierarquia lógica de cabeçalhos (`h1`, `h2`, `h3`) única por página e sem saltos.
- Navegação interna consistente e checklist de acessibilidade aplicada.

## Registro de Uso de IA
Utilizamos ferramentas de IA apenas no final para conferir e validar nosso código, garantindo que os elementos de acessibilidade (como o atributo `lang="pt-BR"`, o *skip link* e a navegação pelo teclado via tecla Tab) estivessem corretos de acordo com o critério da disciplina.

---

# Projeto Integrador - Andarna (Entrega 2)

Repositório da Entrega 2 (Estilo e Responsividade) do Projeto Integrador de Sistemas de Informação.

## Sobre o Projeto
Desenvolvemos uma folha de estilos em CSS própria para a plataforma **Andarna**, focando em:
- Estruturação de layout moderno utilizando Flexbox e CSS Grid, sem utilização de frameworks externos.
- Adaptação visual responsiva para atender aos 3 breakpoints obrigatórios (mobile, tablet e desktop).
- Garantia de contraste adequada e integridade visual em todas as larguras de tela.

## Registro de Uso de IA
Utilizamos ferramentas de IA apenas no final para conferir a sintaxe, validar o comportamento dos breakpoints e revisar a aplicação das variáveis CSS, garantindo que o código estivesse alinhado com a exigência de entrega.

---

# Projeto Integrador - Andarna (Entrega 3)

Repositório da Entrega 3 (Formulário e Refinamento) do Projeto Integrador de Sistemas de Informação.

## Sobre o Projeto
Finalizamos o refinamento visual e os formulários funcionais da plataforma **Andarna**, alinhando o layout ao modelo da disciplina e focando em:
- Formulários funcionais com validação nativa do próprio navegador (campos obrigatórios, formato de e-mail, limite de caracteres e aceitação de termos), sem uso de JavaScript.
- Organização visual responsiva para funcionar bem em celulares, tablets e computadores, dividindo cabeçalho, conteúdo principal, barra lateral e rodapé.
- Revisão de acessibilidade, garantindo contraste adequado para leitura e navegação completa pelo teclado.

## Registro de Uso de IA

### 1. Mapeamento de Uso
Desenvolvemos a estrutura das páginas e os estilos do projeto em dupla, utilizando ferramentas de IA apenas como apoio para revisar o nosso código em comparação com o modelo da disciplina e corrigir detalhes de alinhamento, responsividade e validação.

### 2. Revisão Técnica (Alterações Realizadas)

- **Ajuste na organização da grade e no cabeçalho responsivo:**
  - **O que tínhamos feito:** Tínhamos montado o cabeçalho e a divisão da página de forma mais simples, o que fazia alguns elementos desalinharem ao mudar do computador para o celular.
  - **O que foi alterado:** Ajustamos a distribuição das áreas da página (cabeçalho, menu, conteúdo principal, barra lateral e rodapé) e agrupamos os campos dos formulários com `fieldset`.
  - **Por que foi alterado:** Para manter a interface alinhada ao modelo apresentado em aula e garantir que nenhuma seção quebre em telas menores.

- **Validação nativa nos formulários sem depender de scripts:**
  - **O que tínhamos feito:** Estávamos em dúvida sobre usar código extra para validar os cadastros e tínhamos deixado alguns campos sem regras completas de preenchimento.
  - **O que foi alterado:** Mantivemos apenas a validação própria do navegador, definindo campos obrigatórios, verificação de e-mail, tamanho mínimo e seleção obrigatória de status.
  - **Por que foi alterado:** A Entrega 3 exige que os formulários funcionem com validação nativa do HTML5, sem precisar de JavaScript.

- **Destaque de foco para navegação por teclado e contraste:**
  - **O que tínhamos feito:** O destaque ao navegar usando a tecla `Tab` aparecia mais nos links principais do topo, ficando pouco visível nos campos e botões.
  - **O que foi alterado:** Reforçamos o contorno visual quando um campo, botão ou link está selecionado pelo teclado e conferimos o contraste entre textos e fundos.
  - **Por que foi alterado:** Para facilitar o uso por quem navega apenas pelo teclado e garantir boa leitura em todas as páginas.