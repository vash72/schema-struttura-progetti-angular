
# Struttura del progetto

## SRC
* |-- app
   * |-- core
     * |-- [+] components
     * |-- [+] components-ui
     * |-- [+] models
     * |-- [+] ngrx
       * |-- core.reducer.ts (main entry for redux)
       * |-- example.reducer.ts
       * |-- example.actions.ts
       * |-- example.effects.ts
     * |-- [+] pages (routed components)       
     * |-- [+] shared
       * |-- [+] animations
       * |-- [+] data-services (usually basic http calls)
       * |-- [+] directives
       * |-- [+] guards
       * |-- [+] helpers
       * |-- [+] interceptors
       * |-- [+] resolvers
       * |-- [+] services
     * |-- core.module.ts
   * |-- modules
     * |-- feature (**feature** is a placeholder)
       * |-- [+] components
       * |-- [+] components-ui
       * |-- [+] models
       * |-- [+] modules (if nesting is needed)
       * |-- [+] ngrx
         * |-- feature.reducer.ts
         * |-- feature.actions.ts
         * |-- feature.effects.ts
       * |-- [+] pages (routed components)
         * |-- [+] feature-component for path:'/' (act like index page)
       * |-- [+] shared
         * |-- [+] data-services
         * |-- [+] directives
         * |-- [+] guards
         * |-- [+] helpers
         * |-- [+] interceptors
         * |-- [+] resolvers
         * |-- [+] services
       * |-- feature-routing.module.ts
       * |-- feature.module.ts
   * |-- utils
   * |-- shared
     * |-- [+] components-ui
     * |-- [+] components
     * |-- [+] directives
     * |-- [+] pipes
* |-- assets
  * |-- [+] js
  * |-- [+] images
  * |-- [+] icons
  * |-- [+] videos
* |-- styles
  * |-- [+] partials
  * |-- styles.scss


Module/Components naming in CRUD operations
* |-- **entity-name** (singular)
  * |-- [+] pages (routed components) 
    * |-- [+] **entity-name**-create
    * |-- [+] **entity-name**-index
    * |-- [+] **entity-name**-show
    * |-- [+] **entity-name**-update
    * |-- [+] **entity-name**-delete
  * |-- **entity-name**-routing.module.ts
  * |-- **entity-name**.module.ts
