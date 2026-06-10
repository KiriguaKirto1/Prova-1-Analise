# RestoStock — Prompt para Gerar Sistema SaaS de Estoque para Restaurante

Este repositório contém um prompt completo para gerar, do zero, um sistema web chamado **RestoStock**.

O objetivo do prompt é criar um protótipo funcional em **HTML, CSS e JavaScript puro**, com foco em:

- Controle de estoque para restaurante;
- Fichas técnicas gastronômicas;
- Cálculo de custo, margem e rendimento;
- Dashboard operacional;
- Perfis de usuário e permissões;
- Exportações em PDF e Excel;
- Interface responsiva;
- Tema claro e escuro;
- Módulos complementares como vendas, compras, cardápio, relatórios e configurações.

---

## Como usar

1. Copie o prompt completo abaixo.
2. Cole em uma IA geradora de código.
3. Peça para ela entregar somente um arquivo `index.html`.
4. Salve o resultado como `index.html`.
5. Abra o arquivo diretamente no navegador.

---

## Tecnologias exigidas no resultado

O sistema gerado deve usar apenas:

- HTML5;
- CSS3;
- JavaScript puro;
- jsPDF via CDN;
- jsPDF AutoTable via CDN;
- SheetJS XLSX via CDN.

Não deve usar:

- React;
- Vue;
- Angular;
- Bootstrap;
- Tailwind;
- Backend;
- Banco de dados real;
- Arquivos externos locais;
- Imagens externas obrigatórias.

---

## Prompt completo

```text
Act like um arquiteto sênior de front-end, UX/UI designer especialista em SaaS para restaurantes, product designer de sistemas de estoque, especialista em fichas técnicas gastronômicas e desenvolvedor avançado em HTML, CSS e JavaScript puro.

Crie do zero um sistema web completo chamado “RestoStock”.

O RestoStock deve ser um protótipo funcional de SaaS para controle de estoque de restaurante, com módulos complementares de ficha técnica, dashboard, cardápio, vendas, compras, relatórios, central de módulos, configurações e permissões de usuários.

O resultado deve ser um único arquivo HTML completo, pronto para salvar como index.html e abrir diretamente no navegador.

Não dependa de nenhuma referência externa.
Não peça imagem.
Não peça HTML anterior.
Não peça arquivo.
Não peça print.
Não diga que precisa de referência.
Não use placeholders como “adicione aqui”.
Não use pseudocódigo.
Não corte o código.
Não use backend.
Não use banco de dados real.
Não use React, Vue, Angular, Bootstrap ou Tailwind.
Use apenas HTML5, CSS3 e JavaScript puro.

Pode usar CDN somente para:
- jsPDF;
- jsPDF AutoTable;
- SheetJS XLSX.

Essas bibliotecas devem ser usadas para exportações em PDF e Excel.

O arquivo final deve começar exatamente com:

<!DOCTYPE html>

E terminar exatamente com:

</html>

Não escreva explicações fora do código.
Não use Markdown.
Não coloque o código dentro de blocos ```.

==================================================
OBJETIVO PRINCIPAL
==================================================

Criar um sistema SaaS completo para restaurante, com foco principal em:

1. Controle de estoque.
2. Fichas técnicas conectadas ao estoque.
3. Cálculo de custos.
4. Cálculo de margem.
5. Controle de rendimento.
6. Alertas de estoque crítico.
7. Exportação de dados.
8. Perfis de usuário com permissões.

Os módulos secundários devem existir para tornar o sistema completo, mas as telas de Estoque e Ficha Técnica devem ser as mais ricas, bonitas e funcionais.

==================================================
PRIORIDADE DE IMPLEMENTAÇÃO
==================================================

Se o limite de resposta for um problema, siga esta ordem de prioridade:

Prioridade 1 — obrigatória:
- layout completo;
- sidebar;
- topbar;
- navegação entre telas;
- perfis de usuário;
- permissões visuais;
- dashboard;
- estoque completo;
- ficha técnica completa;
- tema claro/escuro;
- responsividade;
- toasts;
- dados mockados;
- exportação básica PDF/Excel.

Prioridade 2 — importante:
- cardápio;
- vendas;
- compras;
- relatórios;
- configurações;
- central de módulos.

