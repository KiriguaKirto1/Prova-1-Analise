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
Act as a Senior Front-end Architect, Senior UX/UI Designer, SaaS Product Designer for restaurants, restaurant operations consultant, inventory management specialist, purchasing workflow specialist, fiscal document designer, financial reporting specialist, JavaScript application architect and advanced HTML, CSS and Vanilla JavaScript developer.

I need you to create a complete, advanced, realistic and visually polished single-page web prototype called:

RestoStock

RestoStock is a premium SaaS prototype for restaurant management, focused on inventory control, stock batches/lots, expiration dates, FEFO stock consumption, technical recipe sheets, supplier management, supplier quotations, purchase orders, invoice entry, menu management, POS sales, delivery, table orders / comandas, automatic promotions, financial dashboard, revenue reconciliation, professional reports, user permissions, notifications, backup and audit history.

This project is for a school activity, but the final result must look like a real commercial SaaS used by restaurants, cafeterias, burger shops, bistros, bakeries, delivery kitchens and professional kitchens.

The final result must look like a finished product, not a generic demo.

==================================================
1. ABSOLUTE OUTPUT RULES
==================================================

The final result must be one single complete HTML file.

The file must be ready to save as:

index.html

And open directly in the browser.

Use only:

- HTML5;
- CSS3;
- Vanilla JavaScript.

Do not use:

- React;
- Vue;
- Angular;
- Bootstrap;
- Tailwind;
- Backend;
- Real database;
- External images;
- External CSS frameworks;
- External UI libraries;
- Placeholder text like “add here”;
- Placeholder sections;
- Pseudocode;
- Incomplete code;
- Code comments saying “continue here”;
- Markdown outside the HTML;
- Explanations outside the code.

You may use CDN only for:

- jsPDF;
- jsPDF AutoTable;
- SheetJS XLSX.

These libraries must be used for PDF and Excel export features.

The final file must start exactly with:

<!DOCTYPE html>

The final file must end exactly with:

</html>

Do not wrap the final HTML in triple backticks.
Do not explain what you did.
Do not say “continues”.
Do not cut the code.
Do not omit screens.
Do not leave main buttons without function.
Do not create buttons that call missing functions.
Do not create empty screens.
Do not create inconsistent financial data.
Do not create broken navigation.
Do not create a generic layout.
Do not transform the project into an overloaded ERP.
Do not make the interface polluted or confusing.

The final code must run without JavaScript console errors.

==================================================
2. TARGET QUALITY
==================================================

The final project must be equivalent to a 1000/1000 school prototype.

It must demonstrate:

- clear system proposal;
- professional interface;
- realistic restaurant inventory logic;
- coherent data;
- working navigation;
- working user roles;
- working permissions;
- working sales;
- working delivery;
- working table orders;
- working stock control;
- working invoice entry;
- working PDF and Excel exports;
- reliable financial values;
- convincing reports;
- clean responsive layout.

The result must look like a real SaaS prototype that could be presented to a teacher, client or evaluator.

==================================================
3. MAIN PROJECT CONCEPT
==================================================

Create a complete restaurant SaaS prototype.

The business flow must feel connected:

Supplier quotations
→ Purchase order
→ Invoice entry
→ Stock batch / lot creation
→ Inventory update
→ Recipe cost calculation
→ Menu price and margin calculation
→ Sale / delivery / table order
→ FEFO stock consumption
→ Automatic promotion suggestion for expiring batches
→ Revenue registration
→ Faturamento dashboard
→ Revenue reconciliation
→ Professional reports and exports
→ Audit log.

Every module must connect to another module.

Examples:

- Suppliers must be used in purchases and invoices.
- Purchases must use supplier quotations.
- Invoices must create stock batches / lots.
- Stock batches must update inventory quantities.
- Stock batches must have expiration dates.
- Expiring batches must generate alerts and promotions.
- Recipes must use inventory products.
- Menu dishes must be linked to recipes.
- Sales must use menu dishes.
- Sales must consume recipe ingredients using FEFO.
- Delivery orders must support multiple items.
- Table orders / comandas must support multiple items.
- Closed table orders must enter revenue.
- Open table orders must not enter revenue.
- Delivered delivery orders must enter revenue.
- Pending delivery orders must not enter revenue.
- Faturamento and Conferência de Faturamento must use the same revenue base.
- Reports must use the same revenue base as financial reconciliation.
- Audit log must register important actions.

The system must not feel like isolated screens.

==================================================
4. IMPORTANT FIDELITY TO THE CURRENT RESTOSTOCK FILE
==================================================

This prompt must recreate the current RestoStock project style and structure.

Important fidelity rules:

1. The sidebar must NOT show all modules as normal menu items.
2. The sidebar must show “Atalhos principais”.
3. The sidebar must show only 6 main shortcuts at a time.
4. Extra functions must stay inside “Central do Sistema”.
5. The sidebar footer note must explain:
   “Menu com 6 atalhos principais. As funções extras ficam na Central do Sistema com busca e favoritos.”
6. The Central do Sistema must contain all secondary tools, modules, reports, fiscal tools, suppliers, promotions, audit and advanced features.
7. The user must be able to access extra modules through the Central do Sistema.
8. The Central do Sistema must include search and favorite modules.
9. The topbar must include global search.
10. The global search must find products, recipes, sales, reports, modules and tools.
11. The project must use a single-page application style, changing screens without reload.
12. The project must have a visible premium restaurant SaaS interface.
13. The project must preserve the current idea of cards, drawers, modals, toast notifications and dynamic screens.
14. The project must use realistic mock data.
15. The project must preserve the main localStorage key:
    restostock_novo

The project must feel like an improved version of the current RestoStock file, not a completely different app.

==================================================
5. SCHOOL ACTIVITY REQUIREMENTS
==================================================

The prototype must clearly demonstrate a system for inventory control.

It must explicitly show:

1. Users;
2. User roles;
3. Permissions;
4. Features;
5. Screens;
6. Indicators / KPIs;
7. Reports;
8. Mock data;
9. Data exports;
10. Business logic;
11. Relationship between modules.

The main school activity requirement is:

Create a prompt to generate a prototype of an inventory control system.

The generated prototype must include:

- Users;
- Functionalities;
- Screens;
- Indicators;
- Reports.

Therefore, make these items obvious in the interface.

==================================================
6. VISUAL IDENTITY
==================================================

Create a premium, modern, gastronomic and professional interface.

The design must look like a real SaaS dashboard.

Visual inspiration:

- Restaurant ERP;
- Premium inventory dashboard;
- Professional financial dashboard;
- Restaurant management platform;
- Coffee shop management software;
- Modern SaaS admin panel.

Color identity:

- Coffee;
- Wood;
- Cream;
- Caramel;
- Gold;
- Brown;
- Beige;
- Green for success;
- Red for alerts;
- Yellow for warnings;
- Blue for information.

Interface must include:

- Dark fixed sidebar;
- Light content area;
- Light and dark theme;
- Rounded cards;
- Soft shadows;
- Subtle gradients;
- Elegant buttons;
- Status badges;
- KPI cards;
- Data tables;
- Form cards;
- Large modals;
- Side drawers;
- Toast notifications;
- Notification panel;
- Mobile bottom navigation;
- Responsive layout;
- Smooth microinteractions;
- Professional report previews;
- Clean forms above tables;
- Clear data hierarchy;
- Premium dashboard look.

