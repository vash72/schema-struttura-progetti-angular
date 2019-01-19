
# Struttura del progetto

## |-- app

* |-- core
  * |-- [+] guards
  * |-- [+] models
  * |-- [+] helpers
  * |-- [+] http (basic http calls)
  * |-- [+] interceptors
  * |-- [+] services
  * |-- [+] components
  * |-- [+] ngrx
  * |-- core.module.ts
  * |-- core.component.ts
  * |-- core-routing.module.ts
* |-- modules
  * |-- home (**home** è un placeholder per il nome_modulo)
    * |-- [+] components
    * |-- [+] pages
    * |-- [+] ngrx
    * |-- home-routing.module.ts
    * |-- home.module.ts
    * |-- [+] modules (se è necessario nestare moduli)
  * |-- shared
    * |-- [+] components
    * |-- [+] directives
    * |-- [+] pipes
  * |-- utils
  * |-- [+] configs
* |-- assets
  * |-- [+] js
  * |-- [+] imgs
  * |-- [+] bgs
  * |-- [+] icons
* |-- styles
  * |-- [+] partials
  * |-- _consts.scss
  * |-- styles.scss
