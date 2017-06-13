# FoodTrek Dev Log

## April 23, 2015
#### Val Ng
- generated Rails app foundations
- created (bare) trek, section, restaurant, user models

## April 24, 2015
#### Tiancheng Li
- added restaurants 
- added picture upload system 
- New: user will need to give a profile picture upon sign up
- Change config.serve_static_assets to true(/config/environments/production.rb) to enable assess to pictures (this has to be enable in order to get static contents)

## April 24, 2015
#### Feiyu Lu
- Added Trek 
- Added Trekker
- Added Section (Theme)

## April 24, 2015
#### Tiancheng Li
- fix an syntax error. push the whole thing to heroku

## April 25, 2015
#### Wanxin Cheng
- added dashboard model
- edited some basic style

## April 27, 2015
#### Val Ng
- added geolocation (this includes geocoder, figaro, and bing gems. Geocoder for google maps, figaro for adding values to the ENV [environment variable], bing [API] to allow 50,000 free requests per day for geocoding).
- added map canvas so we can show maps on restaurant pages. Probably need to edit so it is not showing on the restaurant page per se, as there is not current restaurant-only page.
- fixed bug in restaurants db table -- even though :name was listed, it had not been migrated. Added name column to table by rails generate (was not able to simply modify file and add that way)

## April 28, 2015
#### Feiyu Lu
- modified the title in the index page according to our scope (maybe we should drop create your own trek -- need agreement here)
- modified footers' links. Work in progress.

#### Tiancheng 
- change the navibar layout/ dropdown menu is now under user's name

## April 29, 2015
#### Wanxin Cheng
- created Check-in model and controllers 

## April 30, 2015
#### Wanxin Cheng
- enable emailing functions
- fixed formating with all the forms