Avoid:

- Flat ugly layout;
- Plain HTML tables only;
- Too many blocks stacked without spacing;
- Broken card layout;
- Poor contrast;
- Hard-to-read values;
- Decorative buttons without action;
- White text on light background;
- Dark text on dark background;
- Overly generic stock photos;
- External images.

Use CSS, emojis, gradients and inline SVGs for visuals.

Required CSS variables:

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

Also create:

body.dark

Dark theme must affect:

- Body background;
- Sidebar;
- Topbar;
- Cards;
- Texts;
- Tables;
- Forms;
- Inputs;
- Selects;
- Modals;
- Drawers;
- Toasts;
- Badges;
- Bottom navigation;
- Notification panel;
- Report cards;
- Invoice preview;
- Charts;
- Buttons.

The light theme must not have white text on a white background.
The dark theme must not have dark text on a dark background.

==================================================
7. GENERAL PAGE STRUCTURE
==================================================

The HTML must contain:

1. Skip link:
Text:
“Pular para o conteúdo principal”

2. Main container:
Class:
.app

3. Sidebar:
- fixed on desktop;
- drawer on mobile;
- width: 260px;
- dark background;
- logo;
- RestoStock name;
- subtitle:
“Gestão inteligente para restaurantes”;
- active user role selector;
- section title:
“Atalhos principais”;
- dynamic main navigation with 6 shortcuts;
- locked states;
- footer note explaining that extra functions are in Central do Sistema.

4. Main:
- content area;
- sticky topbar;
- dynamic screens;
- no page reload.

5. Topbar:
- mobile menu button;
- current screen title;
- current screen subtitle;
- global search input;
- notification button;
- light/dark theme toggle;
- main action button.

6. Notification panel:
- opens when clicking notification button;
- closes when clicking outside;
- closes with Escape;
- shows unread count;
- has “Marcar como lidas” button;
- has notification cards;
- each notification has “Ver detalhes” button;
- “Ver detalhes” must navigate to related module.

7. Mobile bottom navigation:
Visible only on mobile.

Items:

- Dashboard;
- Estoque;
- Ficha Técnica;
- Vendas;
- Mais.

The “Mais” button must open a drawer with:

- Cardápio;
- Delivery;
- Mesas / Comandas;
- Compras;
- Nota Fiscal;
- Fornecedores;
- Promoções;
- Relatórios;
- Faturamento;
- Conferência de Faturamento;
- Usuários;
- Configurações;
- Central do Sistema.

==================================================
8. SIDEBAR AND CENTRAL DO SISTEMA
==================================================

The sidebar must have only 6 main shortcuts.

The default 6 main shortcuts for Administrador / Dono and Gerente should be:

1. Dashboard;
2. Estoque;
3. Ficha Técnica;
4. Cardápio;
5. Vendas;
6. Central do Sistema.

Do not place every module directly in the sidebar.

The sidebar must have a text note:

“Menu com 6 atalhos principais. As funções extras ficam na Central do Sistema com busca e favoritos.”

The Central do Sistema must work as the main hub for the rest of the system.

Central do Sistema must include:

- Search input;
- Favorite modules;
- Operational modules;
- Fiscal modules;
- Financial modules;
- Reports;
- Settings;
- Audit;
- User management.

Central do Sistema cards must include:

1. Delivery;
2. Mesas / Comandas;
3. Compras;
4. Nota Fiscal;
5. Fornecedores;
6. Promoções;
7. Relatórios;
8. Faturamento;
9. Conferência de Faturamento;
10. Usuários;
11. Configurações;
12. Backup;
13. Auditoria;
14. Lotes e Validades;
15. Movimentações de Estoque;
16. Cotações por Fornecedor;
17. Central de Módulos;
18. Reservas;
19. Financeiro avançado;
20. Multiunidades;
21. Integração fiscal;
22. Programa de fidelidade;
23. App da cozinha;
24. BI gerencial.

Each Central card must have:

- icon;
- title;
- description;
- status;
- category;
- favorite button;
- open button;
- functionId.

Status:

- Ativo;
- Disponível;
- Bloqueado;
- Em breve.

If a role does not have permission:

- keep card visible;
- show locked state;
- show lock icon;
- reduce opacity;
- prevent click;
- show toast:
“Você não tem permissão para acessar este módulo.”

Central do Sistema must support:

- filtering by text;
- filtering by category;
- favorite/unfavorite;
- opening a module as a screen, modal or drawer;
- locked module feedback;
- visible permission status.

==================================================
9. USER ROLES
==================================================

Create exactly these user roles:

1. Administrador / Dono
2. Gerente
3. Atendente / Caixa
4. Cozinheiro
5. Estoquista

Each role must have:

- id;
- icon;
- name;
- short description;
- avatar visual;
- permissions array;
- financial visibility level;
- allowed shortcuts;
- allowed Central modules;
- restricted actions.

Role details:

Administrador / Dono:
- full access;
- can create users;
- can edit users;
- can delete users;
- can block users;
- can unblock users;
- can change user roles;
- can view all financial data;
- can edit permissions visually;
- can access settings;
- can export reports;
- can activate modules;
- can restore mock data;
- can clear localStorage;
- can view audit log.
- sidebar shortcuts: Dashboard, Estoque, Ficha Técnica, Cardápio, Vendas, Central do Sistema.

Gerente:
- can access dashboard;
- can access inventory;
- can access lots;
- can access recipes;
- can access menu;
- can access sales;
- can access delivery;
- can access table orders;
- can access purchases;
- can access suppliers;
- can access promotions;
- can access reports;
- can access faturamento;
- can access revenue reconciliation;
- cannot delete users;
- cannot clear all data;
- cannot access sensitive reset actions.
- sidebar shortcuts: Dashboard, Estoque, Ficha Técnica, Cardápio, Vendas, Central do Sistema.

Atendente / Caixa:
- can access summary dashboard;
- can access sales;
- can access delivery;
- can access table orders;
- can access menu;
- can consult inventory availability;
- can close table orders;
- can register payments;
- cannot view unit cost;
- cannot view inventory total value;
- cannot view recipe cost;
- cannot view profit margin;
- cannot edit recipes;
- cannot access purchases;
- cannot access suppliers;
- cannot access advanced reports;
- cannot access settings.
- sidebar shortcuts: Dashboard, Vendas, Cardápio, Delivery, Mesas / Comandas, Central do Sistema.

Cozinheiro:
- can access recipes;
- can view preparation steps;
- can view ingredients;
- can view menu;
- can view ingredient availability;
- can view allergens;
- can view yield;
- can view operational notes;
- cannot view recipe cost;
- cannot view profit;
- cannot view margin;
- cannot view suggested price;
- cannot access sales financial data;
- cannot access reports;
- cannot access purchases;
- cannot access invoice screen.
- sidebar shortcuts: Dashboard, Ficha Técnica, Cardápio, Estoque, Central do Sistema, Configurações básicas.

