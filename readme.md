
# Struttura del progetto

## SRC
* |-- **app**
   * |-- _core_
     * |-- [+] components
     * |-- [+] components-ui
     * |-- [+] ngrx
       * |-- core.reducer.ts (main entry for redux)
       * |-- example.reducer.ts
       * |-- example.actions.ts
       * |-- example.effects.ts
     * |-- [+] pages (routed components)       
     * |-- [+] shared
       * |-- [+] animations
       * |-- [+] guards
       * |-- [+] interceptors
       * |-- [+] resolvers
     * |-- core.module.ts
   * |-- _modules_
     * |-- feature (**feature** is a placeholder)
       * |-- [+] components
       * |-- [+] components-ui
       * |-- [+] modules (if nesting is needed)
       * |-- [+] ngrx
         * |-- feature.reducer.ts
         * |-- feature.actions.ts
         * |-- feature.effects.ts
       * |-- [+] pages (routed components)
         * |-- [+] feature-component for path:'/' (act like index page)
       * |-- [+] shared
         * |-- [+] classes
         * |-- [+] data-services
         * |-- [+] directives
         * |-- [+] guards
         * |-- [+] helpers
         * |-- [+] interceptors
         * |-- [+] models
         * |-- [+] resolvers
         * |-- [+] services
       * |-- feature-routing.module.ts
       * |-- feature.module.ts
   * |-- _lib_
     * |-- [+] classes
     * |-- [+] data-services
     * |-- [+] dtos
     * |-- [+] enums
     * |-- [+] models
     * |-- [+] modules
     * |-- [+] services
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
