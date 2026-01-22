# City Of Wanneroo - Planning Proposals Scraper

* Cookie tracking - No
* Pagnation - yes, via a flag in json data
* Javascript - No
* Clearly defined data within a row - No, data is in a json record, but council reference is inconsistent, sometimes you
  have to look in various places on detail page
* System - socialpinpoint and Hive (v5?) - https://docs.strangebee.com/

This is a scraper that runs on [Morph](https://morph.io). 
To get started [see the documentation](https://morph.io/documentation)

Add any issues to https://github.com/planningalerts-scrapers/issues/issues

## To run the scraper

    bundle exec ruby scraper.rb

### Expected output

Execution time: ? minutes

## To run the tests

bundle exec rake

## To run style and coding checks

    bundle exec rubocop

## To check for security updates

    gem install bundler-audit
    bundle-audit
