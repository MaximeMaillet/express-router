## Releases 0.3.0 - Refacto


#### Released

* Route's configuration accept path of json file or json object

* Route JSON object standard
  * Should start with route
  * Should continue with method or with sub route
  * Then configure your route with
       * String : `MyController#MyAction`
       * Object
       * Function
       
* Fix vulnerability dependencies

* Multiple configurations

* Deduping + deduping with parameters

#### To release


* Default handler for error like not found or errors throwed by user

* Static routes

* Handle middlewares & services

* Error handler for user

* Test