Estoquista:
- can access inventory;
- can access stock batches;
- can access expiration dates;
- can access stock movements;
- can access purchases;
- can access suppliers;
- can access invoice entry;
- can access alerts;
- can access stock reports;
- cannot access sales financial reports;
- cannot access sensitive settings;
- cannot edit users.
- sidebar shortcuts: Dashboard, Estoque, Compras, Nota Fiscal, Fornecedores, Central do Sistema.

Data visibility rules:

If a value is restricted by role, show:

“Restrito pelo perfil”

For Atendente / Caixa, hide:

- unit cost;
- stock value;
- recipe cost;
- profit;
- margin;
- purchase costs;
- supplier pricing.

For Cozinheiro, hide:

- cost;
- profit;
- margin;
- suggested price;
- financial reports.

For Estoquista, hide:

- sales revenue;
- profit by dish;
- financial dashboard details.

==================================================
10. USER MANAGEMENT SCREEN
==================================================

Create a screen called:

“Usuários”

Only Administrador / Dono can fully edit users.

This screen may be opened through Central do Sistema.

Layout:

- summary cards at top;
- user registration/edit form below the summary;
- user table below the form.

Summary cards:

- Total de usuários;
- Usuários ativos;
- Usuários bloqueados;
- Perfis cadastrados;
- Último acesso registrado.

User form fields:

- Nome completo;
- Email;
- Perfil;
- Status;
- Senha temporária simulada;
- Observações.

User table columns:

- Nome;
- Email;
- Perfil;
- Status;
- Último acesso;
- Ações.

Actions:

- Adicionar usuário;
- Editar usuário;
- Bloquear usuário;
- Desbloquear usuário;
- Excluir usuário;
- Alterar perfil.

When non-admin tries to edit users, show toast:

“Somente o Administrador / Dono pode alterar usuários.”

User status:

- Ativo;
- Bloqueado;
- Pendente.

Validation:

- name required;
- email required;
- duplicated email not allowed;
- role required.

==================================================
11. JAVASCRIPT ARCHITECTURE
==================================================

Use organized Vanilla JavaScript.

The architecture must be close to the current RestoStock file.

Create:

state:
- settings;
- data;
- activeScreen;
- activeProfile;
- selectedRecipe;
- selectedSupplier;
- selectedInvoice;
- selectedReport;
- selectedBatch;
- selectedUser;
- stockFilters;
- recipeFilters;
- reportFilters;
- purchaseFilters;
- promotionFilters;
- invoiceDraft;
- cart;
- deliveryCart;
- activeTableOrder;
- activeRecipeTab;
- notificationOpen;
- moreDrawerOpen.

state.settings must include:

- theme;
- density;
- reduceMotion;
- activeProfile;
- expiryAlertDays;
- allowNegativeStock;
- serviceFee;
- currency;
- restaurantName;
- restaurantCNPJ;
- restaurantAddress;
- restaurantPhone;
- restaurantEmail.

state.data must include:

- products;
- stockBatches;
- stockMovements;
- recipes;
- sales;
- deliveryOrders;
- tableOrders;
- purchases;
- suppliers;
- supplierQuotations;
- invoiceEntries;
- promotions;
- reports;
- users;
- modules;
- actionLog;
- notifications;
- losses;
- goals.

Important naming compatibility:

Use the current file style as much as possible:

- products instead of stock;
- stockBatches instead of only stockLots;
- stockMovements or moves for stock movements;
- invoiceEntries for invoices;
- actionLog for audit log;
- restostock_novo as the main localStorage key.

You may also create aliases for cleaner names, but the main data structure must remain compatible with the current file style.

Required helper functions:

- money;
- number;
- safeText;
- todayISO;
- formatCurrency;
- formatPercent;
- formatDate;
- formatDateTime;
- createId;
- daysTo;
- daysUntil;
- stockStatus;
- statusClass;
- batchStatus;
- calcMargin;
- calcAverageCost;
- calcInventoryValue;
- recipeCost;
- recipeCostStatic;
- recipeMargin;
- calcPromotionPrice;
- calcServiceFee;
- calcInvoiceTotals;
- calcRevenueTotals;
- metrics;
- alerts;
- toast;
- save;
- load;
- addLog;
- auditAction;
- renderEmptyState;
- maskRestrictedValues;
- validateRequired;
- validatePositiveNumber;
- confirmedSales;
- salesForReport;
- salesInCurrentMonth;
- salesInCurrentWeek;
- salesInCurrentDay;
- getConfirmedTransactions;
- groupByPaymentMethod;
- groupByChannel;
- reconciliationRows;
- getRecipeIngredientsUsage;
- activeLots;
- consumeStockFEFO.

Required render functions:

- renderAll;
- renderProfile;
- renderSidebar;
- renderTopbar;
- renderNotifications;
- renderDashboard;
- renderStock;
- renderStockBatches;
- renderStockMovements;
- renderRecipes;
- renderRecipePanel;
- renderMenu;
- renderSales;
- renderDelivery;
- renderTableOrders;
- renderPurchases;
- renderInvoices;
- renderSuppliers;
- renderPromotions;
- renderReports;
- renderFaturamento;
- renderRevenueReconciliation;
- renderUsers;
- renderModules;
- renderSettings;
- renderActionLog;
- renderCentralSystem;
- renderMoreDrawer.

Required action functions:

- go;
- openFeature;
- canUseFunction;
- setProfile;
- toggleRoleMenu;
- toggleTheme;
- toggleDensity;
- toggleReduceMotion;
- toggleSidebar;
- openModal;
- closeModal;
- openDrawer;
- closeDrawer;
- openMoreDrawer;
- closeMoreDrawer;
- openGlobalSearch;
- selectRecipe;
- saveRecipe;
- editRecipe;
- deleteRecipe;
- updateCart;
- finishSale;
- updateDeliveryCart;
- finishDeliveryOrder;
- openTableOrder;
- addItemToTableOrder;
- closeTableOrder;
- confirmCloseTableOrder;
- transferTableOrder;
- cancelTableItem;
- registerStockMovement;
- openStockLots;
- openLotsFeature;
- importInvoice;
- saveInvoice;
- generateInvoicePDF;
- exportPDF;
- exportExcel;
- printRecipe;
- exportInventoryExcel;
- exportInventoryPDF;
- exportLotsPDF;
- exportRecipesExcel;
- exportSelectedRecipePDF;
- exportReportPDF;
- exportReportExcel;
- exportRevenueReconciliationPDF;
- exportFaturamentoPDF;
- applyAutomaticPromotions;
- activatePromotion;
- endPromotion;
- openPromotionsFeature;
- suggestBestSupplier;
- saveSupplier;
- savePurchase;
- markPurchaseReceived;
- addUser;
- editUser;
- blockUser;
- unblockUser;
- deleteUser;
- exportBackup;
- importBackupFile;
- resetData;
- clearSavedData;
- markNotificationsAsRead;
- openNotificationTarget;
- runSystemCheck;
- validateV7Data.

Use event delegation where possible, but inline onclick is acceptable if all functions exist.

Important:

- every data-action must trigger an existing function;
- every onclick must call an existing function;
- every button must work or show a meaningful simulated toast;
- no undefined functions;
- no JavaScript console errors;
- no duplicate IDs;
- no broken navigation.

==================================================
12. LOCAL STORAGE
==================================================

