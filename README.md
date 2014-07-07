# Awesome Ruby

A curated list of awesome Ruby frameworks, libraries and resources. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) & [awesome-python](https://github.com/vinta/awesome-python).

Your Pull requests are welcome! Let's make this the awesomest resource for Ruby :purple_heart:

- [Awesome Ruby](#awesome-ruby)
  - [Environment Management](#environment-management)
  - [Package Management](#package-management)
  - [Distribution](#distribution)
  - [File Uploading](#file-uploading)
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
  - [Web Servers](#web-servers)
  - [Database Drivers](#database-drivers)
  - [ORM](#orm)
  - [Web Frameworks](#web-frameworks)
  - [CMS](#cms)
  - [RESTful API](#restful-api)
  - [E-Commerce & Online Paying](#e-commerce-&-online-paying)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Template Engine](#template-engine)
  - [Queue](#queue)
  - [Push Notification](#push-notification)
  - [Site Monitoring](#site-monitoring)
  - [Search](#search)
  - [Asset Management](#asset-management)
  - [Presentation Tools](#presentation-tools)
  - [Caching](#caching)
  - [Email](#email)
  - [Internationalization](#internationalization)
  - [URL Manipulation](#url-manipulation)
  - [HTML/XML/CSS Manipulation](#htmlxmlcss-manipulation)
  - [Web Crawling](#web-crawling)
  - [Web Content Extracting](#web-content-extracting)
  - [Downloader](#downloader)
  - [CSS & Styling](#css-&-styling)
  - [Forms](#forms)
  - [Data Validation](#data-validation)
  - [Anti-spam](#anti-spam)
  - [Tagging](#tagging)
  - [Build Tools](#build-tools)
  - [Admin Panels](#admin-panels)
  - [Processes and Threads](#processes-and-threads)
  - [Networking](#networking)
  - [WebSocket](#websocket)
  - [GUI](#gui)
  - [Game Development](#game-development)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Debugging Tools](#debugging-tools)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Data Visualization](#data-visualization)
  - [Machine Learning](#machine-learning)
  - [MapReduce](#mapreduce)
  - [Third-party APIs](#third-party-apis)
  - [DevOps Tools](#devops-tools)
  - [Foreign Function Interface](#foreign-function-interface)
  - [High Performance](#high-performance)
  - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
  - [Miscellaneous](#miscellaneous)
  - [Editor Plugins](#editor-plugins)
  - [Starter Apps](#starter-apps)
- [Resources](#resources)
  - [People to Follow](#people-to-follow)
  - [Weekly](#weekly)
  - [Twitter](#twitter)
- [Contributing](#contributing)

## Environment Management

*Libraries for Ruby version and environment management.*
  * [rvm](https://rvm.io/) - Ruby Version Manager
  * [rbenv](http://rbenv.org/) - Groom your app’s Ruby environment

## Package Management

*Libraries for package and dependency management.*

  * [RubyGems](https://rubygems.org/) - RubyGems is a package manager for the Ruby programming language that provides a standard format for distributing Ruby programs and libraries

## Distribution

*Libraries to create packaged executables for release distribution.*

## File Uploading

*Libraries for handling file uploads.*

  * [paperclip](https://github.com/thoughtbot/paperclip) Easy file attachment management for ActiveRecord
  * [dragonfly](https://github.com/markevans/dragonfly) On-the-fly processing - suitable for image uploading in Rails, Sinatra and much more
  * [carrierwave](https://github.com/carrierwaveuploader/carrierwave) Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks

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

  * [rdoc](https://github.com/rdoc/rdoc) HTML and online documentation for Ruby projects
  * [yard](https://github.com/lsegal/yard) A Ruby Documentation tool

## Configuration

*Libraries for storing configuration options.*

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development
  * [Commander](http://visionmedia.github.io/commander/) - The complete solution for Ruby command-line executables
  * [Thor](https://github.com/erikhuda/thor) - Thor is a toolkit for building powerful command-line interfaces

* Workflow Tools

## Imagery

*Libraries for manipulating images.*

  * [rmagick](https://github.com/rmagick/rmagick) An interface to the ImageMagick and GraphicsMagick image processing libraries
    *  [minimagick](https://github.com/minimagick/minimagick) Minified version of rmagick
  * [chunky_png](https://github.com/wvanbergen/chunky_png) Read/write access to PNG images in pure Ruby
  * [image_optim](https://github.com/toy/image_optim) Optimize images using multiple utilities
  * [magickly](https://github.com/afeld/magickly) image manipulation as a (plugin-able) service

## Audio

  * [seal](https://github.com/zhangsu/seal) A C library (with Ruby binding) for 3D audio rendering

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

## Web Servers

*App server interface*

  * [puma](https://github.com/puma/puma) A simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications.
  * [thin](https://github.com/macournoyer/thin) A thin and fast web server
  * [trinidad](https://github.com/trinidad/trinidad) Run Rails or Rack applications within an embedded Apache Tomcat container.
  * [unicorn](https://github.com/defunkt/unicorn) An HTTP server for Rack applications designed to only serve fast clients.
  * [passenger](https://github.com/phusion/passenger) A modern web server and application server for Ruby, Python and Node.js.
  * [pow](https://github.com/37signals/pow) Pow treats files and directories as ruby objects giving you more power and flexibility.

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
  * [Ohm](https://github.com/soveran/ohm) - Object-Hash Mapping for Redis

## Web Frameworks

*Web development frameworks.*

  * [Ruby On Rails](http://rubyonrails.org/) - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable productivity
  * [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.
  * [Padrino](http://www.padrinorb.com/) - The Godfather of Sinatra provides a full-stack agnostic framework on top of Sinatra
  * [Cramp](http://cramp.in/) - Cramp is a fully asynchronous real-time web application framework in Ruby
  * [Lotus](http://lotusrb.org/) - A newborn complete Ruby web framework that is simple, fast and lightweight.

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

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Grape](http://intridea.github.io/grape/) - An opinionated micro-framework for creating REST-like APIs in Ruby.
  * [Rails::API](https://github.com/rails-api/rails-api) - Rails for API only applications
  * [jbuilder](https://github.com/rails/jbuilder) - Create JSON structures via a Builder-style DSL
  * [rabl](https://github.com/nesquena/rabl) - General Ruby templating with json, bson, xml, plist and msgpack support

## E-Commerce & Online Paying

  * [Spree](https://github.com/spree/spree)


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
  * [Delayed::Job](https://github.com/tobi/delayed_job) — Database backed asynchronous priority queue.
  * [Qu](https://github.com/bkeepers/qu) A Ruby library for queuing and processing background jobs.
  * [Sidekiq](https://github.com/mperham/sidekiq) Simple, efficient background processing for Ruby

## Push Notification

  * [Rpush](https://github.com/rpush/rpush) - The push notification service for Ruby.
  * [apn_sender](https://github.com/arthurnn/apn_sender) - Background worker to send Apple Push Notifications over a persistent TCP socket.

## Site Monitoring

*Libs for analytics, monitoring*

  * [rack-google-analytics](https://github.com/kangguru/rack-google-analytics) Simple Rack middleware for implementing google analytics tracking
  * [DataDog](https://github.com/DataDog/dogapi-rb) A monitoring service for IT, operations and development teams
  * [Keen IO](https://github.com/keenlabs/keen-gem) Build analytics features directly into your Ruby apps

## Search

*Libraries and software for indexing and performing search queries on data.*

  * [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - Sphinx plugin for ActiveRecord/Rails
  * [elasticsearch-ruby](https://github.com/elasticsearch/elasticsearch-ruby) - Ruby integrations for Elasticsearch
  * [Searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy
  * [PgSearch](https://github.com/Casecommons/pg_search) - PostgreSQL's full text search

## Asset Management

*Tools for managing, compressing and minifying website assets.*

  * [sprockets](https://github.com/sstephenson/sprockets) Rack-based asset packaging system

## Presentation Tools

  * [rabbit](https://github.com/rabbit-shocker/rabbit) A programable presentaton tool by Ruby
  * [reveal-ck](https://github.com/jedcn/reveal-ck) Reveal.js presentations with a Ruby toolset

## Caching

*Libraries for caching data.*

  * [rack-cache](https://github.com/rtomayko/rack-cache) HTTP Caching for Ruby Web Apps
  * [Dalli](https://github.com/mperham/dalli) - a high performance pure Ruby client for accessing memcached servers.

## Email

*Libraries for sending and parsing email.*

  * [mail](https://github.com/mikel/mail) A Really Ruby Mail Library
  * [mailman](https://github.com/titanous/mailman) An incoming mail processing microframework in Ruby

## Internationalization

*Libraries for woking with i18n.*

  * [i18n](https://github.com/svenfuchs/i18n) - Basic internationalization(i18n) library for Ruby
  * [globalize](https://github.com/globalize/globalize) Rails I18n de-facto standard library for ActiveRecord model/data translation
  * [i18n-tasks](https://github.com/glebm/i18n-tasks) Manage translations in ruby applications with the awesome power of static analysis

## URL Manipulation

*Libraries for parsing URLs.*

## HTML/XML/CSS Manipulation

*Libraries for working with HTML, XML & CSS.*

  * [Nokogiri](http://nokogiri.org)
  * [loofah](https://github.com/flavorjones/loofah) A general library for manipulating and transforming HTML/XML documents and fragments

## Web Crawling

*Libraries for scraping websites.*

  * [upton](https://github.com/propublica/upton) A batteries-included framework for easy web-scraping
  * [metainspector](https://github.com/jaimeiniesta/metainspector)

## Web Content Extracting

*Libraries for extracting web contents.*

## Downloader

*Libraries for downloading.*

## CSS & Styling

  * [sass](https://github.com/sass/sass) A CSS preproccessor
    * [sass-rails](https://github.com/rails/sass-rails) Rails stylesheet engine for Sass
  * [less-rails](https://github.com/metaskills/less-rails) The dynamic stylesheet language for the Rails
  * [compass](https://github.com/Compass/compass) A a Stylesheet Authoring Environment
  * [bootstrap-sass](https://github.com/twbs/bootstrap-sass) Official Sass port of Bootstrap
  * [foundation-rails](https://github.com/zurb/foundation-rails) Foundation for Rails
  * [bootswatch-rails](https://github.com/maxim/bootswatch-rails) Bootswatches converted to SCSS ready to use in Rails

## Forms

*Libraries for working with forms.*

  * [simple_form](https://github.com/plataformatec/simple_form) Forms made easy for Rails
  * [formtastic](https://github.com/justinfrench/formtastic) A Rails form builder plugin with semantically rich and accessible markup

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

## Anti-spam

*Libraries for fighting spam.*

## Tagging

*Libraries for tagging items.*

  * [acts-as-taggable-on](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.

## Build Tools

*Compile software from source code.*

## Admin Panels

*Libraries for administrative interfaces.*

  * [active_admin](https://github.com/gregbell/active_admin) The administration framework for Ruby on Rails applications
  * [rails_admin](https://github.com/sferik/rails_admin) A Rails engine that provides an easy-to-use interface for managing your data

## Processes and Threads

*Libraries for woking with processes or threads*

  * [Parallel](https://github.com/grosser/parallel) - Ruby parallel processing made simple and fast

## Networking

*Libraries for network programming.*

## WebSocket

*Libraries for woking with WebSocket.*

  * [Faye](http://faye.jcoglan.com/ruby.html) - Simple pub/sub messaging for the web
  * [websocket-rails](https://github.com/websocket-rails/websocket-rails) - Plug and play websocket support for ruby on rails.

## GUI

*Libraries for working with graphical user interface applications.*

  * [shoes](https://github.com/shoes/shoes) A tiny graphical app kit for ruby
    * [shoes4](https://github.com/shoes/shoes4) the next version of Shoes

## Game Development

*Awesome game development libraries.*

## Logging

  * [Logstash](https://github.com/elasticsearch/logstash) Logstash is a tool for managing events and logs.

*Libraries for generating and working with log files.*

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

  * [prosperity](https://github.com/smathieu/prosperity) The easiest way to graph data from your Rails models

## Machine Learning

*Libraries for Machine Learning.*

## MapReduce

*Framworks and libraries for MapReduce.*

## Third-party APIs

*Libraries for accessing third party APIs.*

  * [koala](https://github.com/arsduo/koala) A lightweight, flexible library for Facebook
  * [fb_graph](https://github.com/nov/fb_graph) A full-stack Facebook Graph API wrapper
  * [twitter](https://github.com/sferik/twitter) A Ruby interface to the Twitter API
  * [tweetstream](https://github.com/tweetstream/tweetstream) A simple library for consuming Twitter's Streaming API
  * [octokit.rb](https://github.com/octokit/octokit.rb) Ruby toolkit for the GitHub API
  * [instagram](https://github.com/Instagram/instagram-ruby-gem) The official gem for the Instagram API
  * [linkedin](https://github.com/hexgnu/linkedin) Ruby wrapper for the LinkedIn API
  * [twilio-ruby](https://github.com/twilio/twilio-ruby) A Ruby gem for communicating with the Twilio API and generating TwiML
  * [youtube_it](https://github.com/kylejginavan/youtube_it) An object-oriented Ruby wrapper for the YouTube GData API
  * [flickraw](https://github.com/hanklords/flickraw) Flickraw is a library to access flickr api
  * [f00px](https://github.com/500px/f00px) Official 500px api ruby gem

## DevOps Tools

*Software and libraries for DevOps.*

  * [Puppet](https://github.com/puppetlabs/puppet) - Server automation framework and application
  * [Chef](https://github.com/opscode/chef) - A systems integration framework, built to bring the benefits of configuration management to your entire infrastructure.
  * [Vagrant](http://www.vagrantup.com) - Vagrant is a tool for building and distributing development environments.
  * [Capistrano](http://www.capistranorb.com) - Remote multi-server automation tool
  * [Mina](https://github.com/mina-deploy/mina) Really fast deployer and server automation tool

## Foreign Function Interface

*Libraries for providing foreign function interface.*


## High Performance

*Libraries for making Ruby faster.*

  * [EventMachine](https://github.com/eventmachine/eventmachine) - EventMachine: fast, simple event-processing library for Ruby programs
  * [Celluloid](http://celluloid.io) - Actor-based concurrent object framework for Ruby

## Algorithms and Design Patterns

*Collections of algorithms and design patterns.*


## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

  * [packetfu](https://github.com/packetfu/packetfu) A mid-level packet manipulation library for Ruby.
  * [chatterbot](https://github.com/muffinista/chatterbot) A straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate
  * [sneakers](https://github.com/jondot/sneakers) A fast background processing framework for Ruby and RabbitMQ

## Editor Plugins

*Plugins for various editors.*

## Starter Apps

*App templates for creating apps quickly*

  * [suspenders](https://github.com/thoughtbot/suspenders) A Rails template with our standard defaults, ready to deploy to Heroku
  * [ruby2-rails4-bootstrap-heroku](https://github.com/diowa/ruby2-rails4-bootstrap-heroku) A starter application based on Ruby 2, Rails 4 and Bootstrap for Sass, deployable on Heroku
  * [rails-bootstrap](https://github.com/RailsApps/rails-bootstrap) Rails 4.1 starter app with the Bootstrap front-end framework
  * [rails4-starterkit](https://github.com/starterkits/rails4-starterkit) Rails 4.1 starter app with production ready performance, security, and authentication

# Resources

*Where to discover new Ruby libraries.*

  * [The Ruby Toolbox](https://www.ruby-toolbox.com/)
  * [RubyGems](https://www.rubygems.org)

## People to Follow

*People in Ruby World*

  * [Yukihiro "Matz" Matsumoto](https://twitter.com/yukihiro_matz) Creator of Ruby lang
  * [David Heinemeier Hansson](https://twitter.com/dhh) Creator of Rails framework
  * [Aaron Patterson](http://tenderlovemaking.com/)

## Weekly

  * [Ruby Weekly](http://rubyweekly.com/) - A free, once–weekly e-mail round-up of Ruby news and articles.
  * [Ruby5](http://ruby5.envylabs.com/) - The latest news in the Ruby and Rails community

## Twitter


# Contributing

Your Pull requests are welcome! Let's make this the **awesomest** resource for Ruby <3
