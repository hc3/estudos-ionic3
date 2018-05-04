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
 
 ### Sistema de navegação
