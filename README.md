## eBay Scraper

An ebay scraper and crawler. Retrieve product data (images, price, reviews, and technical sheet) by ID and search queries.

### Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
git clone git@github.com:phooni/ebay-scraper.git
cd ebay-scraper
npm install
npm run dev; # local development
npm run start; # production
```

Your app should now be running on [localhost:8400](http://localhost:8400/).

Product Data by ID
> http://localhost:8400/id/303279232871

Product Data by Search Queries
> http://localhost:8400/search/iphone

### Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using the web-based flow:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Authors

- **Finbarrs Oketunji** _aka 0xnu_ - _Product Owner_ - [0xnu](https://github.com/0xnu)

### License

The script is published under [WTFPL License](LICENSE).

### Copyright

(c) 2021 [Phooni Limited](https://www.phooni.com).