Prioridade 3 — complementar:
- animações extras;
- gráficos mais elaborados;
- múltiplos relatórios detalhados;
- configurações avançadas.

Nunca sacrifique a qualidade da tela de Estoque nem da tela de Ficha Técnica.
Essas duas áreas devem ser as mais completas do sistema.

==================================================
CONTRATO MÍNIMO FUNCIONAL
==================================================

O sistema deve ser bonito, mas acima de tudo precisa funcionar.

Mesmo que módulos secundários sejam mais simples, estas funções são obrigatórias:

1. Navegação entre telas sem recarregar a página.
2. Sidebar desktop e drawer mobile.
3. Bottom navigation no mobile.
4. Troca de perfil com aplicação visual de permissões.
5. Bloqueio real de módulos sem permissão.
6. Toast para sucesso, erro e permissão negada.
7. Tema claro/escuro salvo no localStorage.
8. Modo compacto/confortável salvo no localStorage.
9. Redução de animações.
10. Renderização real da tabela de estoque a partir de array JavaScript.
11. Busca, filtro e status automático no estoque.
12. Modal ou drawer funcional para estoque.
13. Renderização real dos cards de ficha técnica a partir de array JavaScript.
14. Busca e filtro de fichas técnicas.
15. Alternância entre visualização grade e lista.
16. Seleção de ficha técnica com atualização do painel lateral.
17. Abas funcionais no painel lateral da ficha.
18. Modal funcional de detalhes da ficha.
19. Formulário funcional para nova/editar ficha.
20. Ingredientes dinâmicos no formulário.
21. Etapas de preparo dinâmicas no formulário.
22. Cálculo automático de custo, lucro, margem e preço sugerido.
23. Persistência de fichas e estoque no localStorage.
24. Carrinho funcional na tela de vendas.
25. Exportação Excel de estoque.
26. Exportação Excel de fichas.
27. Exportação PDF da ficha selecionada.
28. Impressão limpa da ficha selecionada.
29. Layout responsivo para desktop, tablet e mobile.

Se precisar simplificar algo, simplifique os módulos secundários, nunca Estoque, Ficha Técnica, navegação, permissões, tema, exportações ou responsividade.

==================================================
IDENTIDADE VISUAL
==================================================

Crie uma interface premium, moderna, gastronômica e profissional.

O estilo deve lembrar um SaaS real usado por restaurantes, cafeterias, hamburguerias, bistrôs e cozinhas profissionais.

Use uma identidade visual baseada em:
- café;
- madeira;
- creme;
- caramelo;
- dourado;
- marrom;
- bege;
- verde para sucesso;
- vermelho para alerta;
- amarelo para atenção;
- azul para informação.

A interface deve ter:
- sidebar escura;
- cards claros;
- sombras suaves;
- cantos arredondados;
- gradientes sutis;
- botões elegantes;
- badges de status;
- tabelas modernas;
- modais grandes;
- drawer lateral;
- toast de feedback;
- tema claro e escuro;
- responsividade completa;
- microinterações suaves.

Crie variáveis CSS obrigatórias:

--bg
--card
--card2
--text
--muted
--border
--primary
--primary2
--accent
--accent-soft
--green
--red
--yellow
--blue
--shadow
--radius

Crie também:

body.dark

O modo escuro deve alterar toda a aparência do sistema, incluindo:
- fundo;
- cards;
- textos;
- bordas;
- botões;
- tabelas;
- modais;
- painéis;
- badges;
- inputs;
- sidebars;
- drawers.

==================================================
ESTRUTURA DO HTML
==================================================

O HTML deve conter:

1. Skip link:
Texto:
“Pular para o conteúdo principal”

2. Container principal:
Classe:
.app

Layout desktop:
- sidebar fixa à esquerda com 260px;
- conteúdo principal à direita.

3. Sidebar:
- logo;
- nome RestoStock;
- subtítulo “Gestão inteligente para restaurantes”;
- seletor de perfil;
- menu de navegação;
- nota lateral no rodapé.

4. Main:
- topbar sticky;
- telas internas;
- conteúdo dinâmico.

5. Topbar:
- botão de menu mobile;
- título da tela atual;
- subtítulo da tela;
- busca global;
- botão de notificações;
- botão de tema claro/escuro;
- botão de ação principal.

