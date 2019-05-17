
# Struttura del progetto

## SRC
* |-- app
   * |-- core
     * |-- [+] animations
     * |-- [+] components
     * |-- [+] components-ui
     * |-- [+] data-services (usually basic http calls)
     * |-- [+] directives
     * |-- [+] guards
     * |-- [+] helpers
     * |-- [+] interceptors
     * |-- [+] models
     * |-- [+] ngrx
       * |-- core.reducer.ts (main entry for redux)
       * |-- example.reducer.ts
       * |-- example.actions.ts
       * |-- example.effects.ts
     * |-- [+] resolvers
     * |-- [+] services
     * |-- core.module.ts
   * |-- modules
     * |-- feature (**feature** is a placeholder)
       * |-- [+] components
       * |-- [+] components-ui
       * |-- [+] data-services
       * |-- [+] directives
       * |-- [+] guards
       * |-- [+] helpers
       * |-- [+] interceptors
       * |-- [+] models
       * |-- [+] modules (if nesting is needed)
       * |-- [+] ngrx
         * |-- feature.reducer.ts
         * |-- feature.actions.ts
         * |-- feature.effects.ts
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
