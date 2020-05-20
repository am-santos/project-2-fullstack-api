Base route: /user

home page -> DONE

- user: all users -> each have different view details
- view.hbs: user/home-page-layout
- URL: /user/:userid/home

profile page -> DONE

- user: all users -> each have different view details
- view.hbs: user/profile_edit
- URL: /user/profile/:userid/edit

edit profile

- user: all users -> each have different view details
- view.hbs: user/profile
- URL: /user/profile/:userid

create product -> DONE

- user: all users -> any owner view
- view.hbs: user/product/create_product
- URL: /user/:userid/product/create

product page view -> DONE

- user: all users -> owner view & all others
- view.hbs: user/product/single
- URL: /user/:userid/product/:productId

update roduct -> DONE

- user: all users -> owner view
- view.hbs: user/product/update_product
- URL: /user/:userid/product/:productId/update

----------------- VIEWS NEEDS ---------------------------------

profile page -> DONE

- user information

home page

- user information
- list of products:
  - client: all products, quantity > 0
  - owner: all owned products
  - supplier: all triggered products

product page

- user information
- client (& all other owners): order
- product owner: edit button
- supplier: provide

create product -> DONE

- user information
- product owners

update roduct -> DONE

- user information
- product owners