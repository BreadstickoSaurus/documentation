# Verzamel project
---
## Backend

### Endpoints :
#### Games :
- [X] Authentication
- [X] Get Collection
- [X] Get Wishlist
- [X] Get Game details
- [X] Add game to collection
- [X] Add game to wishlist
- [X] Delete game

#### Images :
- [X] Add images to a game
- [X] Delete images from a game
- [X] Get images from a game

#### Alternate titles :
- [X] add alt titles to a game
- [X] remove alt titles from a game

#### Platforms :
- [X] crud

#### Publishers
- [X] crud

#### Developers :
- [X] crud

#### Genres
- [X] crud

#### States
- [X] get all states

#### Countries
- [X] get all countries

#### Searching
- [X] semantic search
- [ ] regular search
- [ ] do embedding during post of a game instead of every search

#### Sharing collection/wishlist
- [ ] follow a user
- [ ] get followed users
- [ ] see followed users collection/wishlist
- [ ] see specific game from followed user

## Frontend

### General
- [X] login/register
- [X] pwa with caching (doesnt work with "npm run dev", use "npm run serve" instead)
  
### Collection
- [X] browse own collection
- [X] crud
- [ ] browse other people's collection

### Wishlist
- [ ] browse own wishlist
- [ ] crud
- [X] browse games from all wishlists
  - [X] with semantic search
  - [ ] with regular search

## Extra
- [X] Docker
  - [ ] Fixed SQL bug
  - [ ] automatic injection of .env variables so only 1 .env is needed
- [X] Data script files