Use the main localStorage key:

restostock_novo

This key must save:

- settings;
- data.

Example structure:

{
  settings: { ... },
  data: { ... }
}

Also create auxiliary separated localStorage keys for compatibility and visibility:

restostock.theme
restostock.density
restostock.reduceMotion
restostock.activeRole
restostock.recipes
restostock.stock
restostock.sales

But the main source of truth must remain:

restostock_novo

Do not remove restostock_novo.

On page load:

- try to load restostock_novo;
- if it exists, merge saved settings and data;
- if it does not exist, use initialData();
- then run ensureCollections();
- then validateV7Data();
- then apply theme and density;
- then render all screens.

Settings screen must allow:

- export backup JSON;
- import backup JSON;
- restore mock data;
- clear saved data.

Backup JSON must export:

{
  settings,
  data
}

==================================================
13. DASHBOARD SCREEN
==================================================

Create an executive dashboard.

Hero card:

Badge:
“Operação em tempo real”

Title:
“Bem-vindo ao RestoStock”

Text:
“Controle estoque, fichas técnicas, compras, vendas, notas fiscais, comandas, promoções e relatórios em uma única plataforma.”

Tags:

- Estoque inteligente;
- Lotes e validade;
- Fichas padronizadas;
- FEFO automático;
- Faturamento conferido;
- Promoções automáticas.

Required KPI cards:

1. Vendas do dia;
2. Pedidos;
3. Valor em estoque;
4. Insumos críticos;
5. Lotes vencendo;
6. Lotes vencidos;
7. Promoções ativas;
8. Faturamento do mês;
9. Margem média;
10. Fichas ativas;
11. Comandas abertas;
12. Notas fiscais recebidas.

Each KPI must include:

- icon;
- label;
- value;
- subtitle;
- status indicator;
- visual detail.

Dashboard sections:

1. Quick actions:

- Nova entrada de estoque;
- Importar nota fiscal;
- Nova ficha técnica;
- Registrar venda;
- Novo pedido delivery;
- Abrir comanda;
- Pedido de compra;
- Exportar relatório;
- Ver alertas.

2. Operational alerts:

- critical stock;
- expiring batches;
- expired batches;
- pending purchases;
- low margin recipes;
- active promotions;
- open table orders;
- revenue divergence if any.

3. Visual charts:

- horizontal bars for consumption by category;
- donut chart for revenue by channel;
- payment method list;
- recent activity timeline;
- top ingredients by consumption;
- expiring batches progress bars.

4. Revenue preview:

- daily revenue;
- weekly revenue;
- monthly revenue;
- payment method total;
- channel total;
- reconciliation status.

All values must be coherent.

==================================================
14. FATURAMENTO SCREEN
==================================================

Create a specific screen called:

“Faturamento”

This screen is different from “Conferência de Faturamento”.

Faturamento is the financial overview dashboard.

Conferência de Faturamento is the validation/reconciliation screen.

The Faturamento screen must show:

- Faturamento do dia;
- Faturamento da semana;
- Faturamento do mês;
- Ticket médio;
- Total de pedidos pagos;
- Faturamento por forma de pagamento;
- Faturamento por canal;
- Últimas vendas confirmadas;
- Vendas canceladas;
- Comandas abertas não contabilizadas;
- Delivery pendente não contabilizado.

Important:

The payment method total must use the same period as the selected faturamento card.

If the screen shows “Faturamento do mês”, the payment method chart must also show the month.
If the screen shows “Faturamento da semana”, the payment method chart must also show the week.
If the screen shows “Faturamento do dia”, the payment method chart must also show the day.

Never show a contradiction such as:

Debit + Credit + Pix = R$ 3.400
but Faturamento do mês = R$ 1.400

unless the period filter visibly explains the difference.

Faturamento must have filters:

- Hoje;
- Últimos 7 dias;
- Mês atual;
- Personalizado.

When filter changes, update:

- KPI cards;
- payment method chart;
- channel chart;
- sales table;
- total revenue.

==================================================
15. CONFERÊNCIA DE FATURAMENTO SCREEN
==================================================

Create screen or Central feature:

“Conferência de Faturamento”

Purpose:

Ensure revenue values are coherent.

This screen must show:

- gross revenue;
- daily revenue;
- weekly revenue;
- monthly revenue;
- revenue by payment method;
- revenue by channel;
- counter sales;
- delivered delivery orders;
- closed table orders;
- canceled sales;
- open table orders not counted;
- validation status.

Important rule:

All revenue blocks must use the same selected period and same confirmed transaction base.

Confirmed transactions:

- finished POS sales;
- delivered delivery orders;
- closed table orders.

Not counted:

- canceled sales;
- canceled delivery;
- open table orders;
- pending delivery;
- draft purchases;
- invoices not related to sales.

Payment method total must always match revenue total for the selected period.

Show validation line:

“Total por formas de pagamento = Total faturado no período”

If correct:

“Conferência correta”

If incorrect:

“Divergência encontrada”

Do not allow contradictions like:

payment methods total = R$ 3.400
monthly revenue = R$ 1.400

unless filters are clearly different and visibly labeled.

The reconciliation screen must also show:

- list of counted transactions;
- list of ignored transactions;
- reason why each ignored transaction was not counted;
- validation badge;
- export PDF button.

==================================================
16. INVENTORY SCREEN
==================================================

Create a complete inventory screen.

Use products array as the main inventory collection.

Hero:

Badge:
“Controle de insumos”

Title:
“Estoque Inteligente”

Description:
“Acompanhe estoque total, lotes, custos, validade, fornecedores, notas fiscais e impacto dos insumos nas fichas técnicas.”

Buttons:

- Nova entrada;
- Ajustar estoque;
- Importar NF;
- Exportar Excel;
- Exportar PDF.

Summary cards:

- Total de insumos;
- Valor total em estoque;
- Itens críticos;
- Lotes vencendo;
- Lotes vencidos;
- Custo médio;
- Entradas no mês;
- Saídas no mês.

Filters:

- search by product;
- category;
- status;
- batch status;
- supplier;
- expiration range;
- sorting.

Inventory table columns:

- Insumo;
- Categoria;
- Estoque total;
- Unidade;
- Estoque mínimo;
- Custo médio;
- Valor em estoque;
- Fornecedor principal;
- Validade mais próxima;
- Status;
- Ações.

Actions:

- Entrada;
- Saída;
- Ajustar;
- Ver lotes;
- Editar.

Status:

- Normal;
- Estoque baixo;
- Crítico;
- Sem estoque;
- Próximo do vencimento;
- Vencido.

Stock movement drawer/modal fields:

- Item;
- Tipo de movimentação;
- Quantidade;
- Motivo;
- Observação;
- Perfil responsável.

Movement types:

- Entrada;
- Saída;
- Ajuste.

Validation:

- no negative stock unless allowNegativeStock is true;
- no zero quantity;
- no missing item;
- no invalid date;
- no blank reason for adjustment.

==================================================
17. INITIAL INVENTORY DATA
==================================================

The current RestoStock file is closer to a restaurant / burger shop operational inventory, so use realistic products for that type of restaurant.

Default inventory must include at least 20 products, mixing restaurant ingredients and operational items.

Include products such as:

- Pão brioche;
- Hambúrguer 180g;
- Queijo cheddar;
- Bacon;
- Alface americana;
- Tomate;
- Cebola roxa;
- Batata congelada;
- Óleo de fritura;
- Molho especial;
- Ketchup;
- Maionese;
- Refrigerante lata;
- Água mineral;
- Café especial;
- Leite;
- Chocolate meio amargo;
- Farinha de trigo;
- Ovos;
- Arroz arbóreo;
- Cogumelos frescos;
- Salmão;
- Spaghetti;
- Queijo parmesão;
- Azeite;
- Camarão;
- Leite de coco;
- Alho;
- Cebola.

Each product must have:

- id;
- name;
- category;
- unit;
- qty;
- min;
- cost;
- supplier;
- expiry;
- observations.

Categories should include:

- Carnes;
- Hortifruti;
- Laticínios;
- Mercearia;
- Panificação;
- Bebidas;
- Sobremesas;
- Massas;
- Peixes;
- Embalagens.

Units should include:

- kg;
- g;
- un;
- L;
- ml;
- pacote;
- caixa;
- fatias.

==================================================
18. STOCK BATCHES / LOTS
==================================================

Create a separate stockBatches array.

Each stock batch must have:

- id;
- productId;
- product;
- lot;
- remaining;
- originalQty;
- unit;
- unitCost;
- supplier;
- invoice;
- expiry;
- entryDate;
- status;
- observations.

Batch status calculation:

Normal:
- more than expiryAlertDays until expiration.

Próximo do vencimento:
- 1 to expiryAlertDays days until expiration.

Vencido:
- expiration date before today.

Consumido:
- remaining quantity equals 0.

The batches panel must show:

- product;
- lot number;
- supplier;
- remaining quantity;
- original quantity;
- unit cost;
- expiration date;
- days until expiration;
- origin document;
- status;
- actions.

Batch actions:

- Consumir;
- Ajustar;
- Ver nota fiscal;
- Promover pratos relacionados.

The system must show a visual warning when:

- batch expires soon;
- batch is already expired;
- batch quantity is very low;
- batch is fully consumed.

==================================================
19. FEFO STOCK CONSUMPTION
==================================================

Implement FEFO:

First Expire, First Out.

When a POS sale, delivery order or table order is completed:

1. Identify sold menu items.
2. Find linked recipe.
3. Find recipe ingredients.
4. Find related inventory products.
5. Find available stock batches.
6. Sort batches by expiration date ascending.
7. Consume from the batch that expires first.
8. If quantity is insufficient, consume remaining quantity from next batch.
9. Register stock movement.
10. Update batch remaining quantity.
11. Update product qty.
12. Update average cost if needed.
13. Audit the action.
14. Show toast.

If there is not enough stock:

- show warning toast;
- still allow simulated sale only if user confirms;
- mark stock issue in actionLog.

If an expired batch would be consumed:

- show confirm() warning:
“Este lote está vencido. Deseja continuar nesta simulação?”

==================================================
20. INVOICE ENTRY SCREEN
==================================================

Create a screen or Central feature called:

“Nota Fiscal”

Purpose:
Register fictional invoices and automatically add stock batches.

The screen must allow:

- manual invoice entry;
- automatic invoice simulation;
- supplier selection;
- invoice item table;
- tax calculation;
- invoice preview;
- invoice PDF export;
- automatic stock batch creation.

Layout:

Top area:
- invoice form;
- supplier selection;
- invoice metadata;
- action buttons.

Middle area:
- product item table;
- add/remove item controls;
- tax summary.

Bottom area:
- invoice preview in Modelo 1 style;
- save/import/export buttons.

Show clearly:

“Documento fictício sem valor fiscal.”

Invoice structure must follow “Nota Fiscal Modelo 1” style.

Required sections:

1. Header:

- “NOTA FISCAL MODELO 1”
- Nota Fiscal Nº
- Saída / Entrada
- 1ª via
- Data de emissão
- Hora de emissão
- Documento fictício sem valor fiscal

2. Emitente:

- Nome / Razão Social
- Endereço
- Bairro / Distrito
- Município
- UF
- Fone / Fax
- CEP
- CNPJ
- Inscrição Estadual

3. Destinatário / Remetente:

- Nome / Razão Social
- CNPJ / CPF
- Endereço
- Bairro / Distrito
- CEP
- Município
- Fone / Fax
- UF
- Inscrição Estadual

4. Natureza da Operação:

- Natureza da operação
- CFOP
- Inscrição Estadual do Substituto Tributário
- Data limite para emissão

5. Fatura:

- Número
- Vencimento
- Valor

6. Dados do Produto:

Columns:

- Código
- Descrição dos produtos
- Classificação fiscal
- Situação tributária
- Unidade
- Quantidade
- Valor unitário
- Valor total
- Alíquota ICMS
- Alíquota IPI
- Valor do IPI

7. Cálculo do Imposto:

- Base de cálculo do ICMS
- Valor do ICMS
- Base de cálculo ICMS substituição
- Valor do ICMS substituição
- Valor total dos produtos
- Valor do frete
- Valor do seguro
- Outras despesas acessórias
- Valor total do IPI
- Valor total da nota

8. Transportador / Volumes Transportados:

- Nome / Razão Social
- Frete por conta
- Placa do veículo
- UF
- CNPJ / CPF
- Endereço
- Município
- Inscrição Estadual
- Quantidade
- Espécie
- Marca
- Número
- Peso bruto
- Peso líquido

9. Dados Adicionais:

- Informações complementares
- Reservado ao fisco
- Número de controle do formulário
- Dados da AIDF e do impressor

10. Receipt section:

- “Recebemos os produtos constantes da nota fiscal indicada ao lado”
- Data do recebimento
- Identificação e assinatura do recebedor.

When saving an invoice:

- create invoice entry in invoiceEntries;
- create stock batches for each item;
- update product quantity;
- update average cost;
- register stock movements;
- update supplier history;
- add actionLog entry;
- show toast.

Invoice PDF requirements:

- use jsPDF;
- use AutoTable for product table;
- look like a formal invoice;
- may have more than one page;
- repeat important header data on new pages;
- include page numbers;
- include “Documento fictício sem valor fiscal”;
- include all required sections;
- if products exceed one page, continue table on the next page.

==================================================
21. SUPPLIERS SCREEN
==================================================

Create a professional suppliers screen.

This screen may open through Central do Sistema.

Layout rule:

- editing / registration form at the top;
- table below.

Do not use ugly stacked supplier blocks.
Do not use random cards for each supplier if it makes editing messy.

Top summary cards:

- Total de fornecedores;
- Fornecedores ativos;
- Prazo médio;
- Melhor avaliação;
- Cotações válidas.

Supplier form fields:

- Nome do fornecedor;
- CNPJ fictício;
- Contato;
- Telefone;
- Email;
- Endereço;
- Cidade;
- Estado;
- Prazo de entrega;
- Pedido mínimo;
- Categorias principais;
- Status;
- Observações.

Supplier table columns:

- Fornecedor;
- CNPJ;
- Contato;
- Telefone;
- Email;
- Categorias;
- Prazo;
- Pedido mínimo;
- Status;
- Ações.

Actions:

- Editar;
- Ver cotações;
- Desativar;
- Excluir.

Supplier status:

- Ativo;
- Em avaliação;
- Bloqueado;
- Inativo.

==================================================
22. SUPPLIER QUOTATIONS
==================================================

Create supplierQuotations array.

Each quotation must have:

- id;
- supplierId;
- supplier;
- productId;
- product;
- unitCost;
- deliveryTime;
- minimumOrder;
- validityDate;
- qualityRating;
- lastPurchaseDate.

In purchases, when selecting product and supplier:

- automatically fill unit cost;
- automatically fill delivery time;
- automatically fill minimum order;
- calculate estimated total;
- show supplier quality rating.

Function:

suggestBestSupplier

Must recommend best supplier based on:

- lowest unit cost;
- shortest delivery time;
- highest quality rating;
- valid quotation;
- minimum order compatibility.

Show suggestion box:

“Melhor opção sugerida: [Fornecedor] — melhor custo-benefício.”

==================================================
23. PURCHASES SCREEN
==================================================

Create a purchases screen.

This screen may open through Central do Sistema.

Layout rule:

- purchase form at the top;
- purchase table below.

Top summary cards:

- Pedidos em aberto;
- Pedidos aprovados;
- Pedidos recebidos;
- Pedidos atrasados;
- Valor previsto.

Purchase form fields:

- Fornecedor;
- Produto;
- Quantidade;
- Unidade;
- Valor unitário automático;
- Prazo de entrega automático;
- Pedido mínimo automático;
- Data prevista;
- Status;
- Observações.

When supplier and product are selected:

- automatically fill unit cost;
- automatically fill delivery time;
- automatically fill minimum order;
- calculate total;
- show best supplier suggestion.

Purchase table columns:

- Pedido;
- Fornecedor;
- Produto;
- Quantidade;
- Unidade;
- Valor unitário;
- Valor total;
- Data prevista;
- Status;
- Ações.

Status:

- Rascunho;
- Enviado;
- Aprovado;
- Recebido;
- Atrasado.

Actions:

- Editar;
- Aprovar;
- Marcar como recebido;
- Gerar nota fiscal;
- Exportar.

When purchase is marked as “Recebido”:

- allow generating invoice entry;
- allow creating stock batch;
- update purchase status;
- add actionLog entry.

==================================================
24. TECHNICAL RECIPE SHEET SCREEN
==================================================

Create a rich screen called:

“Ficha Técnica”

This is one of the most important and beautiful parts of the system.

Use recipes array.

The system may contain burger shop recipes and restaurant recipes.

Include at least these recipes:

- Burger Artesanal;
- X-Bacon Artesanal;
- X-Salada;
- Batata Frita Grande;
- Frango Grelhado;
- Strogonoff de Frango;
- Contra-filé Executivo;
- Risoto de Cogumelos;
- Salmão Grelhado;
- Spaghetti Carbonara;
- Salada Caesar;
- Brownie da Casa;
- Filé ao Molho Madeira;
- Moqueca de Peixe.

Each recipe must have:

- id;
- name;
- category;
- price;
- ingredients;
- prep;
- minutes;
- image;
- gallery;
- steps;
- active.

Each ingredient must link to a product.

Ingredient structure:

{
  product: "Nome do produto",
  qty: number
}

Recipe calculations:

- ingredient cost;
- total cost;
- cost per portion;
- profit;
- margin;
- suggested price.

Formula examples:

profit = salePrice - totalCost

margin = ((salePrice - totalCost) / salePrice) * 100

suggestedPrice = totalCost / (1 - desiredMargin)

Recipe screen layout:

Desktop:

- left side: recipe list;
- right side: sticky detail panel.

Mobile:

- single column.

Recipe list must include:

- search;
- category filter;
- status filter;
- grid/list switch;
- new recipe button.

Recipe cards must include:

- visual area using generated SVG data URI, CSS, emoji or gradient;
- category badge;
- status badge;
- name;
- short description;
- cost;
- sale price;
- margin;
- preparation time;
- details button;
- edit button.

List view rules:

- must not break cards;
- cards must occupy full width;
- image on the left and content on the right on desktop;
- single column on mobile;
- buttons must remain aligned.

Selected recipe panel tabs:

1. Ingredientes;
2. Preparo;
3. Custos.

All tabs must work.

For Cozinheiro role:

- hide cost;
- hide profit;
- hide margin;
- hide suggested price;
- show “Restrito pelo perfil.”

==================================================
25. MENU / CARDÁPIO SCREEN
==================================================

Create a beautiful menu management screen.

The menu screen must look like a real restaurant menu module.

Top summary cards:

- Pratos disponíveis;
- Pratos indisponíveis;
- Em promoção;
- Margem média;
- Alertas de ingredientes.

Toolbar:

- search;
- category filter;
- availability filter;
- promotion filter.

Each dish card must show:

- dish visual;
- name;
- category;
- normal price;
- promotional price if active;
- availability;
- margin status;
- ingredients alert;
- promotion badge;
- recipe link;
- actions.

Availability:

- Disponível;
- Indisponível;
- Sazonal;
- Em promoção.

Actions:

- Editar;
- Alterar disponibilidade;
- Ver ficha técnica;
- Ativar promoção;
- Encerrar promoção.

If recipe uses ingredient close to expiration, show:

“Promoção sugerida por validade”

Card design must be polished.

==================================================
26. AUTOMATIC PROMOTIONS
==================================================

Create promotions based on expiration dates.

promotions array must have:

- id;
- recipeId;
- products;
- reason;
- promoPrice;
- originalPrice;
- discount;
- startDate;
- endDate;
- status.

Promotion status:

- Sugerida;
- Ativa;
- Encerrada;
- Bloqueada.

Rules:

If batch expires in 5 days or less:

- suggest promotion for recipes that use that product.

If batch expires in 3 days or less:

- activate promotion automatically.

Never create promotion that makes margin negative.

If promotion reduces margin too much:

- show warning.

Promotion screen must include:

- active promotions;
- suggested promotions;
- related product;
- related batch;
- expiration date;
- original price;
- promotional price;
- margin impact;
- status;
- actions.

Actions:

- Ativar;
- Encerrar;
- Editar preço;
- Ver lote relacionado.

==================================================
27. SALES SCREEN
==================================================

Create a POS sales screen.

Do not include discount field.

Sales screen must include:

- product / recipe list;
- cart;
- quantity control;
- remove item;
- subtotal;
- service fee if applicable;
- total;
- payment method;
- sale channel;
- finish sale button.

Payment methods:

- Dinheiro;
- PIX;
- Débito;
- Crédito;
- Vale-refeição.

Sale channels:

- Balcão;
- Salão;
- Delivery;
- Mesa.

When sale is finished:

- validate cart is not empty;
- register sale;
- consume stock using FEFO;
- update reports;
- update faturamento;
- update revenue reconciliation;
- add actionLog entry;
- show toast.

Canceled sales must not count as revenue.

==================================================
28. DELIVERY SCREEN
==================================================

Create a delivery screen with multiple items per order.

A delivery order must include:

- customer name;
- phone;
- address;
- neighborhood;
- delivery fee;
- payment method;
- status;
- multiple items;
- quantities;
- subtotal;
- total.