6. Bottom navigation mobile:
Visível apenas no mobile.
Itens:
- Dashboard;
- Estoque;
- Ficha Técnica;
- Vendas;
- Mais.

==================================================
PERFIS DE USUÁRIO
==================================================

Crie exatamente estes perfis:

1. Administrador / Dono
2. Gerente
3. Atendente / Caixa
4. Cozinheiro
5. Estoquista

Cada perfil deve ter:
- ícone;
- nome;
- descrição;
- permissões;
- avatar visual.

Permissões:

Administrador / Dono:
- acesso total;
- pode editar;
- pode excluir;
- pode exportar;
- pode acessar configurações;
- pode ativar módulos.

Gerente:
- dashboard;
- estoque;
- ficha técnica;
- cardápio;
- vendas;
- compras;
- relatórios;
- sem configurações avançadas.

Atendente / Caixa:
- dashboard resumido;
- vendas;
- cardápio;
- consulta simples de estoque;
- sem edição de fichas;
- sem compras;
- sem configurações.

Cozinheiro:
- ficha técnica;
- cardápio;
- consulta de estoque;
- sem vendas financeiras;
- sem compras;
- sem configurações.

Estoquista:
- estoque;
- compras;
- fornecedores;
- alertas;
- consulta de fichas;
- sem vendas;
- sem cardápio financeiro;
- sem configurações sensíveis.

Menu lateral obrigatório:
- Dashboard;
- Estoque;
- Ficha Técnica;
- Cardápio;
- Vendas;
- Compras;
- Relatórios;
- Central de Módulos;
- Configurações.

Quando o perfil não tiver permissão:
- item deve aparecer bloqueado;
- mostrar cadeado;
- reduzir opacidade;
- impedir clique;
- mostrar toast: “Você não tem permissão para acessar este módulo.”

==================================================
ARQUITETURA INTERNA DO JAVASCRIPT
==================================================

Organize o JavaScript de forma clara, compacta e reutilizável.

Use esta estrutura lógica:

1. state:
Objeto global com:
- tela ativa;
- perfil ativo;
- tema;
- densidade;
- ficha selecionada;
- filtros de estoque;
- filtros de ficha;
- carrinho;
- aba ativa da ficha.

2. data:
Objeto com arrays mockados:
- stock;
- recipes;
- menu;
- sales;
- purchases;
- reports;
- modules.

3. permissions:
Objeto com permissões por perfil.

4. helpers:
Funções auxiliares:
- formatCurrency;
- formatPercent;
- calcMargin;
- calcStockStatus;
- showToast;
- saveLocal;
- loadLocal;
- createId.

5. render:
Funções de renderização:
- renderApp;
- renderSidebar;
- renderDashboard;
- renderStock;
- renderRecipes;
- renderRecipePanel;
- renderMenu;
- renderSales;
- renderPurchases;
- renderReports;
- renderModules;
- renderSettings.

6. actions:
Funções de interação:
- navigateTo;
- switchRole;
- toggleTheme;
- openModal;
- closeModal;
- selectRecipe;
- saveRecipe;
- updateCart;
- exportPDF;
- exportExcel.

Use data attributes para eventos:

data-screen
data-action
data-id
data-tab

Exemplos:
- data-screen="estoque"
- data-action="open-stock-drawer"
- data-action="select-recipe"
- data-id="risoto-cogumelos"
- data-tab="ingredientes"

Evite criar muitos listeners separados.
Use event delegation no document sempre que possível.

Use JavaScript para renderizar listas, cards, tabelas e módulos a partir de arrays de dados.
Evite repetir manualmente grandes blocos HTML.
O código deve ser completo, mas otimizado para caber em uma única resposta.

==================================================
LOCALSTORAGE
==================================================

Use as seguintes chaves no localStorage:

restostock.theme
restostock.density
restostock.reduceMotion
restostock.activeRole
restostock.recipes
restostock.stock
restostock.sales

Ao carregar a página:
- recuperar preferências salvas;
- recuperar fichas técnicas salvas;
- recuperar estoque salvo;
- se não existir dado salvo, usar os dados mockados padrão.

Na tela de Configurações, crie ações para:
- limpar localStorage;
- restaurar dados mockados;
- exportar backup simulado.

==================================================
TELA DASHBOARD
==================================================

Crie uma dashboard executiva.

