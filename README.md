# H@ckerhaus


Travelers and techies alike can finally find a place to stay in SF with this easy-to-use app for locating a bed in a community living environment in the Bay area.

![homepage](https://github.com/izzydoesit/hackerhaus/blob/master/app/assets/images/Hackerhaus%20-%20home.png)
![info-section](https://github.com/izzydoesit/hackerhaus/blob/master/app/assets/images/Hackerhaus%20-%20home%20(cont.).png)
![home bottom](https://github.com/izzydoesit/hackerhaus/blob/master/app/assets/images/Hackerhaus-home(3).png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
ruby 2.3.1
bundler 1.12.5
rails 5.0.0
pg 0.19.0
elasticsearch 5.0.0

```

### Installing
From the command terminal, clone the repository to your local directory...
```
$ git clone https://www.github.com/izzydoesit/hackerhaus.git
$ cd hackerhaus
```

Then run bundle command to install all dependencies and run the server.  

```
$ bundle install
$ rails server
```


## Running ALL the tests

```
bundle exec rspec spec
```

## Deployment

You must have Heroku CLI installed and be logged in to Heroku in order to deploy live via Heroku servers
(Please see the [documentation](https://devcenter.heroku.com) to get set up with Heroku)

Then after installation and login, via the command line
```
$ heroku create
$ git push heroku master
$ heroku open
```

## Built With

* [Ruby on Rails](http://api.rubyonrails.org/) -  Back-End Framework used
* [Elasticsearch](https://elastic.co) - Search tool used
* [PostgreSQL](https://www.postgresql.org/) - Database used
* [React-On-Rails](https://github.com/shakacode/react_on_rails) - React front end framework used
* [Mapbox](https://www.mapbox.com) - Map API used

## Authors

* **Israel Matos** - [Github](https://github.com/izzydoesit)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Thank you for all your help!!
* Will Wong
