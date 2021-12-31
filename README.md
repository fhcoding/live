# live
See Projects in live Demo

---
# Free Ads

## [Live](https://gentle-forest-06217.herokuapp.com/)

This project is a free, quick, accessible with modern design and fast ads publishing app.

It comes with many features that help you populate what you wanna sell or share with thousands of clients on the web and surely on socials medias.
## Goals

- Free ads publishing
- Ads boosting on socials medias
## Development

- Languages
    - PHP
    - SQL
    - HTML
    - CSS
- FrameWorks
    - Laravel (Backend)
    - Twitter Bootstrap (CSS)

## Challenges

- Design a functional and fast data structure for the ads system (users, categories, attributes, tag...)
- Use the available perfect method in laravel for every action in the backend
- Be consistent and produce clean code
- Find the right page template for twitter bootstrap and combine with good css
- Perfectly combine user experience and errors handling
- Share source code and task between the team's member
- Accessibility best practices and SEO performance for avery accessible single page
- ...

## Demo

- Clone this repository
    - > git clone git@github.com:EpitechCodingAcademyPromo2022/C-DEV-120-COT-1-1-freeads-hermann.fatchola.git
- Run server on the public folder

## Main functionalities

- index or home
    > => display adds, show links and button for ( login, quick publish, about page, terms and conditions page ), show search bar
- ads
    > => browse available ads by (user, category, tag and attribute)
- admin
    > => Show links for necessary user action ( create, update, delete ads and categories, [ update other users ] )
- profile
    > => Show detail about a given user
- search
    > => Display filterable search results
- Edit some of the app aspect like theme color and font size
- Email confirmation for newly signed up users
- Share buttons to populate ads on socials medias (twitter, facebook, instagram, whatsApp...)
- Login and Sign up with twitter or facebook

## Development details

### Main models

- User
- Ad
- App
- Category

### Main views

- / 
    - [index]
- /search
    - [search]
- /ads/
    - /
    - /{id|slug}
- /categories/
    - /
    - /{id|slug}
- /edit
    - /ads/{id|slug}
    - /categories/{id|slug}
- /login
    - [login]
- /signup
    - [signup]
- /dashboard
    - [dashboard]
- /profile
     - [profile]
- /help
    - [help]
- /about
    - [about]
- /terms-and-conditions
    - [terms]

### Main controllers

- UserController
- AdController
- AppController
- CategoryController

## Best practices we kept in mind

- No duplicate
    - User
    - Ad
    - Picture
    - Tag
    - Attribute
- Error handling with laravel features
- Follow the best redirection header

## Future works

- Multi languages support
- Free ads community :-)
- Speed performances
## Contributors

- [@fhcoding](https://github.com/fhcoding)
- [@doris](https://github.com/Doris-LeARN)
- [@shounkpatin](https://github.com/shounkpatin)

## Contacts

## Organization
- [epitech.eu](epitech.eu)

---