Delivery status:

- Novo;
- Em preparo;
- Saiu para entrega;
- Entregue;
- Cancelado.

User must be able to:

- add multiple products;
- change quantity;
- remove products;
- calculate subtotal;
- calculate delivery fee;
- calculate total;
- finish order;
- change status.

Revenue rule:

Delivery only counts as revenue when status is:

- Entregue.

Canceled delivery does not count as revenue.

==================================================
29. TABLE ORDERS / COMANDAS
==================================================

Create feature:

“Mesas / Comandas”

A table order must have:

- id;
- table number;
- customer name optional;
- opening time;
- items;
- subtotal;
- service fee;
- total;
- payment method;
- status.

Status:

- Aberta;
- Em atendimento;
- Fechada;
- Cancelada.

User must be able to:

- open table order;
- select table number;
- add multiple items;
- change quantity;
- remove item;
- cancel item;
- transfer table;
- view subtotal;
- view service fee;
- close table order;
- choose payment method;
- simulate split payment.

Revenue rule:

Open table orders do not count as revenue.
Only closed table orders count as revenue.
Canceled table orders do not count as revenue.

When closing table order:

- register sale with channel “Mesa”;
- consume stock using FEFO;
- update faturamento;
- update revenue reconciliation;
- add actionLog entry;
- show toast.

==================================================
30. REPORTS SCREEN
==================================================

Create professional reports.

Reports must look like reliable business analysis.

Filters:

- period;
- channel;
- payment method;
- category;
- supplier;
- status.

Report cards:

1. Vendas por período;
2. Margem por prato;
3. Custo de estoque;
4. Curva ABC de insumos;
5. Compras por fornecedor;
6. Fichas com baixa margem;
7. Promoções ativas;
8. Lotes próximos do vencimento;
9. Consumo por ingrediente;
10. Faturamento por canal;
11. Conferência de pagamento;
12. Notas fiscais recebidas.

Each report card must have:

- title;
- description;
- indicator;
- risk/status badge;
- view button;
- export PDF button;
- export Excel button.

Report detail modal/drawer must show:

- report title;
- applied filters;
- summary;
- KPIs;
- analytical table;
- action recommendations;
- observations.

PDF report structure:

1. Cover page;
2. Report title;
3. Restaurant identification;
4. Date and time of generation;
5. Applied filters;
6. Executive summary;
7. KPIs;
8. Analytical table;
9. Visual indicators;
10. Findings;
11. Action plan;
12. Conclusion;
13. Footer with page number.

Reports may have more than one page.
PDFs must look convincing and professional.

Excel reports:

Use multiple sheets:

- Resumo;
- Dados;
- Plano de ação.

If XLSX fails, generate CSV fallback.

==================================================
31. CENTRAL DE MÓDULOS / CENTRAL DO SISTEMA
==================================================

Create:

“Central do Sistema”

This is the hub for every extra feature outside the 6 main sidebar shortcuts.

It must show:

- module search;
- favorite modules;
- categorized modules;
- locked modules;
- active modules;
- quick access cards.

Categories:

- Operação;
- Estoque;
- Fiscal;
- Financeiro;
- Relatórios;
- Administração;
- Configurações.

Modules:

- Delivery;
- Mesas / Comandas;
- Compras;
- Nota Fiscal;
- Fornecedores;
- Promoções;
- Relatórios;
- Faturamento;
- Conferência de Faturamento;
- Usuários;
- Configurações;
- Backup;
- Auditoria;
- Lotes e Validades;
- Movimentações de Estoque;
- Cotações por Fornecedor;
- Central de Módulos;
- Reservas;
- Financeiro avançado;
- Multiunidades;
- Integração fiscal;
- Programa de fidelidade;
- App da cozinha;
- BI gerencial.

Each module card must show:

- icon;
- module name;
- description;
- category;
- status;
- favorite button;
- open button;
- functionId.

Status:

- Ativo;
- Disponível;
- Bloqueado;
- Em breve.

Only Administrador / Dono can activate locked optional modules.

If another role tries to activate:

show toast:
“Somente o Administrador / Dono pode ativar módulos.”

==================================================
32. AUDIT LOG / ACTION LOG
==================================================

Create actionLog array.

Register actions:

- stock adjustment;
- stock movement;
- invoice import;
- purchase received;
- recipe edited;
- menu item changed;
- sale finished;
- delivery finished;
- table order closed;
- promotion activated;
- user edited;
- report exported;
- backup exported;
- data restored.

Action log record:

- id;
- date;
- profile;
- action;
- module;
- detail.

Show action log in Settings or Central do Sistema.

Audit table must show:

- date;
- profile;
- module;
- action;
- detail.

==================================================
33. VALIDATIONS
==================================================

Prevent invalid data.

Show toast errors for:

- negative stock;
- sale without item;
- delivery without item;
- table order without item;
- invoice without product;
- supplier without name;
- purchase without supplier;
- recipe sale price lower than cost;
- missing expiration date;
- stock movement with zero quantity;
- closing table order without payment method;
- delivery without address;
- user without email;
- duplicated user email;
- purchase quantity below minimum order;
- invoice total equal to zero;
- promotion with negative margin.

Validation examples:

“Adicione pelo menos um item antes de finalizar a venda.”
“Informe um fornecedor antes de salvar a compra.”
“Não é possível movimentar estoque com quantidade zero.”
“O preço de venda não pode ser menor que o custo da ficha.”
“A quantidade está abaixo do pedido mínimo do fornecedor.”
“Promoção bloqueada porque deixaria a margem negativa.”

==================================================
34. EXPORTS
==================================================

Required exports:

- Inventory PDF;
- Inventory Excel;
- Stock batches PDF;
- Stock movements Excel;
- Invoice PDF;
- Supplier list Excel;
- Purchase report PDF;
- Purchase report Excel;
- Recipe PDF;
- Recipe Excel;
- Sales report PDF;
- Delivery report PDF;
- Table orders report PDF;
- Promotions report PDF;
- Faturamento PDF;
- Revenue reconciliation PDF;
- Complete backup JSON.

Before exporting:

- check if jsPDF / AutoTable / XLSX are loaded.

If not loaded, show toast:

“Biblioteca de exportação ainda não carregada. Tente novamente em alguns segundos.”

PDFs must not look empty.
PDFs must have:

- title;
- date;
- company identification;
- table or structured content;
- summary;
- footer;
- page numbers when possible.

==================================================
35. SETTINGS SCREEN
==================================================

Settings screen must include:

1. Appearance:

- light/dark theme;
- compact/comfortable density;
- reduce animations.

2. Restaurant:

- restaurant name;
- fake CNPJ;
- address;
- phone;
- email;
- service fee;
- currency;
- expiry alert days;
- allow negative stock option.

3. Data:

- export backup JSON;
- import backup JSON;
- restore mock data;
- clear localStorage.

4. Permissions summary:

- list roles;
- explain permissions.

5. Audit log:

- show recent actions.

==================================================
36. RESPONSIVENESS
==================================================

Create breakpoints:

- 1250px;
- 1000px;
- 860px.

Desktop:

