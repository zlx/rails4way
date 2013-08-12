## Why Rest

1. Use of a client-server architecture
2. Stateless communication
3. Explicit signaling of response cacheability
4. Use of HTTP request methods such as GET, POST, PUT and DELETE

## Resource

+ The current time of day
+ A library book's borrowing history
+ The entire text of the Little Prince
+ A map of jacksonville Beach
+ The inventory of a store


## CRUD

> resources :auctions   VS  resource :auction

new     => GET    new_auctions_path
create  => POST   auctions_path
show    => GET    auction_path(id)
edit    => GET    edit_auction_path(id)
update  => PATCH  auction_path(id)
index   => GET    auctions_path
destroy => DELETE auction_path(id)


## PATCH vs PUT

[PFC 5789](http://www.rfc-editor.org/rfc/rfc5789.txt)


## Nested Resource

Do not Deep Nested Resource

## shallow

shallow: true  => shorter your url?


## route concern

DRY