Elementos obrigatórios:

1. Hero card:
Badge:
“Operação em tempo real”

Título:
“Bem-vindo ao RestoStock”

Texto:
“Controle estoque, fichas técnicas, custos, vendas e alertas operacionais em uma única plataforma.”

Tags:
- Estoque inteligente;
- Custos controlados;
- Fichas padronizadas;
- Alertas automáticos.

2. KPIs:
Crie 6 cards:
- Vendas do dia;
- Pedidos;
- Valor em estoque;
- Insumos críticos;
- Margem média;
- Fichas ativas.

Cada KPI deve ter:
- ícone;
- label;
- valor;
- subtítulo;
- detalhe visual.

3. Ações rápidas:
- Nova entrada de estoque;
- Nova ficha técnica;
- Registrar venda;
- Pedido de compra;
- Exportar relatório;
- Ver alertas.

4. Gráficos simulados:
- barras horizontais de consumo por categoria;
- donut chart de vendas por tipo;
- lista de alertas operacionais.

5. Alertas:
- estoque crítico;
- vencimento próximo;
- margem baixa;
- compra pendente;
- ingrediente com alto consumo.

==================================================
TELA ESTOQUE — MÓDULO MAIS IMPORTANTE
==================================================

A tela de Estoque deve ser muito completa.

Crie um hero:

Badge:
“Controle de insumos”

Título:
“Estoque Inteligente”

Descrição:
“Acompanhe níveis mínimos, custos, validade, fornecedores e impacto dos insumos nas fichas técnicas.”

Botões:
- Nova entrada;
- Ajustar estoque;
- Exportar Excel;
- Exportar PDF.

Cards de resumo:
- Total de insumos;
- Valor total em estoque;
- Itens críticos;
- Vencimentos próximos;
- Custo médio;
- Entradas no mês.

Filtros:
- busca por insumo;
- categoria;
- status;
- ordenação.

Tabela de estoque com colunas:
- Insumo;
- Categoria;
- Estoque atual;
- Unidade;
- Estoque mínimo;
- Custo unitário;
- Valor em estoque;
- Fornecedor;
- Validade;
- Status;
- Ações.

Status possíveis:
- Normal;
- Atenção;
- Crítico;
- Vencendo.

Ações por item:
- Entrada;
- Saída;
- Ajustar;
- Editar.

Crie modal ou drawer para cadastrar/editar item de estoque com campos:
- nome;
- categoria;
- unidade;
- estoque atual;
- estoque mínimo;
- custo unitário;
- fornecedor;
- validade;
- observações.

Dados obrigatórios de estoque:
- Arroz arbóreo;
- Cogumelos frescos;
- Pão brioche;
- Carne bovina;
- Salmão;
- Spaghetti;
- Bacon;
- Alface romana;
- Chocolate meio amargo;
- Tomate;
- Queijo parmesão;
- Azeite;
- Camarão;
- Leite de coco;
- Farinha de trigo;
- Ovos;
- Creme de leite;
- Batata;
- Cebola;
- Alho.

O status deve ser calculado automaticamente com base em:
- estoque atual;
- estoque mínimo;
- validade.

==================================================
TELA FICHA TÉCNICA — MÓDULO MAIS BONITO
==================================================

A tela de Ficha Técnica deve ser a mais visual e sofisticada do sistema.

Crie layout em duas colunas no desktop:

Coluna esquerda:
- lista de fichas técnicas.

Coluna direita:
- painel sticky com detalhes da ficha selecionada.

No mobile:
- tudo deve virar uma coluna.

--------------------------------------------------
Hero da Ficha Técnica
--------------------------------------------------

Badge:
“Gestão de receitas”

Título:
“Ficha Técnica Inteligente”

Descrição:
“Padronize receitas, calcule custo por porção, controle rendimento, margem e impacto dos ingredientes no estoque.”

Botões:
- Nova ficha;
- Exportar Excel;
- Imprimir selecionada.

Mini KPIs:
- Total de fichas;
- Margem média;
- Custo médio;
- Receitas ativas.

--------------------------------------------------
Painel de lista
--------------------------------------------------

Cabeçalho:
Título:
“Fichas Técnicas”

Subtítulo:
“Controle receitas, custos, rendimento, preparo e padronização da cozinha.”

