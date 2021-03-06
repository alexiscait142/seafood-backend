
# SEAstainability

This is the backend for SEAstainability, an app built to show sustainable seafood choices.

This app is fully deployed at:
* https://mod3seafood.firebaseapp.com/
* https://mod3seafood.herokuapp.com/fish
** https://mod3seafood.herokuapp.com/regions

App functionality:

* Filter through the sustainable seafood choices on the left by typing in a fish name.
* View fish that are best farmed or caught wild.
* Filter through the seafood list by clicking on a region on the map (SVG).
* Sign-up/login to view seafood choices in your area and add seafood choices to your profile.
* Click on the Dory icon to learn more about protecting our oceans.

## Getting Started/Installing

Fork and clone this repo. First use the command:

```
bundle install
```
to create your Gemfile. Since this is built with PostgreSQL, you will also need to run:

```
rails db:create
```
as well as:

```
rails db:migrate
```
and:
```
rails db:seed
```

To start the rails server, run this command:
```
rails s
```

Next, find my "seafood-frontend" repo to run the frontend file. (https://github.com/alexiscait142/seafood_frontend)

### Prerequisites

This app requires Ruby on Rails, Active Record, and Postgres.

## Resources

* [FishWatch API](https://www.fishwatch.gov/developers) - Sustainable Seafood API -- NOAA
* [Seafood Watch](https://www.seafoodwatch.org/) - Seafood Watch -- Monterey Bay Aquarium
* [Great Pacific Garbage Patch](https://www.nationalgeographic.org/encyclopedia/great-pacific-garbage-patch/) - Information on the Great Pacific Garbage Patch -- National Geographic
* [The Oceans & CO2](https://usa.oceana.org/carbon-emissions-are-killing-oceans) - Information on the effects of excess CO2 on the oceans -- Oceana

## Authors

* **Alexis Chilinski**

## Deployment

* Deployed to http://mod3seafood.herokuapp.com/
* /fish
* /regions

## Acknowledgments

* Flatiron School
