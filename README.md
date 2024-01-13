# FluxV1

## Bibliotecas
* FluxRequest 
* Simplifier
* DateFormat
* SO(SearchObject)
* PO(PostObject)



# Bom vamos passar pelas principais funcionalidades de cada secção da lib


##  1. PO (Post Object) : é uma secção que vai servir como encapsulador de dados para o post, facilitando na semantica e na economia de linhas do codígo principal.

  ### As duas classes principais são : 
  - UserObject :
    * Os parâmetros de entrada do UserObject são as ordem de campos de um post de Usuario
     ``` javascript
     import UserObject from '.\FluxyV1\FluxAPI\lib\SearchObject'

     const postTuple = new UserObject("nome-do-usuario","email-de-usuario","senha-de-usuario");
    ```
  - SearchPost :
    * Os parâmetros de entrada do UserObject são as ordem de campos de um post de noticia
     ``` javascript
     import NoticyObject from '.\FluxyV1\FluxAPI\lib\SearchObject'

     const postTuple = new NoticyObject("nome-da-noticia","corpo-da-noticia","path-da-img","id-de-usuario-dono-do-post");
    ```