Toolbar:
- busca;
- filtro por categoria;
- seletor grade/lista;
- botão nova ficha.

Categorias:
- Todos;
- Massas;
- Carnes;
- Peixes;
- Lanches;
- Saladas;
- Sobremesas;
- Vegetarianos;
- Brasileiros.

--------------------------------------------------
Cards de ficha técnica
--------------------------------------------------

Crie pelo menos 8 fichas:

1. Risoto de Cogumelos
2. Burger Artesanal
3. Salmão Grelhado
4. Spaghetti Carbonara
5. Salada Caesar
6. Brownie da Casa
7. Filé ao Molho Madeira
8. Moqueca de Peixe

Cada card deve ter:
- área visual ilustrada com gradiente, emoji gastronômico ou SVG inline;
- badge de categoria;
- badge de status;
- nome;
- descrição curta;
- custo total;
- preço de venda;
- margem;
- tempo de preparo;
- rendimento;
- botão Detalhes;
- botão Editar.

Não use imagens externas.
Todos os visuais de pratos devem ser feitos com CSS, emojis, SVG inline ou gradientes internos.

Status possíveis:
- Ativa;
- Revisar custo;
- Alta margem;
- Sazonal;
- Bloqueada.

--------------------------------------------------
Painel lateral de detalhes
--------------------------------------------------

Quando nenhuma ficha estiver selecionada:
Mostrar:
- ícone grande;
- título “Selecione uma ficha técnica”;
- texto explicativo;
- botão “Criar nova ficha”.

Quando uma ficha estiver selecionada:
Mostrar:
- ilustração grande do prato;
- categoria;
- status;
- nome;
- descrição;
- responsável;
- última atualização;
- alérgenos;
- validade operacional.

Cards de estatísticas:
- custo total;
- preço de venda;
- lucro;
- margem;
- rendimento;
- custo por porção.

Abas:
- Ingredientes;
- Preparo;
- Custos.

Aba Ingredientes:
- nome;
- quantidade;
- unidade;
- custo unitário;
- custo total;
- aviso se ingrediente estiver crítico no estoque.

Aba Preparo:
- passos numerados;
- título;
- descrição;
- tempo estimado;
- nota de qualidade.

Aba Custos:
- custo de ingredientes;
- perdas;
- embalagem;
- custo total;
- preço de venda;
- lucro;
- margem;
- preço sugerido;
- barra visual de margem.

Botões:
- Imprimir;
- PDF;
- Excel;
- Editar.

==================================================
MODAL DE DETALHES DA FICHA
==================================================

Ao clicar em Detalhes, abrir modal grande com:

- overlay escuro com blur;
- cabeçalho fixo;
- botão fechar;
- ilustração do prato;
- título;
- descrição;
- badges;
- resumo operacional;
- tabela de ingredientes;
- passos de preparo;
- custos;
- dicas do chef;
- controle de qualidade;
- alérgenos;
- observações.

Botões:
- Imprimir;
- Exportar PDF;
- Exportar Excel;
- Editar;
- Fechar.

==================================================
FORMULÁRIO DE NOVA/EDITAR FICHA
==================================================

Crie modal ou drawer.

Campos:
- nome;
- categoria;
- descrição;
- preço de venda;
- rendimento;
- tempo de preparo;
- responsável;
- status;
- alérgenos;
- observações;
- dicas do chef.

Ingredientes dinâmicos:
- ingrediente;
- quantidade;
- unidade;
- custo unitário;
- custo total;
- botão remover;
- botão adicionar ingrediente.

Etapas dinâmicas:
- título;
- descrição;
- tempo;
- nota;
- botão remover;
- botão adicionar etapa.

Cálculos automáticos:
- custo total;
- custo por porção;
- lucro;
- margem;
- preço sugerido.

Ao salvar:
- atualizar dados em memória;
- salvar no localStorage;
- atualizar interface;
- mostrar toast.

==================================================
CARDÁPIO
==================================================

Crie tela simples, mas bonita, com:
- cards de pratos;
- categoria;
- preço;
- custo;
- margem;
- disponibilidade;
- botão editar;
- botão alternar disponibilidade.

Disponibilidade:
- Disponível;
- Indisponível;
- Sazonal.

Os pratos devem se conectar visualmente às fichas técnicas.

