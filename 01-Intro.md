## Ionic V3

Comandos básicos
- ionic generate page <name_page>.
- ionic generate component <name_component>.

### NgModule (decorator).

  - Decorator.
  - Metadados.
    - Declarations: Component, Pipe, Diretivas e Páginas.
    - EntryComponents: Páginas ( apenas ).
    - Providers: Services.
    
### Página x Component.

  - Component.
    - src/components ( folder ).
    - .html, .scss, .ts ( arquivos ).
    - adicionar no @NgModule em declarations ````<nome_component></nome_component>.````
    
    
  - Página
    - src/pages ( folder ).
    - .html, .scss, .ts ( arquivos ).
    - adicionar no @ngModule em declarations e entryComponents.
    
 > Um component é um elemento dentro de uma página e uma página é uma view completa que pode conter vários components.
 
 > Uma página precisa ser inputada no declarations e entrycomponents do modulo principal (````@NgModule```` ).
 
 ### Sistema de navegação.

  - Navegação funciona baseada na estrutura de dados pilha.
  - LIFO ( ùltimo a entrar, primeiro a sair ).
  - Métodos ````push() pop() setRoot() ```` são usados para empilhar, desempilhar e setar página como root.
  - ````<ion-nav>```` é quem gerência esse processo.
  - ````NavController```` quem tem os métodos push, pop e setRoot.

 ### Navegando a partir da raiz.
 
  - Usando o ````@ViewChild()```` conseguimos acessar qualquer elemento no app.component.ts e a partir da ai fazer a navegação ou setar uma página como root.
  
  
