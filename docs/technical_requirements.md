# 1. The purpose of project

The goal of the project is to create a website where users can get acquainted with more 
local information about the establishments of their city. Our users will be able to create 
new acquaintances and rally the community around good establishments. At the moment we are 
starting from Bialystok, but there will be the possibility of integration with other cities.

# 2. System description

The system consists of the following main functional blocks:

1. Main page with the ability to select a city, general news and the possibility 
of integrating a new city
2. Registration, authentication and authorization
3. Inside the city, a list of bars is available, a map with these establishments 
and the ability to create a beacon of a friendly company
4. Adding events in institutions on their pages and on the general page of the city
5. Subscribe to specific news

## 2.1 Users types

There will be two types of users:
- Level 1 User: regular user
- Level 2 User: users with editing rights for a specific establishment
- Level 3 User: administrator

## 2.2 Friendly beacon functionality

Single users, or groups that lack people, can create a beacon on the map that is tied to a 
specific establishment. Any user can look at this beacon and accept the invitation.
- the beacon works 20 minutes
- the user can disable the beacon ahead of time
- available only to registered users

## 2.3 Main page

The main page will be directly advertising the project itself with the ability to add a city, 
which the administration later confirms, and the ability to simply go to the next url for 
a specific city.

## 2.4 Level 2 user features

- editing a linked establishment
- creating entries in a specific bar(can choose only for the establishments, or also for the city)

## 2.5 Custom subscription

1. a subscription to general news will be available upon registration by checking the box
2. the subscription of the level below is a subscription to the general news of the city
3. an even more local subscription is a subscription to certain establishments

# 3. Proposed technology stack

To implement the system, the following stack of technologies is proposed::
- Backend:
  - Language Python 3.8.10
  - Framework Django 4.0.2
  - Database:
    - SQLite during development
    - Postgres during deploy
- Frontend:
  - Vue js

# 4. Design requirements

Will discuss in the coming days