==================================================
VENDAS
==================================================

Crie tela de vendas/POS com:
- lista de produtos;
- busca;
- filtros;
- carrinho lateral;
- adicionar item;
- alterar quantidade;
- remover item;
- subtotal;
- taxa de serviço;
- desconto;
- total;
- forma de pagamento;
- botão finalizar venda.

Ao finalizar:
- mostrar toast;
- limpar carrinho;
- registrar venda simulada.

==================================================
COMPRAS
==================================================

Crie tela de compras com:
- cards de resumo;
- tabela de pedidos;
- fornecedores;
- status;
- previsão;
- valor.

Status:
- Rascunho;
- Enviado;
- Aprovado;
- Recebido;
- Atrasado.

Botões:
- Novo pedido;
- Exportar;
- Ver fornecedor.

==================================================
RELATÓRIOS
==================================================

Crie tela de relatórios com cards:

- Vendas por período;
- Margem por prato;
- Custo de estoque;
- Curva ABC de insumos;
- Compras por fornecedor;
- Fichas com baixa margem.

Cada card deve ter:
- título;
- descrição;
- indicador;
- botão visualizar;
- botão exportar.

Inclua uma tabela analítica simulada.

==================================================
CENTRAL DE MÓDULOS
==================================================

Crie tela com cards de módulos:

- Delivery;
- Reservas;
- Financeiro avançado;
- Multiunidades;
- Integração fiscal;
- Programa de fidelidade;
- Controle de validade;
- Auditoria de estoque;
- App da cozinha.

Status:
- Ativo;
- Disponível;
- Bloqueado;
- Em breve.

Cada card deve ter:
- ícone;
- nome;
- descrição;
- status;
- botão.

==================================================
CONFIGURAÇÕES
==================================================

Crie tela de configurações com seções:

Aparência:
- tema claro/escuro;
- densidade compacta/confortável;
- reduzir animações.

Restaurante:
- nome;
- CNPJ fictício;
- endereço;
- taxa de serviço;
- moeda.

Usuários e permissões:
- lista dos perfis;
- descrição de permissões.

Dados:
- limpar localStorage;
- restaurar dados mockados;
- exportar backup simulado.

==================================================
JAVASCRIPT OBRIGATÓRIO
==================================================

Implemente JavaScript puro para:

Navegação:
- trocar telas sem reload;
- atualizar título;
- atualizar subtítulo;
- atualizar item ativo;
- controlar menu mobile;
- controlar bottom nav.

Perfis:
- abrir dropdown;
- trocar perfil;
- aplicar permissões;
- bloquear telas;
- mostrar toast de acesso negado.

Tema:
- alternar claro/escuro;
- salvar preferência;
- modo compacto;
- reduzir animações.

Estoque:
- renderizar tabela;
- busca;
- filtros;
- status automático;
- drawer/modal de item;
- entrada simulada;
- ajuste simulado;
- exportar Excel;
- exportar PDF.

Ficha técnica:
- renderizar cards;
- buscar;
- filtrar;
- alternar grade/lista;
- selecionar ficha;
- renderizar painel lateral;
- trocar abas;
- abrir modal de detalhes;
- criar ficha;
- editar ficha;
- adicionar/remover ingredientes;
- adicionar/remover etapas;
- calcular custo;
- calcular margem;
- salvar localStorage;
- exportar PDF;
- exportar Excel;
- imprimir.

Vendas:
- adicionar item ao carrinho;
- alterar quantidade;
- remover item;
- calcular subtotal;
- calcular taxa;
- calcular desconto;
- calcular total;
- finalizar venda.

Feedback:
- toasts;
- empty states;
- mensagens de sucesso;
- mensagens de erro.

==================================================
EXPORTAÇÃO E IMPRESSÃO
==================================================

Usar:
- jsPDF;
- jsPDF AutoTable;
- SheetJS XLSX.

Funções obrigatórias:
- exportar ficha selecionada em PDF;
- exportar ingredientes da ficha em PDF com tabela;
- exportar lista de fichas em Excel;
- exportar estoque em Excel;
- exportar relatório em PDF;
- imprimir ficha selecionada.

Antes de exportar, verifique se as bibliotecas externas estão disponíveis.

