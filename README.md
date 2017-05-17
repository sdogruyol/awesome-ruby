# Awesome Ruby

A curated list of awesome Ruby frameworks, libraries and resources. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) & [awesome-python](https://github.com/vinta/awesome-python).

## Contribution

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
  - [CSS and Styling](#css-and-styling)
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
  - [Feature Flipping] (#feature-flipping)
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
  - [Spreadsheets](#spreadsheets)
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

  * [active_admin](https://github.com/activeadmin/activeadmin) The administration framework for Ruby on Rails applications
  * [rails_admin](https://github.com/sferik/rails_admin) A Rails engine that provides an easy-to-use interface for managing your data
  * [administrate](https://github.com/thoughtbot/administrate) A framework for creating flexible, powerful admin dashboards in Rails.

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

  * [Refinery CMS](http://www.refinerycms.com) An extendable Ruby on Rails CMS that supports Rails 3.2 and 4.2
  * [Comfortable Mexican Sofa](https://github.com/comfy/comfortable-mexican-sofa) A powerful Rails 4 CMS Engine
  * [Browser](http://www.browsercms.org/) Humane Content Management for Rails
  * [Locomotive](http://www.locomotivecms.com/) a brand new CMS system with super sexy UI and cool features
  * [Radiant](http://radiantcms.org/) A no-fluff, open source content management system
  * [Nesta](http://nestacms.com/) A lightweight CMS, implemented in Sinatra
  * [alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms) the most powerful, user friendly and flexible Rails CMS
  * [weby](https://github.com/cercomp/weby) Newbie CMS in Ruby on Rails

## Code Analysis and Linter

*Libraries and tools for analyzing, parsing and manipulation codebases.*

  * [Rubocop](https://github.com/bbatsov/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide.
  * [ruby-lint](https://github.com/YorickPeterse/ruby-lint) - ruby-lint is a static code analysis tool for Ruby
  * [brakeman](https://github.com/presidentbeef/brakeman) - Static analysis tool which checks Ruby on Rails applications for security vulnerabilities

## Command-line Tools

*Libraries for building command-line application.*

  * [Commander](http://visionmedia.github.io/commander/) - The complete solution for Ruby command-line executables
  * [Thor](https://github.com/erikhuda/thor) - Thor is a toolkit for building powerful command-line interfaces

## Configuration

*Libraries for storing configuration options.*

## CSS and Styling

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

  * [kangal](https://github.com/lab2023/kangal) - Extended validation gem for email, subdomain, credit card, tax number etc
  * [bin_checker](https://github.com/lab2023/bin_checker) - BIN validator for Turkish Banks

## Data Visualization

*Libraries for visualizing data.*

  * [prosperity](https://github.com/smathieu/prosperity) The easiest way to graph data from your Rails models

## Database Drivers

*Libraries for connecting and operating databases.*

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
  * [Chef](https://github.com/chef/chef) - A systems integration framework, built to bring the benefits of configuration management to your entire infrastructure.
  * [Vagrant](https://www.vagrantup.com/) - Vagrant is a tool for building and distributing development environments.
  * [Capistrano](http://capistranorb.com/) - Remote multi-server automation tool
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

  * [Active Merchant](https://github.com/activemerchant/active_merchant) - A simple payment abstraction library extracted from Shopify.
  * [Spree](https://github.com/spree/spree) - A complete open source e-commerce solution for Ruby on Rails.
  * [PayPal Merchant SDK](https://github.com/paypal/merchant-sdk-ruby) - Provides Ruby APIs for processing payments, recurring payments, subscriptions and transactions using PayPal's Merchant APIs.

## E-Mail

*Libraries for sending and parsing email.*

  * [mail](https://github.com/mikel/mail) A Really Ruby Mail Library
  * [mailman](https://github.com/mailman/mailman) An incoming mail processing microframework in Ruby

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
  * [attache](https://github.com/choonkeat/attache) - Yet another approach to file upload https://attache-demo.herokuapp.com

## Feature flipping

*Libraries for flipping features*

  * [helioth](https://github.com/gmontard/helioth) Manage feature flipping and rollout
  * [flipper](https://github.com/jnunemaker/flipper) feature flipping for ANYTHING
  * [flip](https://github.com/pda/flip) Flip lets you declare and manage feature flags, backed by cookies (private testing) and database (site-wide)
  * [rollout](https://github.com/FetLife/rollout) Feature flippers.

## Foreign Function Interface

*Libraries for providing foreign function interface.*

## Forms

*Libraries for working with forms.*

  * [simple_form](https://github.com/plataformatec/simple_form) Forms made easy for Rails
  * [formtastic](https://github.com/justinfrench/formtastic) A Rails form builder plugin with semantically rich and accessible markup

## Game Development

*Awesome game development libraries.*

  * [Gosu](https://www.libgosu.org/) - A 2D game development library for the Ruby and C++ programming languages


## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

  * [geocoder](https://github.com/alexreisner/geocoder) Complete Ruby geocoding solution
  * [Geokit](https://github.com/geokit/geokit) - Geokit gem provides geocoding and distance/heading calculations.

## Git Tools

*Libraries for working with Git VCS*

  * [katip](https://github.com/lab2023/katip) - Change logger for Git initialized projects

## GUI

*Libraries for working with graphical user interface applications.*

  * [shoes](https://github.com/shoes/shoes) A tiny graphical app kit for ruby
    * [shoes4](https://github.com/shoes/shoes4) the next version of Shoes

## High Performance

*Libraries for making Ruby faster.*

  * [EventMachine](https://github.com/eventmachine/eventmachine) - EventMachine: fast, simple event-processing library for Ruby programs
  * [Celluloid](https://celluloid.io/) - Actor-based concurrent object framework for Ruby. It has its own [awesomeness](https://github.com/sashaegorov/awesome-celluloid).

## HTML/XML/CSS Manipulation

*Libraries for working with HTML, XML & CSS.*

  * [Nokogiri](http://www.nokogiri.org/)
  * [loofah](https://github.com/flavorjones/loofah) A general library for manipulating and transforming HTML/XML documents and fragments

## HTTP

*Libraries for working with HTTP.*

  * [httparty](https://github.com/jnunemaker/httparty) Makes http fun again!
  * [faraday](https://github.com/lostisland/faraday) Simple, but flexible HTTP client library, with support for multiple backends.
  * [http](https://github.com/httprb/http) A simple Ruby DSL for making HTTP requests
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

  * [Logstash](https://github.com/elastic/logstash) Logstash is a tool for managing events and logs.

## Machine Learning

*Libraries for Machine Learning.*

  * [PredictionIO Ruby SDK](https://github.com/PredictionIO/PredictionIO-Ruby-SDK) - The PredictionIO Ruby SDK provides a convenient API to quickly record your users' behavior and retrieve personalized predictions for them

## MapReduce

*Frameworks and libraries for MapReduce.*

## Natural Language Processing

*Libraries for working with human languages.*

* [Treat](https://github.com/louismullie/treat) - Treat is a toolkit for natural language processing and computational linguistics in Ruby

## Networking

*Libraries for network programming.*

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

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
  * [Homebrew](http://brew.sh) - Homebrew installs the stuff you need that Apple didn’t
  * [Homebrew Cask](http://caskroom.io/) - Cask provides a friendly homebrew-style CLI workflow for the administration of Mac applications distributed as binaries

## Pagination

  * [kaminari](https://github.com/amatsuda/kaminari) A Scope & Engine based, clean, powerful, customizable and sophisticated paginator
  * [will_paginate](https://github.com/mislav/will_paginate) Pagination library for Rails 3, Sinatra, Merb, DataMapper, and more
  * [order_query](https://github.com/glebm/order_query) Keyset pagination to find the next or previous record(s) relative to the current one efficiently, e.g. for infinite scroll.

## PDF Processing

  * [DocRaptor](https://github.com/DocRaptor/docraptor-ruby) Wrapper library for [DocRaptor's](https://docraptor.com) Ruby-based HTML-to-PDF API
  * [wicked_pdf](https://github.com/mileszs/wicked_pdf) PDF generator (from HTML) plugin for Ruby on Rails
  * [pdfkit](https://github.com/pdfkit/pdfkit) HTML+CSS to PDF using wkhtmltopdf
  * [prawn](https://github.com/prawnpdf/prawn) Fast, Nimble PDF Writer for Ruby

## Presentation Tools

  * [rabbit](https://github.com/rabbit-shocker/rabbit) A programable presentaton tool by Ruby
  * [reveal-ck](https://github.com/jedcn/reveal-ck) Reveal.js presentations with a Ruby toolset

## Processes and Threads

*Libraries for woking with processes or threads*

  * [Parallel](https://github.com/grosser/parallel) - Ruby parallel processing made simple and fast

## Profiling

  * [bullet](https://github.com/flyerhzm/bullet) - help to kill N+1 queries and unused eager loading

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

## Spreadsheets

*Libraries for manipulating Excel, Google Spreadsheets, Numbers, OpenOffice and LibreOffice files*

  * [spreadsheet](https://github.com/zdavatz/spreadsheet) - The Spreadsheet Library is designed to read and write Spreadsheet Documents.
  * [axlsx](https://github.com/randym/axlsx) - Axlsx excels at helping you generate beautiful Office Open XML Spreadsheet documents.
  * [axlsx_rails](https://github.com/straydogstudio/axlsx_rails) - Axlsx_Rails provides an Axlsx renderer so you can move all your spreadsheet code from your controller into view files.
  * [roo](https://github.com/roo-rb/roo) - Roo implements read access for all spreadsheet types and read/write access for Google spreadsheets.
  * [google-spreadsheet-ruby](https://github.com/gimite/google-spreadsheet-ruby) - This is a library to read/write Google Spreadsheet.
  * [rubyXL](https://github.com/weshatheleopard/rubyXL) - rubyXL is a gem which allows the parsing, creation, and manipulation of Microsoft Excel (.xlsx/.xlsm) Documents
  * [Odf-report](https://github.com/sandrods/odf-report) - Generates ODF files, given a template (.odt) and data, replacing tags
  * [simple_xlsx_writer](https://github.com/harvesthq/simple_xlsx_writer) - Just as the name says, simple writter for Office 2007+ Excel files
  * [remote_table](https://github.com/seamusabshere/remote_table) - Open local or remote XLSX, XLS, ODS, CSV (comma separated), TSV (tab separated), other delimited, fixed-width files, and Google Docs.
  * [acts_as_xlsx](https://github.com/randym/acts_as_xlsx) - acts_as_xlsx lets you turn any ActiveRecord::Base inheriting class into an excel spreadsheet.
  * [activeadmin-axlsx](https://github.com/randym/activeadmin-axlsx) - This gem uses axlsx to provide excel/xlsx downloads for resources in Active Admin.
  * [to_spreadsheet](https://github.com/glebm/to_spreadsheet) - Render XLSX from Rails using existing views
  * [write_xlsx](https://github.com/cxn03651/write_xlsx) - write_xlsx is a gem to create a new file in the Excel 2007+ XLSX format.
  * [excel_rails](https://github.com/asanghi/excel_rails) - Allows you to program spreadsheets using .rxls views
  * [sheets](https://github.com/bspaulding/Sheets) - Work with spreadsheets easily in a native ruby format.
  * [workbook](https://github.com/murb/workbook) - Workbook contains workbooks, as in a table, contains rows, contains cells, reads/writes excel, ods and csv and tab separated files...
  * [Spreadsheet report](https://github.com/gnoso/spreadsheet_report) - Simple tool for running queries against ActiveRecord and putting them into a Google Spreadsheet.
  * [oxcelix](https://github.com/gbiczo/oxcelix) - A fast Excel 2007/2010 (.xlsx) file parser that returns a collection of Matrix objects
  * [wrap_excel](https://github.com/tomiacannondale/wrap_excel) - WrapExcel is to wrap the win32ole, and easy to use Excel operations with ruby. Detailed description please see the README.
  * [write_xlsx_rails](https://github.com/maxd/write_xlsx_rails) - xlsx renderer for Rails base on write_xlsx gem

## Scheduling

  * [whenever](https://github.com/javan/whenever) Cron jobs in Ruby
  * [resque-scheduler](https://github.com/resque/resque-scheduler) A light-weight job scheduling system built on top of resque
  * [rufus-scheduler](https://github.com/jmettraux/rufus-scheduler) Scheduler for Ruby
  * [Clockwork](https://github.com/tomykaira/clockwork) Clockwork is a cron replacement. It runs as a lightweight, long-running Ruby process which sits alongside your web processes (Mongrel/Thin) and your worker processes (DJ/Resque/Minion/Stalker) to schedule recurring work at particular times or dates.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

## Search

*Libraries and software for indexing and performing search queries on data.*

  * [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - Sphinx plugin for ActiveRecord/Rails
  * [elasticsearch-ruby](https://github.com/elastic/elasticsearch-ruby) - Ruby integrations for Elasticsearch
  * [Searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy
  * [Algoliasearch Rails](https://github.com/algolia/algoliasearch-rails/) - AlgoliaSearch integration to your favorite ORM
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
  * [cybele](https://github.com/lab2023/cybele) - Rails 4.x template with responder, simple form, haml, exception notification, etc ...

## Text Processing

*Libraries for parsing and manipulating texts.*

  * General

  * Specific Formats

  * Parser

    * [Yomu](https://github.com/Erol) - Read text and metadata from files and documents (.doc, .docx, .pages, .odt, .rtf, .pdf)

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
       * [Cucumber Site](https://cucumber.io/) - Behaviour Driven Development with elegacy and joy
    * [Spinach](https://github.com/codegram/spinach) - Spinach is a high-level BDD framework that leverages the expressive Gherkin language (used by Cucumber) to help you define executable specifications of your application or library's acceptance criteria.
    * [Rubytest](http://rubyworks.github.io/rubytest) - Rubytest is a testing meta-framework useful for creating highly customize test suites or building whole new test frameworks.
       * [BRASS](http://rubyworks.github.io/brass) - Bare-metal Ruby assertion system standard used by Rubytest.
       * [Lemon](http://rubyworks.github.io/lemon) - Strict unit test system built on top of Rubytest.
    * [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Collection of testing matchers extracted from Shoulda
    * [capybara](https://github.com/jnicklas/capybara) - Acceptance test framework for web applications
  * Mock
    * [RSpec-mocks](https://github.com/rspec/rspec-mocks) - RSpec's 'test double' framework, with support for stubbing and mocking
    * [Mocha](http://gofreerange.com/mocha/docs/) - Mocking and stubbing library with JMock/SchMock syntax, which allows mocking and stubbing of methods on real (non-mock) classes.
    * [FlexMock](https://github.com/jimweirich/flexmock) - Flexible mocking for Ruby testing
  * Fake Data
    * [Faker](https://github.com/stympy/faker) - A library for generating fake data such as names, addresses, and phone numbers
    * [ffaker](https://github.com/ffaker/ffaker) - Faker Refactored.
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
  * [rspotify](https://github.com/guilhermesad/rspotify) Ruby wrapper for the Spotify Web API

## URL Manipulation

*Libraries for parsing URLs.*

## Video

*Libraries for manipulating video and GIFs.*

  * [streamio-ffmpeg](https://github.com/streamio/streamio-ffmpeg) Simple yet powerful ruby FFmpeg wrapper for reading metadata and transcoding movies

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
  * [Pakyow](https://pakyow.com/) - Pakyow is an open-source framework for the modern web. Build working software faster with a development process that remains friendly to both designers and developers. It's built for getting along.

## Web Servers

*App server interface*

  * [puma](https://github.com/puma/puma) A simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications.
  * [thin](https://github.com/macournoyer/thin) A thin and fast web server
  * [trinidad](https://github.com/trinidad/trinidad) Run Rails or Rack applications within an embedded Apache Tomcat container.
  * [unicorn](https://github.com/defunkt/unicorn) An HTTP server for Rack applications designed to only serve fast clients.
  * [passenger](https://github.com/phusion/passenger) A modern web server and application server for Ruby, Python, and Node.js.
  * [pow](https://github.com/basecamp/pow) Pow treats files and directories as ruby objects giving you more power and flexibility.
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
  * [backup](https://github.com/backup/backup) An elegant DSL in Ruby for performing backups on UNIX-like systems
  * [kss](https://github.com/kneath/kss) Documenting CSS and generating styleguides
  * [AASM](https://github.com/aasm/aasm) - A library for adding finite state machines to Ruby classes
  * [JsonCompare](https://github.com/a2design-inc/json-compare) - Returns the difference between two JSON files
  * [blankable](https://github.com/lab2023/blankable) - Adds blank slates to index view in Rails
  * [tcmb_currency](https://github.com/lab2023/tcmb_currency) - T.C.M.B. currencies for Money Gem
  * [enumerize](https://github.com/brainspec/enumerize) - Enumerated attributes with I18n and ActiveRecord/Mongoid support
  * [lol_dba](https://github.com/plentz/lol_dba) - lol_dba is a small package of rake tasks that scan your application models and displays a list of columns that probably should be indexed.
  * [annotate-models](https://github.com/ctran/annotate_models) - Annotate ActiveRecord models
  * [fast_attributes](https://github.com/applift/fast_attributes) - FastAttributes adds attributes with their types to the class
  * [Github Changelog Generator](https://github.com/skywinder/Github-Changelog-Generator) — automatically generate change log from your tags, issues, labels and pull requests on GitHub.
  * [Letter Opener](https://github.com/ryanb/letter_opener) — Preview email in the default browser instead of sending it.
  * [Auto HTML](https://github.com/dejan/auto_html) — Transforming URLs to appropriate resource (image, link, YouTube, Vimeo video,...).


## Editor Plugins

*Plugins for various editors.*

  * [vim-ruby](https://github.com/vim-ruby/vim-ruby) Vim/Ruby Configuration Files
  * [vim-rails](https://github.com/tpope/vim-rails) rails.vim: Ruby on Rails power tools

# Resources

*Where to discover things (libraries, news e.g) about Ruby.*

  * [The Ruby Toolbox](https://www.ruby-toolbox.com/)
  * [RubyGems](https://rubygems.org/)
  * [RubyDaily](http://rubydaily.org) - Community driven news
  * [Ruby Weekly](http://rubyweekly.com/) - A free, once–weekly e-mail round-up of Ruby news and articles.
  * [Ruby5](https://ruby5.codeschool.com/) - The latest news in the Ruby and Rails community
  * [RubyFlow](http://www.rubyflow.com) - Ruby Programming Community Link Blog
  * [GemBundle](http://www.gembundle.com) - A place to discover new Ruby Gems

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