- fixed sidebar;
- 6 shortcut sidebar;
- Central do Sistema for extra modules;
- grid cards;
- advanced tables;
- forms above tables;
- recipe two-column layout;
- sticky recipe panel;
- readable reports.

Tablet:

- reduced grids;
- stacked panels;
- responsive forms;
- scrollable tables.

Mobile:

- sidebar becomes drawer;
- compact topbar;
- bottom navigation;
- “Mais” drawer;
- tables with horizontal scroll;
- cards in one column;
- forms above tables;
- invoice preview becomes scrollable;
- report tables become scrollable;
- modals fit screen height;
- buttons wrap without breaking.

==================================================
37. ACCESSIBILITY
==================================================

Include:

- skip link;
- input labels;
- aria-label on icon buttons;
- visible focus;
- good contrast;
- semantic buttons;
- keyboard navigation;
- reduced motion option;
- clear locked-state text;
- meaningful button labels;
- readable table headers.

==================================================
38. MOCK DATA
==================================================

Create realistic mock data directly in JavaScript.

Required:

- at least 20 inventory products;
- multiple stock batches for several products;
- at least 10 technical recipe sheets;
- at least 10 menu dishes;
- at least 6 POS sales;
- at least 5 delivery orders;
- at least 5 table orders;
- at least 5 purchase orders;
- at least 5 suppliers;
- supplier quotations;
- at least 3 invoice entries;
- at least 5 active or suggested promotions;
- at least 6 reports;
- exactly 5 user roles;
- at least 5 users;
- at least 15 Central do Sistema modules;
- actionLog entries.

Data must be coherent.

Financial data must match.

Inventory batches must connect to products.
Recipe ingredients must connect to products.
Menu dishes must connect to recipes.
Purchases must connect to suppliers.
Invoices must connect to suppliers and stock batches.
Promotions must connect to recipes, menu items and stock batches.
Sales must connect to menu items.
Faturamento must use the same source as confirmed sales, delivered delivery and closed table orders.
Revenue reconciliation must use the same source as Faturamento.

==================================================
39. REQUIRED CSS CLASSES
==================================================

Create complete styles for:

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
- .notification-panel
- .recipe-page-shell
- .recipe-board
- .recipe-sidepanel
- .recipe-card
- .recipe-detail
- .recipe-tabs
- .stock-table
- .form-grid
- .actions
- .invoice-preview
- .report-card
- .report-detail
- .supplier-form
- .purchase-form
- .promotion-card
- .audit-log
- .reconciliation-card
- .faturamento-card
- .central-grid
- .central-card
- .feature-grid
- .summary-pill
- .quick-btn

Include:

- @media print;
- responsive CSS;
- visible focus styles;
- dark theme styles;
- reduced motion styles.

==================================================
40. PRIORITY RULE IF THE ANSWER GETS TOO LARGE
==================================================

If the generated code becomes too large, never remove the core modules.

Never cut or simplify these parts:

1. Dashboard;
2. Estoque;
3. Stock batches / lots;
4. Ficha Técnica;
5. Cardápio;
6. Vendas;
7. Delivery with multiple items;
8. Mesas / Comandas with multiple items;
9. Compras;
10. Nota Fiscal Modelo 1;
11. Fornecedores;
12. Faturamento;
13. Conferência de Faturamento;
14. Relatórios;
15. Central do Sistema;
16. Perfis e permissões;
17. localStorage restostock_novo;
18. PDF/Excel exports;
19. Responsive layout.

If you must simplify something, only simplify optional modules:

- Reservas;
- Multiunidades;
- Programa de fidelidade;
- App da cozinha;
- BI gerencial;
- Financeiro avançado.

Optional modules may be represented as active/locked cards in Central do Sistema, but core modules must be functional.

Do not remove the 6-shortcut sidebar logic.
Do not remove Central do Sistema.
Do not remove Faturamento.
Do not remove Conferência de Faturamento.
Do not remove Nota Fiscal Modelo 1.
Do not remove user permissions.

==================================================
41. FINAL QUALITY CHECK
==================================================

Before delivering final HTML, internally verify and fix:

1. File starts with <!DOCTYPE html>.
2. File ends with </html>.
3. No JavaScript console errors.
4. Every data-action calls existing function.
5. Every onclick calls existing function.
6. Sidebar has only 6 main shortcuts.
7. Sidebar includes Central do Sistema.
8. Sidebar note says extra functions are in Central do Sistema.
9. Central do Sistema includes all extra modules.
10. Mobile bottom navigation works.
11. Mobile “Mais” drawer works.
12. Notifications panel works.
13. Notifications navigate to correct screens.
14. All required roles exist.
15. Permissions work.
16. Admin can edit users.
17. Non-admin cannot edit users.
18. Inventory has at least 20 products.
19. Inventory has stock batches.
20. Batch status is calculated correctly.
21. FEFO consumption works.
22. Invoice entry creates stock batches.
23. Invoice PDF follows Modelo 1 structure.
24. Supplier screen has form above table.
25. Purchase screen has form above table.
26. Purchase unit cost auto-fills by supplier quotation.
27. Best supplier suggestion works.
28. Recipes are connected to products.
29. Recipe list view does not break layout.
30. Recipe costs are calculated.
31. Cozinheiro cannot see cost/margin.
32. Menu screen looks polished.
33. Expiring batches generate promotions.
34. Promotion never creates negative margin.
35. Sales screen has no discount field.
36. Delivery supports multiple items.
37. Table orders support multiple items.
38. Table orders can be closed.
39. Open table orders do not count as revenue.
40. Delivered delivery counts as revenue.
41. Canceled sales do not count as revenue.
42. Faturamento screen exists and works.
43. Faturamento values do not contradict each other.
44. Revenue by payment method matches total revenue for same selected period.
45. Revenue reconciliation shows correct validation.
46. Reports have filters.
47. Report PDFs look professional.
48. Excel exports work or fallback CSV works.
49. Backup JSON export works.
50. Settings restore mock data works.
51. localStorage uses restostock_novo as main key.
52. Theme and density are persisted.
53. Light/dark theme works.
54. Compact/comfortable density works.
55. Reduced motion works.
56. Mobile layout works.
57. No main screen is empty.
58. No white text on white background.
59. No broken recipe list layout.
60. Sidebar does not move incorrectly on scroll.
61. Notification button opens and navigates correctly.
62. Payment method totals match selected-period revenue.
63. Invoice entry does not generate empty batches.
64. Purchase received can generate invoice.
65. Delivery order with multiple items calculates correctly.
66. Table order with multiple items calculates correctly.
67. Central do Sistema search works.
68. Global search works.
69. User role switch updates permissions visually.
70. Restricted values show “Restrito pelo perfil”.
71. Export buttons show friendly toast if libraries are not loaded.
72. The system still looks clean and usable, not like a polluted ERP.

If any item fails, fix before delivering.

==================================================
42. FINAL DELIVERY
==================================================

Create everything from scratch.
Do not request files.
Do not ask for references.
Do not use external images.
Do not use frameworks.
Do not create a generic interface.
Do not create only one screen.
Do not leave main buttons without function.
Do not cut the code.
Do not write explanations outside the HTML.

The final result must look like a real SaaS, complete, beautiful, responsive and functional for restaurant inventory management.

Deliver only the complete HTML code.
```
