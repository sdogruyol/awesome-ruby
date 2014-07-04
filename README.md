# Awesome Ruby

A curated list of awesome Ruby frameworks, libraries and resources. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) & [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Ruby](#awesome-ruby)
    - [Environment Management](#environment-management)
    - [Package Management](#package-management)
    - [Distribution](#distribution)
    - [Files](#files)
    - [Date and Time](#date-and-time)
    - [Text Processing](#text-processing)
    - [Natural Language Processing](#natural-language-processing)
    - [Documentation](#documentation)
    - [Configuration](#configuration)
    - [Command-line Tools](#command-line-tools)
    - [Imagery](#imagery)
    - [Audio](#audio)
    - [Video](#video)
    - [Geolocation](#geolocation)
    - [HTTP](#http)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [ORM](#orm)
    - [Web Frameworks](#web-frameworks)
    - [CMS](#cms)
    - [RESTful API](#restful-api)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Template Engine](#template-engine)
    - [Queue](#queue)
    - [Search](#search)
    - [Asset Management](#asset-management)
    - [Caching](#caching)
    - [Email](#email)
    - [Internationalization](#internationalization)
    - [URL Manipulation](#url-manipulation)
    - [HTML Manipulation](#html-manipulation)
    - [Web Crawling](#web-crawling)
    - [Web Content Extracting](#web-content-extracting)
    - [Downloader](#downloader)
    - [Forms](#forms)
    - [Data Validation](#data-validation)
    - [Anti-spam](#anti-spam)
    - [Tagging](#tagging)
    - [Build Tools](#build-tools)
    - [Admin Panels](#admin-panels)
    - [Processes and Threads](#processes-and-threads)
    - [Networking](#networking)
    - [WebSocket](#websocket)
    - [Cryptography](#cryptography)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [Logging](#logging)
    - [Testing](#testing)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Debugging Tools](#debugging-tools)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Data Visualization](#data-visualization)
    - [Machine Learning](#machine-learning)
    - [Functional Programming](#functional-programming)
    - [MapReduce](#mapreduce)
    - [Third-party APIs](#third-party-apis)
    - [DevOps Tools](#devops-tools)
    - [Foreign Function Interface](#foreign-function-interface)
    - [High Performance](#high-performance)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Miscellaneous](#miscellaneous)
    - [Editor Plugins](#editor-plugins)
- [Resources](#resources)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)

## Environment Management

*Libraries for Ruby version and environment management.*
  * [rvm](https://rvm.io/) - Ruby Version Manager
  * [rbenv](http://rbenv.org/) - Groom your app’s Ruby environment

## Package Management

*Libraries for package and dependency management.*
  * [RubyGems](https://rubygems.org/) - RubyGems is a package manager for the Ruby programming language that provides a standard format for distributing Ruby programs and libraries

## Distribution

*Libraries to create packaged executables for release distribution.*

## Files

*Libraries for file manipulation and MIME type detection.*

## Date and Time

*Libraries for working with dates and times.*

## Text Processing

*Libraries for parsing and manipulating texts.*

* General

* Specific Formats

* Parser

## Natural Language Processing

*Libraries for working with human languages.*

## Documentation

*Libraries for generating project documentation.*

## Configuration

*Libraries for storing configuration options.*

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development

* Workflow Tools

## Imagery

*Libraries for manipulating images.*

## Audio

*Libraries for manipulating audio.*

## Video

*Libraries for manipulating video and GIFs.*

  * [streamio-ffmpeg](https://github.com/streamio/streamio-ffmpeg) Simple yet powerful ruby ffmpeg wrapper for reading metadata and transcoding movies

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

  * [geocoder](https://github.com/alexreisner/geocoder) Complete Ruby geocoding solution
  * [Geokit](https://github.com/geokit/geokit) - Geokit gem provides geocoding and distance/heading calculations.

## HTTP

*Libraries for working with HTTP.*

  * [httparty](https://github.com/jnunemaker/httparty) Makes http fun again!
  * [faraday](https://github.com/lostisland/faraday) Simple, but flexible HTTP client library, with support for multiple backends.
  * [http](https://github.com/tarcieri/http) A simple Ruby DSL for making HTTP requests
  * [excon](https://github.com/excon/excon) Usable, fast, simple HTTP(S) 1.1 for Ruby
  * [nestful](https://github.com/maccman/nestful) Simple Ruby HTTP/REST client with a sane API

## Database Drivers

*Libraties for connecting and operating databases.*

* Relational Databases
  * [ruby-pg](https://bitbucket.org/ged/ruby-pg) Ruby interface to the PostgreSQL >= 8.4
  * [mysql2](https://github.com/brianmario/mysql2) A modern, simple and very fast Mysql library for Ruby
  * [sqlite3-ruby](https://github.com/sparklemotion/sqlite3-ruby) Ruby bindings for the SQLite3 embedded database

* NoSQL Databases

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* Relational Databases

  * [ActiveRecord](https://www.ruby-toolbox.com/projects/activerecord) - Databases on Rails. Build a persistent domain model by mapping database tables to Ruby classes
  * [DataMapper](http://datamapper.org/) - DataMapper is an Object Relational Mapper written in Ruby. The goal is to create an ORM which is fast, thread-safe and feature rich.
  * [Sequel](http://sequel.jeremyevans.net/) - The Database Toolkit for Ruby

* NoSQL Databases

  * [Mongoid](http://mongoid.org) - Mongoid (pronounced mann-goyd) is an Object-Document-Mapper (ODM) for MongoDB written in Ruby.

## Web Frameworks

*Web development frameworks.*

  * [Ruby On Rails](http://rubyonrails.org/) - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable productivity
  * [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.
  * [Padrino](http://www.padrinorb.com/) - The Godfather of Sinatra provides a full-stack agnostic framework on top of Sinatra
  * [Cramp](http://cramp.in/) - Cramp is a fully asynchronous real-time web application framework in Ruby
  * [Lotus](http://lotusrb.org/) - A newborn complete Ruby web framework that is simple, fast and lightweight.

## CMS

*Content management systems*

  * [Refinery](http://refinerycms.com/)
  * [Browser](http://www.browsercms.org/)
  * [Locomotive](http://www.locomotivecms.com/)
  * [Radiant](http://radiantcms.org/)
  * [Nesta](http://nestacms.com/)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Grape](http://intridea.github.io/grape/) - An opinionated micro-framework for creating REST-like APIs in Ruby.
  * [Rails::API](https://github.com/rails-api/rails-api) - Rails for API only applications
  * [jbuilder](https://github.com/rails/jbuilder) - Create JSON structures via a Builder-style DSL
  * [rabl](https://github.com/nesquena/rabl) - General Ruby templating with json, bson, xml, plist and msgpack support

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

  * [Devise](https://github.com/plataformatec/devise) - Devise is a flexible authentication solution for Rails based on Warden
  * [Omniauth](https://github.com/intridea/omniauth) - OmniAuth is a flexible authentication system utilizing Rack middleware
  * [Warden](https://github.com/hassox/warden) - General Rack Authentication Framework
  * [AuthLogic](https://github.com/binarylogic/authlogic) - A simple ruby authentication solution
  * [Sorcery](https://github.com/NoamB/sorcery) - Magical authentication for Rails 3 & 4

## Template Engine

*Libraries and tools for templating and lexing.*

  * [Slim](https://github.com/slim-template/slim) A templating lang that reduce the syntax to the essential parts without becoming cryptic.
    * [slim-rails](https://github.com/slim-template/slim-rails) Rails port of Slim lang
  * [Haml](https://github.com/haml/haml) HTML Abstraction Markup Language - A Markup Haiku
    * [haml-rails](https://github.com/indirect/haml-rails) Rails port of Haml lang
  * [Tilt](https://github.com/rtomayko/tilt)
  * [Liquid](https://github.com/Shopify/liquid)

## Queue

*Libraries for working with event and task queues.*

  * [Resque](https://github.com/resque/resque) A Redis-backed Ruby library for creating background jobs, placing them on multiple queues.
  * [Sidekiq](http://sidekiq.org) — a full-featured background processing framework for Ruby. It aims to be simple to integrate with any modern Rails application and much higher performance than other existing solutions.
  * [Delayed::Job](https://github.com/tobi/delayed_job) — Database backed asynchronous priority queue.
  * [Qu](https://github.com/bkeepers/qu) A Ruby library for queuing and processing background jobs.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - Sphinx plugin for ActiveRecord/Rails
* [elasticsearch-ruby](https://github.com/elasticsearch/elasticsearch-ruby) - Ruby integrations for Elasticsearch
* [Searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy

## Asset Management

*Tools for managing, compressing and minifying website assets.*

## Caching

*Libraries for caching data.*

## Email

*Libraries for sending and parsing email.*

## Internationalization

*Libraries for woking with i18n.*

* [i18n](https://github.com/svenfuchs/i18n) - Basic internationalization(i18n) library for Ruby

## URL Manipulation

*Libraries for parsing URLs.*

## HTML Manipulation

*Libraries for working with HTML and XML.*

## Web Crawling

*Libraries for scraping websites.*

## Web Content Extracting

*Libraries for extracting web contents.*

## Downloader

*Libraries for downloading.*

## Forms

*Libraries for working with forms.*

* [Simple Form](https://github.com/plataformatec/simple_form) - Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.
* [Formtastic](https://github.com/justinfrench/formtastic) - A Rails form builder plugin with semantically rich and accessible markup.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

## Anti-spam

*Libraries for fighting spam.*

## Tagging

*Libraries for tagging items.*

## Build Tools

*Compile software from source code.*

## Admin Panels

*Libraries for administrative interfaces.*

  * [active_admin](https://github.com/gregbell/active_admin) The administration framework for Ruby on Rails applications
  * [rails_admin](https://github.com/sferik/rails_admin) A Rails engine that provides an easy-to-use interface for managing your data

## Processes and Threads

*Libraries for woking with processes or threads*

## Networking

*Libraries for network programming.*

## WebSocket

*Libraries for woking with WebSocket.*

## Cryptography


## GUI

*Libraries for working with graphical user interface applications.*

## Game Development

*Awesome game development libraries.*

## Logging

*Libraries for generating and working with log files.*


## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
  * [RSpec](http://rspec.info/) - BDD for Ruby
  * [MiniTest](https://github.com/seattlerb/minitest) - minitest provides a complete suite of testing facilities supporting TDD, BDD, mocking, and benchmarking
* Mock
  * [RSpec-mocks](https://github.com/rspec/rspec-mocks) - RSpec's 'test double' framework, with support for stubbing and mocking
  * [Mocha](http://gofreerange.com/mocha/docs/) - Mocking and stubbing library with JMock/SchMock syntax, which allows mocking and stubbing of methods on real (non-mock) classes.
  * [FlexMock](https://github.com/jimweirich/flexmock) - Flexible mocking for Ruby testing
* Fake Data
  * [Faker](https://github.com/stympy/faker) - A library for generating fake data such as names, addresses, and phone numbers
  * [ffaker](https://github.com/emmanueloga/ffaker) - Faker Refactored.
  * [Forgery](https://github.com/sevenwire/forgery) - Easy and customizable generation of forged data.
* Code Coverage

* Load Testing

* Error Handler


## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

  * [Rubocop](https://github.com/bbatsov/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide.
  * [ruby-lint](https://github.com/YorickPeterse/ruby-lint) - ruby-lint is a static code analysis tool for Ruby

## Debugging Tools

*Libraries for debugging and developing.*

  * [byebug](https://github.com/deivid-rodriguez/byebug) - Debugging in Ruby 2
  * [debugger](https://github.com/cldwalker/debugger) - port of ruby-debug that works on 1.9.2 and 1.9.3

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

## Data Visualization

*Libraries for visualizing data.*


## Machine Learning

*Libraries for Machine Learning.*


## Functional Programming


## MapReduce

*Framworks and libraries for MapReduce.*

## Third-party APIs

*Libraries for accessing third party APIs.*

  * [koala](https://github.com/arsduo/koala) A lightweight, flexible library for Facebook
  * [fb_graph](https://github.com/nov/fb_graph) A full-stack Facebook Graph API wrapper
  * [twitter](https://github.com/sferik/twitter) A Ruby interface to the Twitter API
  * [tweetstream](https://github.com/tweetstream/tweetstream) A simple library for consuming Twitter's Streaming API
  * [octokit.rb](https://github.com/octokit/octokit.rb) Ruby toolkit for the GitHub API

## DevOps Tools

*Software and libraries for DevOps.*

  * [Puppet](https://github.com/puppetlabs/puppet) - Server automation framework and application
  * [Chef](https://github.com/opscode/chef) - A systems integration framework, built to bring the benefits of configuration management to your entire infrastructure.
  * [Vagrant](http://www.vagrantup.com) - Vagrant is a tool for building and distributing development environments.
  * [Capistrano](http://www.capistranorb.com) - Remote multi-server automation tool

## Foreign Function Interface

*Libraries for providing foreign function interface.*


## High Performance

*Libraries for making Ruby faster.*


## Algorithms and Design Patterns

*Collections of algorithms and design patterns.*


## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*


## Editor Plugins

*Plugins for various editors.*


# Resources

Where to discover new Ruby libraries.

  * [The Ruby Toolbox](https://www.ruby-toolbox.com/)
  * [RubyGems](https://www.rubygems.org)

## Websites



## Weekly

  * [Ruby Weekly](http://rubyweekly.com/) A free, once–weekly e-mail round-up of Ruby news and articles.


## Twitter


# Contributing

Your Pull requests are welcome! Let's make this the **awesomest** resource for Ruby <3