Se jsPDF, jsPDF AutoTable ou XLSX não estiverem carregados, mostre um toast amigável:
“Biblioteca de exportação ainda não carregada. Tente novamente em alguns segundos.”

Para Excel, se XLSX falhar, gere um CSV simples como fallback.

A impressão deve ocultar:
- sidebar;
- topbar;
- botões;
- navegação mobile.

E mostrar apenas:
- nome da ficha;
- dados principais;
- ingredientes;
- preparo;
- custos.

==================================================
RESPONSIVIDADE
==================================================

Crie breakpoints para:
- 1250px;
- 1000px;
- 860px.

Desktop:
- sidebar fixa;
- cards em grid;
- ficha técnica em duas colunas.

Tablet:
- grids reduzidos;
- painéis empilhados quando necessário.

Mobile:
- sidebar vira drawer;
- topbar compacta;
- busca global pode ser ocultada;
- cards em uma coluna;
- tabelas com scroll horizontal;
- bottom nav fixa;
- painel da ficha abaixo da lista.

==================================================
ACESSIBILIDADE
==================================================

Inclua:
- skip link;
- labels em inputs;
- aria-label em botões de ícone;
- alt em ilustrações quando aplicável;
- foco visível;
- contraste adequado;
- botões semânticos;
- navegação por teclado;
- opção de reduzir animações;
- textos claros em estados bloqueados.

==================================================
DADOS MOCKADOS
==================================================

Crie dados realistas diretamente no JavaScript.

Fichas técnicas:
- no mínimo 8 fichas completas.

Cada ficha deve ter:
- id;
- nome;
- categoria;
- descrição;
- tempo;
- rendimento;
- custo;
- preço;
- margem;
- status;
- alérgenos;
- responsável;
- atualização;
- validade operacional;
- ingredientes;
- etapas;
- dicas;
- observações;
- notas de qualidade.

Estoque:
- no mínimo 20 insumos.

Cardápio:
- no mínimo 8 pratos.

Vendas:
- no mínimo 6 vendas simuladas.

Compras:
- no mínimo 5 pedidos.

Relatórios:
- no mínimo 6 relatórios.

Módulos:
- no mínimo 9 módulos.

As fichas técnicas devem se relacionar visualmente com ingredientes do estoque sempre que possível.

==================================================
CSS OBRIGATÓRIO
==================================================

Crie estilos completos para:

- .app
- aside
- main
- .topbar
- .mobile-bottom
- .screen
- .screen.active
- .brand
- .logo
- .profile
- .role-current
- .role-toggle
- .role-options
- .role-option
- .nav
- .locked
- .card
- .kpi
- .status
- .empty
- .table-wrap
- table
- th
- td
- .modal-overlay
- .modal
- .drawer-overlay
- .drawer
- .toast
- .recipe-page-shell
- .recipe-board
- .recipe-sidepanel
- .recipe-card
- .recipe-detail
- .recipe-tabs
- .stock-table
- .form-grid
- .actions

Inclua também:
- @media print;
- responsividade;
- animações;
- foco visível.

==================================================
REGRAS PARA EVITAR CÓDIGO CORTADO
==================================================

Para evitar corte de resposta:
- use CSS organizado, mas sem duplicação excessiva;
- renderize componentes repetitivos via JavaScript;
- não repita cards manualmente quando puder gerar por array;
- módulos secundários podem ser mais compactos;
- mantenha Estoque e Ficha Técnica como telas mais completas;
- priorize funções reais nos botões principais;
- crie dados mockados eficientes;
- evite comentários longos;
- não inclua explicações fora do código.

==================================================
REGRAS FINAIS
==================================================

Crie tudo do zero.
Não dependa de referência.
Não solicite arquivos.
Não use imagens externas.
Não use frameworks.
Não entregue uma interface genérica.
Não entregue apenas uma tela.
Não deixe botões principais sem função.
Não corte o código.
Não use comentários dizendo “continua”.
Não escreva explicações fora do HTML.
Não use Markdown.

O resultado deve parecer um SaaS real, completo, bonito, responsivo e funcional para controle de estoque de restaurante, com ficha técnica avançada e módulos complementares.

O arquivo final deve começar exatamente com:

<!DOCTYPE html>

E terminar exatamente com:

</html>

Entregue somente o código HTML completo.

Take a deep breath and work on this problem step-by-step.
