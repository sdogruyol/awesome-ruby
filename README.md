# Awesome Ruby

A curated list of awesome Ruby frameworks, libraries and resources. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) & [awesome-python](https://github.com/vinta/awesome-python).

Your Pull requests are welcome! Let's make this the awesomest resource for Ruby :purple_heart:

- [Awesome Ruby](#awesome-ruby)
  - [Admin Panels](#admin-panels)
  - [Anti-spam](#anti-spam)
  - [Asset Management](#asset-management)
  - [Audio](#audio)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Build Tools](#build-tools)
  - [Caching](#caching)
  - [Cloud Services](#cloud-services)
  - [CMS](#cms)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Command-line Tools](#command-line-tools)
  - [Configuration](#configuration)
  - [CSS & Styling](#css-&-styling)
  - [Data Validation](#data-validation)
  - [Data Visualization](#data-visualization)
  - [Database Drivers](#database-drivers)
  - [Date and Time](#date-and-time)
  - [Debugging Tools](#debugging-tools)
  - [DevOps Tools](#devops-tools)
  - [Distribution](#distribution)
  - [Documentation](#documentation)
  - [Downloader](#downloader)
  - [E-Commerce & Online Paying](#e-commerce-&-online-paying)
  - [E-Mail](#email)
  - [Environment Management](#environment-management)
  - [File Uploading](#file-uploading)
  - [Foreign Function Interface](#foreign-function-interface)
  - [Forms](#forms)
  - [Game Development](#game-development)
  - [Geolocation](#geolocation)
  - [GUI](#gui)
  - [High Performance](#high-performance)
  - [HTML/XML/CSS Manipulation](#htmlxmlcss-manipulation)
  - [HTTP](#http)
  - [Imagery](#imagery)
  - [Internationalization](#internationalization)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [MapReduce](#mapreduce)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [Package Management](#package-management)
  - [Presentation Tools](#presentation-tools)
  - [Processes and Threads](#processes-and-threads)
  - [Push Notification](#push-notification)
  - [Queue](#queue)
  - [RESTful API](#restful-api)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Search](#search)
  - [Site Monitoring](#site-monitoring)
  - [Starter Apps](#starter-apps)
  - [Tagging](#tagging)
  - [Template Engine](#template-engine)
  - [Testing](#testing)
  - [Text Processing](#text-processing)
  - [Third-party APIs](#third-party-apis)
  - [URL Manipulation](#url-manipulation)
  - [Video](#video)
  - [Web Content Extracting](#web-content-extracting)
  - [Web Crawling](#web-crawling)
  - [Web Frameworks](#web-frameworks)
  - [Web Servers](#web-servers)
  - [WebSocket](#websocket)
- [Miscellaneous](#miscellaneous)
  - [Editor Plugins](#editor-plugins)
- [Resources](#resources)
  - [People to Follow](#people-to-follow)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)


## Admin Panels

*Libraries for administrative interfaces.*

  * [active_admin](https://github.com/gregbell/active_admin) The administration framework for Ruby on Rails applications
  * [rails_admin](https://github.com/sferik/rails_admin) A Rails engine that provides an easy-to-use interface for managing your data

## Anti-spam

*Libraries for fighting spam.*

  * [RubySpamAssassin](https://github.com/noeticpenguin/RubySpamAssassin) Kills Spam Dead. Perhaps before it's sent!

## Asset Management

*Tools for managing, compressing and minifying website assets.*

  * [sprockets](https://github.com/sstephenson/sprockets) Rack-based asset packaging system
  * [rails-assets](https://github.com/rails-assets/rails-assets/) is the frictionless proxy between Bundler and Bower

## Audio

  * [seal](https://github.com/zhangsu/seal) A C library (with Ruby binding) for 3D audio rendering

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

  * [Devise](https://github.com/plataformatec/devise) - Devise is a flexible authentication solution for Rails based on Warden
  * [Omniauth](https://github.com/intridea/omniauth) - OmniAuth is a flexible authentication system utilizing Rack middleware
  * [Warden](https://github.com/hassox/warden) - General Rack Authentication Framework
  * [AuthLogic](https://github.com/binarylogic/authlogic) - A simple ruby authentication solution
  * [Sorcery](https://github.com/NoamB/sorcery) - Magical authentication for Rails 3 & 4
  * [CanCanCan](https://github.com/CanCanCommunity/cancancan) Authorization gem for Rails (continued version of CanCan from ryanb)
  * [pundit](https://github.com/elabs/pundit) - Minimal authorization using object oriented design.
  * [authority](https://github.com/nathanl/authority) - ORM neutral authorization.
  * [doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) An OAuth 2 provider for Rails

## Build Tools

*Compile software from source code.*

  * [teapot](https://github.com/ioquatix/teapot) A decentralised build tool for managing complex cross-platform projects

## Caching

*Libraries for caching data.*

  * [rack-cache](https://github.com/rtomayko/rack-cache) HTTP Caching for Ruby Web Apps
  * [Dalli](https://github.com/mperham/dalli) - a high performance pure Ruby client for accessing memcached servers.

## Cloud Services

  * [fog](https://github.com/fog/fog) The Ruby cloud services library
  * [aws-sdk-ruby](https://github.com/aws/aws-sdk-ruby) The official AWS SDK for Ruby

## CMS

*Content management systems*

  * [Refinery](http://refinerycms.com/) An extendable Ruby on Rails CMS that supports Rails 3.2 and 4
  * [Comfortable Mexican Sofa](https://github.com/comfy/comfortable-mexican-sofa) A powerful Rails 4 CMS Engine
  * [Browser](http://www.browsercms.org/) Humane Content Management for Rails
  * [Locomotive](http://www.locomotivecms.com/) a brand new CMS system with super sexy UI and cool features
  * [Radiant](http://radiantcms.org/) A no-fluff, open source content management system
  * [Nesta](http://nestacms.com/) A lightweight CMS, implemented in Sinatra
  * [alchemy_cms](https://github.com/magiclabs/alchemy_cms) the most powerful, user friendly and flexible Rails CMS
  * [weby](https://github.com/cercomp/weby) Newbie CMS in Ruby on Rails

## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

  * [Rubocop](https://github.com/bbatsov/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide.
  * [ruby-lint](https://github.com/YorickPeterse/ruby-lint) - ruby-lint is a static code analysis tool for Ruby

## Command-line Tools

*Libraries for building command-line application.*

  * [Commander](http://visionmedia.github.io/commander/) - The complete solution for Ruby command-line executables
  * [Thor](https://github.com/erikhuda/thor) - Thor is a toolkit for building powerful command-line interfaces

## Configuration

*Libraries for storing configuration options.*

## CSS & Styling

  * [sass](https://github.com/sass/sass) A CSS preproccessor
    * [sass-rails](https://github.com/rails/sass-rails) Rails stylesheet engine for Sass
  * [less-rails](https://github.com/metaskills/less-rails) The dynamic stylesheet language for the Rails
  * [compass](https://github.com/Compass/compass) A a Stylesheet Authoring Environment
  * [bootstrap-sass](https://github.com/twbs/bootstrap-sass) Official Sass port of Bootstrap
  * [foundation-rails](https://github.com/zurb/foundation-rails) Foundation for Rails
  * [bootswatch-rails](https://github.com/maxim/bootswatch-rails) Bootswatches converted to SCSS ready to use in Rails
  * [bourbon](https://github.com/thoughtbot/bourbon) A lightweight mixin library for Sass

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

## Data Visualization

*Libraries for visualizing data.*

  * [prosperity](https://github.com/smathieu/prosperity) The easiest way to graph data from your Rails models

## Database Drivers

*Libraties for connecting and operating databases.*

  * Relational Databases
    * [ruby-pg](https://bitbucket.org/ged/ruby-pg) Ruby interface to the PostgreSQL >= 8.4
    * [mysql2](https://github.com/brianmario/mysql2) A modern, simple and very fast Mysql library for Ruby
    * [sqlite3-ruby](https://github.com/sparklemotion/sqlite3-ruby) Ruby bindings for the SQLite3 embedded database

  * NoSQL Databases

## Date and Time

*Libraries for working with dates and times.*

  * [stamp](https://github.com/jeremyw/stamp) Date and time formatting for humans


## Debugging Tools

*Libraries for debugging and developing.*

  * [byebug](https://github.com/deivid-rodriguez/byebug) - Debugging in Ruby 2
  * [debugger](https://github.com/cldwalker/debugger) - port of ruby-debug that works on 1.9.2 and 1.9.3

## DevOps Tools

*Software and libraries for DevOps.*

  * [Puppet](https://github.com/puppetlabs/puppet) - Server automation framework and application
  * [Chef](https://github.com/opscode/chef) - A systems integration framework, built to bring the benefits of configuration management to your entire infrastructure.
  * [Vagrant](http://www.vagrantup.com) - Vagrant is a tool for building and distributing development environments.
  * [Capistrano](http://www.capistranorb.com) - Remote multi-server automation tool
  * [Mina](https://github.com/mina-deploy/mina) Really fast deployer and server automation tool

## Distribution

*Libraries to create packaged executables for release distribution.*

  * [fpm](https://github.com/jordansissel/fpm)  Building packages for multiple platforms (deb, rpm, etc) with great ease and sanity.

## Documentation

*Libraries for generating project documentation.*

  * [rdoc](https://github.com/rdoc/rdoc) HTML and online documentation for Ruby projects
  * [yard](https://github.com/lsegal/yard) A Ruby Documentation tool

## Downloader

*Libraries for downloading.*

## E-Commerce & Online Paying

  * [Active Merchant](https://github.com/Shopify/active_merchant) - A simple payment abstraction library extracted from Shopify.
  * [Spree](https://github.com/spree/spree) - A complete open source e-commerce solution for Ruby on Rails.
  * [PayPal Merchant SDK](https://github.com/paypal/merchant-sdk-ruby) - Provides Ruby APIs for processing payments, recurring payments, subscriptions and transactions using PayPal's Merchant APIs.

## E-Mail

*Libraries for sending and parsing email.*

  * [mail](https://github.com/mikel/mail) A Really Ruby Mail Library
  * [mailman](https://github.com/titanous/mailman) An incoming mail processing microframework in Ruby

## Environment Management

*Libraries for Ruby version and environment management.*

  * [chruby](https://github.com/postmodern/chruby) - Changes the current Ruby
  * [chgems](https://github.com/postmodern/chgems) - Chroot for RubyGems
  * [rvm](https://rvm.io/) - Ruby Version Manager
  * [rbenv](http://rbenv.org/) - Groom your app’s Ruby environment
  * [ruby-install](https://github.com/postmodern/ruby-install) - Installs Ruby, JRuby, Rubinius, MagLev or MRuby
  * [ruby-build](https://github.com/sstephenson/ruby-build) - Compile and install Ruby

## Error Handling

*Libraries for exception and error handling.*

  * [Exception Notification](https://github.com/smartinez87/exception_notification) - A set of notifiers for sending notifications when errors occur in a Rack/Rails application
  * [Errbit](http://errbit.github.io/errbit) - The open source, self-hosted error catcher
  * [Airbrake](https://github.com/airbrake/airbrake) - The official Airbrake library for Ruby on Rails (and other Rack based frameworks)
  * [Better Errors](https://github.com/charliesome/better_errors) - Better error page for Rack apps


## File Uploading

*Libraries for handling file uploads.*

  * [paperclip](https://github.com/thoughtbot/paperclip) Easy file attachment management for ActiveRecord
  * [dragonfly](https://github.com/markevans/dragonfly) On-the-fly processing - suitable for image uploading in Rails, Sinatra and much more
  * [carrierwave](https://github.com/carrierwaveuploader/carrierwave) Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks

## Foreign Function Interface

*Libraries for providing foreign function interface.*

## Forms

*Libraries for working with forms.*

  * [simple_form](https://github.com/plataformatec/simple_form) Forms made easy for Rails
  * [formtastic](https://github.com/justinfrench/formtastic) A Rails form builder plugin with semantically rich and accessible markup

## Game Development

*Awesome game development libraries.*

  * [Gosu](http://www.libgosu.org) - A 2D game development library for the Ruby and C++ programming languages


## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

  * [geocoder](https://github.com/alexreisner/geocoder) Complete Ruby geocoding solution
  * [Geokit](https://github.com/geokit/geokit) - Geokit gem provides geocoding and distance/heading calculations.

## GUI

*Libraries for working with graphical user interface applications.*

  * [shoes](https://github.com/shoes/shoes) A tiny graphical app kit for ruby
    * [shoes4](https://github.com/shoes/shoes4) the next version of Shoes

## High Performance

*Libraries for making Ruby faster.*

  * [EventMachine](https://github.com/eventmachine/eventmachine) - EventMachine: fast, simple event-processing library for Ruby programs
  * [Celluloid](http://celluloid.io) - Actor-based concurrent object framework for Ruby

## HTML/XML/CSS Manipulation

*Libraries for working with HTML, XML & CSS.*

  * [Nokogiri](http://nokogiri.org)
  * [loofah](https://github.com/flavorjones/loofah) A general library for manipulating and transforming HTML/XML documents and fragments

## HTTP

*Libraries for working with HTTP.*

  * [httparty](https://github.com/jnunemaker/httparty) Makes http fun again!
  * [faraday](https://github.com/lostisland/faraday) Simple, but flexible HTTP client library, with support for multiple backends.
  * [http](https://github.com/tarcieri/http) A simple Ruby DSL for making HTTP requests
  * [excon](https://github.com/excon/excon) Usable, fast, simple HTTP(S) 1.1 for Ruby
  * [nestful](https://github.com/maccman/nestful) Simple Ruby HTTP/REST client with a sane API

## Imagery

*Libraries for manipulating images.*

  * [rmagick](https://github.com/rmagick/rmagick) An interface to the ImageMagick and GraphicsMagick image processing libraries
    *  [minimagick](https://github.com/minimagick/minimagick) Minified version of rmagick
  * [chunky_png](https://github.com/wvanbergen/chunky_png) Read/write access to PNG images in pure Ruby
  * [image_optim](https://github.com/toy/image_optim) Optimize images using multiple utilities
  * [magickly](https://github.com/afeld/magickly) image manipulation as a (plugin-able) service

## Internationalization

*Libraries for woking with i18n.*

  * [i18n](https://github.com/svenfuchs/i18n) - Basic internationalization(i18n) library for Ruby
  * [globalize](https://github.com/globalize/globalize) Rails I18n de-facto standard library for ActiveRecord model/data translation
  * [i18n-tasks](https://github.com/glebm/i18n-tasks) Manage translations in ruby applications with the awesome power of static analysis

## Logging

*Libraries for generating and working with log files.*

  * [Logstash](https://github.com/elasticsearch/logstash) Logstash is a tool for managing events and logs.

## Machine Learning

*Libraries for Machine Learning.*

  * [PredictionIO Ruby SDK](https://github.com/PredictionIO/PredictionIO-Ruby-SDK) - The PredictionIO Ruby SDK provides a convenient API to quickly record your users' behavior and retrieve personalized predictions for them

## MapReduce

*Framworks and libraries for MapReduce.*

## Natural Language Processing

*Libraries for working with human languages.*

## Networking

*Libraries for network programming.*

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* Relational Databases

  * [ActiveRecord](https://www.ruby-toolbox.com/projects/activerecord) - Databases on Rails. Build a persistent domain model by mapping database tables to Ruby classes
  * [DataMapper](http://datamapper.org/) - DataMapper is an Object Relational Mapper written in Ruby. The goal is to create an ORM which is fast, thread-safe and feature rich.
  * [Sequel](http://sequel.jeremyevans.net/) - The Database Toolkit for Ruby

* NoSQL Databases

  * [Mongoid](http://mongoid.org) - Mongoid (pronounced mann-goyd) is an Object-Document-Mapper (ODM) for MongoDB written in Ruby.
  * [Ohm](https://github.com/soveran/ohm) - Object-Hash Mapping for Redis


## Package Management

*Libraries for package and dependency management.*

  * [RubyGems](https://rubygems.org/) - RubyGems is a package manager for the Ruby programming language that provides a standard format for distributing Ruby programs and libraries
  * [Bundler](http://bundler.io) - Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed

## Pagination

  * [kaminari](https://github.com/amatsuda/kaminari) A Scope & Engine based, clean, powerful, customizable and sophisticated paginator
  * [will_paginate](https://github.com/mislav/will_paginate) Pagination library for Rails 3, Sinatra, Merb, DataMapper, and more

## PDF Processing

  * [wicked_pdf](https://github.com/mileszs/wicked_pdf) PDF generator (from HTML) plugin for Ruby on Rails
  * [pdfkit](https://github.com/pdfkit/pdfkit) HTML+CSS to PDF using wkhtmltopdf
  * [prawn](https://github.com/prawnpdf/prawn) Fast, Nimble PDF Writer for Ruby

## Presentation Tools

  * [rabbit](https://github.com/rabbit-shocker/rabbit) A programable presentaton tool by Ruby
  * [reveal-ck](https://github.com/jedcn/reveal-ck) Reveal.js presentations with a Ruby toolset

## Processes and Threads

*Libraries for woking with processes or threads*

  * [Parallel](https://github.com/grosser/parallel) - Ruby parallel processing made simple and fast

## Push Notification

  * [Rpush](https://github.com/rpush/rpush) - The push notification service for Ruby.
  * [apn_sender](https://github.com/arthurnn/apn_sender) - Background worker to send Apple Push Notifications over a persistent TCP socket.
  * [Houston](https://github.com/nomad/houston) - A simple gem for sending Apple Push Notifications.

## Queue

*Libraries for working with event and task queues.*

  * [Resque](https://github.com/resque/resque) A Redis-backed Ruby library for creating background jobs, placing them on multiple queues.
  * [Delayed::Job](https://github.com/tobi/delayed_job) — Database backed asynchronous priority queue.
  * [Qu](https://github.com/bkeepers/qu) A Ruby library for queuing and processing background jobs.
  * [Sidekiq](https://github.com/mperham/sidekiq) Simple, efficient background processing for Ruby

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Grape](http://intridea.github.io/grape/) - An opinionated micro-framework for creating REST-like APIs in Ruby.
  * [Rails::API](https://github.com/rails-api/rails-api) - Rails for API only applications
  * [jbuilder](https://github.com/rails/jbuilder) - Create JSON structures via a Builder-style DSL
  * [rabl](https://github.com/nesquena/rabl) - General Ruby templating with json, bson, xml, plist and msgpack support
  * [active_model_serializers](https://github.com/rails-api/active_model_serializers) - ActiveModel::Serializer implementation and Rails hooks
  * [oat](https://github.com/ismasan/oat) - Adapters-based API serializers with Hypermedia support for Ruby apps (HAL, Siren, JSONAPI).

## Scheduling

  * [whenever](https://github.com/javan/whenever) Cron jobs in Ruby
  * [resque-scheduler](https://github.com/resque/resque-scheduler) A light-weight job scheduling system built on top of resque
  * [rufus-scheduler](https://github.com/jmettraux/rufus-scheduler) Scheduler for Ruby

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

## Search

*Libraries and software for indexing and performing search queries on data.*

  * [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - Sphinx plugin for ActiveRecord/Rails
  * [elasticsearch-ruby](https://github.com/elasticsearch/elasticsearch-ruby) - Ruby integrations for Elasticsearch
  * [Searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy
  * [PgSearch](https://github.com/Casecommons/pg_search) - PostgreSQL's full text search
  * [Rroonga](https://github.com/ranguba/rroonga) - The Ruby bindings of Groonga
  * [Sunspot](https://github.com/sunspot/sunspot) - Solr-powered search for Ruby objects

## Site Monitoring

*Libs for analytics, monitoring*

  * [rack-google-analytics](https://github.com/kangguru/rack-google-analytics) Simple Rack middleware for implementing google analytics tracking
  * [DataDog](https://github.com/DataDog/dogapi-rb) A monitoring service for IT, operations and development teams
  * [Keen IO](https://github.com/keenlabs/keen-gem) Build analytics features directly into your Ruby apps

## Static Page Generation

  * [jekyll](https://github.com/jekyll/jekyll) A blog-aware, static site generator in Ruby
  * [middleman](https://github.com/middleman/middleman)

## Starter Apps

*App templates for creating apps quickly*

  * [suspenders](https://github.com/thoughtbot/suspenders) A Rails template with our standard defaults, ready to deploy to Heroku
  * [ruby2-rails4-bootstrap-heroku](https://github.com/diowa/ruby2-rails4-bootstrap-heroku) A starter application based on Ruby 2, Rails 4 and Bootstrap for Sass, deployable on Heroku
  * [rails-bootstrap](https://github.com/RailsApps/rails-bootstrap) Rails 4.1 starter app with the Bootstrap front-end framework
  * [rails4-starterkit](https://github.com/starterkits/rails4-starterkit) Rails 4.1 starter app with production ready performance, security, and authentication

## Text Processing

*Libraries for parsing and manipulating texts.*

  * General

  * Specific Formats

  * Parser

## Tagging

*Libraries for tagging items.*

  * [acts-as-taggable-on](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.

## Template Engine

*Libraries and tools for templating and lexing.*

  * [Slim](https://github.com/slim-template/slim) A templating lang that reduce the syntax to the essential parts without becoming cryptic.
    * [slim-rails](https://github.com/slim-template/slim-rails) Rails port of Slim lang
  * [Haml](https://github.com/haml/haml) HTML Abstraction Markup Language - A Markup Haiku
    * [haml-rails](https://github.com/indirect/haml-rails) Rails port of Haml lang
  * [Tilt](https://github.com/rtomayko/tilt)
  * [Liquid](https://github.com/Shopify/liquid)

## Testing

*Libraries for testing codebases and generating test data.*

  * Testing Frameworks
    * [RSpec](http://rspec.info/) - BDD for Ruby
    * [MiniTest](https://github.com/seattlerb/minitest) - minitest provides a complete suite of testing facilities supporting TDD, BDD, mocking, and benchmarking
    * [Cucumber]
       * [Cucumber Github](https://github.com/cucumber/cucumber/wiki) - Cucumber is a tool that executes plain-text functional descriptions as automated tests
       * [Cucumber Site](http://cukes.info/) - Behaviour Driven Development with elegacy and joy
  * Mock
    * [RSpec-mocks](https://github.com/rspec/rspec-mocks) - RSpec's 'test double' framework, with support for stubbing and mocking
    * [Mocha](http://gofreerange.com/mocha/docs/) - Mocking and stubbing library with JMock/SchMock syntax, which allows mocking and stubbing of methods on real (non-mock) classes.
    * [FlexMock](https://github.com/jimweirich/flexmock) - Flexible mocking for Ruby testing
  * Fake Data
    * [Faker](https://github.com/stympy/faker) - A library for generating fake data such as names, addresses, and phone numbers
    * [ffaker](https://github.com/emmanueloga/ffaker) - Faker Refactored.
    * [Forgery](https://github.com/sevenwire/forgery) - Easy and customizable generation of forged data.
  * Code Coverage
    * [simplecov](https://github.com/colszowka/simplecov) Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage
  * Load Testing

  * Error Handler

## Third-party APIs

*Libraries for accessing third party APIs.*

  * [koala](https://github.com/arsduo/koala) A lightweight, flexible library for Facebook
  * [fb_graph](https://github.com/nov/fb_graph) A full-stack Facebook Graph API wrapper
  * [twitter](https://github.com/sferik/twitter) A Ruby interface to the Twitter API
  * [tweetstream](https://github.com/tweetstream/tweetstream) A simple library for consuming Twitter's Streaming API
  * [gitlab](https://github.com/NARKOZ/gitlab) Ruby wrapper and CLI for the GitLab API
  * [octokit.rb](https://github.com/octokit/octokit.rb) Ruby toolkit for the GitHub API
  * [instagram](https://github.com/Instagram/instagram-ruby-gem) The official gem for the Instagram API
  * [linkedin](https://github.com/hexgnu/linkedin) Ruby wrapper for the LinkedIn API
  * [twilio-ruby](https://github.com/twilio/twilio-ruby) A Ruby gem for communicating with the Twilio API and generating TwiML
  * [viewpoint-spws](https://github.com/zenchild/viewpoint-spws) A Microsoft Sharepoint Web Services library for Ruby.
  * [youtube_it](https://github.com/kylejginavan/youtube_it) An object-oriented Ruby wrapper for the YouTube GData API
  * [flickraw](https://github.com/hanklords/flickraw) Flickraw is a library to access flickr api
  * [f00px](https://github.com/500px/f00px) Official 500px api ruby gem

## URL Manipulation

*Libraries for parsing URLs.*

## Video

*Libraries for manipulating video and GIFs.*

  * [streamio-ffmpeg](https://github.com/streamio/streamio-ffmpeg) Simple yet powerful ruby ffmpeg wrapper for reading metadata and transcoding movies

## Web Content Extracting

*Libraries for extracting web contents.*

## Web Crawling

*Libraries for scraping websites.*

  * [upton](https://github.com/propublica/upton) A batteries-included framework for easy web-scraping
  * [metainspector](https://github.com/jaimeiniesta/metainspector)

## Web Frameworks

*Web development frameworks.*

  * [Ruby On Rails](http://rubyonrails.org/) - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable productivity
  * [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.
  * [Padrino](http://www.padrinorb.com/) - The Godfather of Sinatra provides a full-stack agnostic framework on top of Sinatra
  * [Cramp](http://cramp.in/) - Cramp is a fully asynchronous real-time web application framework in Ruby
  * [Lotus](http://lotusrb.org/) - A newborn complete Ruby web framework that is simple, fast and lightweight.
  * [Cuba](http://cuba.is/) - Cuba is a microframework for web development originally inspired by Rum, a tiny but powerful mapper for Rack applications.
  * [Pakyow](http://pakyow.com/) - Pakyow is an open-source framework for the modern web. Build working software faster with a development process that remains friendly to both designers and developers. It's built for getting along.

## Web Servers

*App server interface*

  * [puma](https://github.com/puma/puma) A simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications.
  * [thin](https://github.com/macournoyer/thin) A thin and fast web server
  * [trinidad](https://github.com/trinidad/trinidad) Run Rails or Rack applications within an embedded Apache Tomcat container.
  * [unicorn](https://github.com/defunkt/unicorn) An HTTP server for Rack applications designed to only serve fast clients.
  * [passenger](https://github.com/phusion/passenger) A modern web server and application server for Ruby, Python and Node.js.
  * [pow](https://github.com/37signals/pow) Pow treats files and directories as ruby objects giving you more power and flexibility.
  * [goliath](https://github.com/postrank-labs/goliath) is a non-blocking Ruby web server framework.

## WebSocket

*Libraries for woking with WebSocket.*

  * [Faye](http://faye.jcoglan.com/ruby.html) - Simple pub/sub messaging for the web
  * [websocket-rails](https://github.com/websocket-rails/websocket-rails) - Plug and play websocket support for ruby on rails.

# Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

  * [packetfu](https://github.com/packetfu/packetfu) A mid-level packet manipulation library for Ruby.
  * [chatterbot](https://github.com/muffinista/chatterbot) A straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate
  * [sneakers](https://github.com/jondot/sneakers) A fast background processing framework for Ruby and RabbitMQ
  * [ransack](https://github.com/activerecord-hackery/ransack) Object-based searching.
  * [cinch](https://github.com/cinchrb/cinch) The IRC Bot Building Framework
  * [pry](https://github.com/pry/pry) An IRB alternative and runtime developer console
  * [friendly_id](https://github.com/norman/friendly_id) Slugging and permalink plugins for ActiveRecord
  * [backup](https://github.com/meskyanichi/backup) An elegant DSL in Ruby for performing backups on UNIX-like systems
  * [kss](https://github.com/kneath/kss) Documenting CSS and generating styleguides

## Editor Plugins

*Plugins for various editors.*

  * [vim-ruby](https://github.com/vim-ruby/vim-ruby) Vim/Ruby Configuration Files
  * [vim-rails](https://github.com/tpope/vim-rails) rails.vim: Ruby on Rails power tools

# Resources

*Where to discover things (libraries, news e.g) about Ruby.*

  * [The Ruby Toolbox](https://www.ruby-toolbox.com/)
  * [RubyGems](https://www.rubygems.org)
  * [RubyDaily](http://rubydaily.org) - Community driven news
  * [Ruby Weekly](http://rubyweekly.com/) - A free, once–weekly e-mail round-up of Ruby news and articles.
  * [Ruby5](http://ruby5.envylabs.com/) - The latest news in the Ruby and Rails community
  * [RubyFlow](http://www.rubyflow.com) - Ruby Programming Community Link Blog

## People to Follow

*People in Ruby World*

  * [Yukihiro "Matz" Matsumoto](https://twitter.com/yukihiro_matz) - Creator of Ruby lang
  * [David Heinemeier Hansson](https://twitter.com/dhh) - Creator of Rails framework
  * [Koichi Sasada](https://github.com/ko1) - Ruby core committer and the developer of YARV
  * [Aaron Patterson](http://tenderlovemaking.com/) - Committer to Nokogiri, Ruby, and Ruby on Rails
  * [Avdi Grimm](http://devblog.avdi.org/) - Host of Ruby Tapas webcasts
  * [Aman Gupta](http://tmm1.net/)- Ruby core committer


# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing

Your Pull requests are welcome! Let's make this the **awesomest** resource for Ruby <3
