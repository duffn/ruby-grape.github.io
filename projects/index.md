---
layout: page
title: Community Projects
tags: [projects]
comments: false
---

### Core

* [grape](https://github.com/ruby-grape/grape): An opinionated framework for creating REST-like APIs in Ruby.
* [ruby-grape.github.io](https://github.com/ruby-grape/ruby-grape.github.io): The ruby-grape community site.

### Entities and Representers

* [grape-entity](https://github.com/ruby-grape/grape-entity): An API focused facade that sits on top of an object model.
* [grape-rabl](https://github.com/ruby-grape/grape-rabl): Use Rabl templates.
* [grape-roar](https://github.com/ruby-grape/grape-roar): Use Roar with Grape.
* [grape-active_model_serializers](https://github.com/ruby-grape/grape-active_model_serializers): Use active_model_serializers.
* [grape-msgpack](https://github.com/rosylilly/grape-msgpack): Message pack formatter.

### Caching

* [garner](https://github.com/artsy/garner): A RACK-based cache implementation that works with Grape.
* [grape-cache_control](https://github.com/karlfreeman/grape-cache_control): Cache-Control and Expires helpers.
* [grape-rails-cache](https://github.com/monterail/grape-rails-cache): HTTP and server side cache integration with Rails.
* [grape-shaman_cache](https://github.com/wjp2013/grape-shaman_cache): HTTP and server side cache integration for a non-Rails application and Jbuilder.
* [grape-cache](https://github.com/AlexYankee/grape-cache): Another Grape middleware-style caching gem.
* [grape-present_cache](https://github.com/u2/grape-present_cache): Grape fragment cache.

### Data

* [otr-activerecord](https://github.com/jhollinger/otr-activerecord): A simple way to use ActiveRecord with your Grape apps.
* [api-pagination](https://github.com/davidcelis/api-pagination): Pagination with [will_paginate](https://github.com/mislav/will_paginate) or [kaminari](https://github.com/amatsuda/kaminari).
* [grape-kaminari](https://github.com/monterail/grape-kaminari): [Kaminari](https://github.com/amatsuda/kaminari) paginator integration.

### HTTP

* [grape-cors](https://github.com/adamluzsi/grape-cors): Ruby Grape Api extension with Cross-origin resource sharing.
* [grape-throttle](https://github.com/xevix/grape-throttle): Provides a simple endpoint-specific throttling mechanism.
* [grape-batch](https://github.com/c4mprod/grape-batch): Rack middleware which extends Grape::API to support request batching.

### Routing

* [grape-route-helpers](https://github.com/reprah/grape-route-helpers): Path helpers for Grape APIs, similar to Rails' named path helpers.
* [grape-raketasks](https://github.com/reprah/grape-raketasks): Rake task to print out Grape API routes, similar to Rails' rake routes.

### Logging

* [grape_logging](https://github.com/aserafin/grape_logging): Provides simple request logging capabilities (response code, path, parameters, request time, etc).
* [grape-middleware-logger](https://github.com/ridiculous/grape-middleware-logger): Middleware that logs the request path, endpoint name, parameters, response status, errors and duration.

### Authentication and Authorization

* [grape-doorkeeper](https://github.com/fuCtor/grape-doorkeeper): Grape integration with Doorkeeper.
* [grape_api_signature](https://github.com/faber-lotto/grape_api_signature): A RACK-Based AWS Style signature authentication for grape API.
* [wine_bouncer](https://github.com/antek-drzewiecki/wine_bouncer): Doorkeeper OAuth2 authorization middleware for grape APIs.
* [grape_token_auth](https://github.com/mcordell/grape_token_auth): Grape token auth gem for frontend JavaScript apps ([ng-token-auth](https://github.com/lynndylanhurley/ng-token-auth) compatible).
* [grape_oauth2](https://github.com/nbulaj/grape_oauth2): Flexible, fully customizable and simple OAuth2 provider for Grape API.

### Documentation

* [grape-swagger](https://github.com/ruby-grape/grape-swagger): Provides an autogenerated documentation for your Grape API.
* [grape-swagger-rails](https://github.com/ruby-grape/grape-swagger-rails): Swagger UI as Rails Engine for grape-swagger gem.
* [grape-swagger-ui](https://github.com/kendrikat/grape-swagger-ui): Integrates swagger-ui with the Rails asset pipeline.
* [grape-apiary](https://github.com/connexio-labs/grape-apiary): Generate an Apiary Blueprint for you Grape API.
* [grape-swagger-entity](https://github.com/ruby-grape/grape-swagger-entity): Provides grape-entity models parsing for swagger autogenerated documentation.
* [grape-swagger-representable](https://github.com/ruby-grape/grape-swagger-representable): Provides representable models parsing for swagger autogenerated documentation.

### Monitoring, Performance & Instrumentation

* [grape-librato](https://github.com/seanmoon/grape-librato): Librato metrics.
* [grape-appsignal](https://github.com/aai/grape-appsignal): Integration with AppSignal.
* [grape-oink](https://github.com/xevix/grape-oink): Identify routes which significantly increase VM heap size using [oink parser](https://github.com/noahd1/oink).
* [skylight](https://github.com/skylightio/skylight-ruby): Integration with Skylight, [documentation](https://docs.skylight.io/grape).

### Development

* [grape-reload](https://github.com/AlexYankee/grape-reload): Expiremental approach for providing reloading of Grape-based rack applications in dev.

### Testing

* [grape-entity-matchers](https://github.com/agileanimal/grape-entity-matchers): Shoulda-style matchers to help with testing Grape entities.

### Generators

* [grape-scaffold](https://github.com/icicletech/grape-scaffold): An API scaffold generator for Rails.
* [grape-api-generator](https://github.com/vinh0604/grape-api-generator): Some rails generators to help quickly bootstrap new Grape API structure.
* [gris](https://github.com/artsy/gris): A framework (and generators) for building [hal+json hypermedia](http://stateless.co/hal_specification.html) API services using Rack, Grape, Roar, RSpec, and ActiveRecord.
* [grape-starter](https://github.com/LeFnord/grape-starter) Quickly create a API skeleton using Rack, Grape, Grape Swagger and Sequel or ActiveRecord.
* [grapethor](https://rawongithub.github.io/grapethor) Grape REST-like API application generator based on Thor.

### Opinionated Frameworks

* [grape_ape_rails](https://github.com/mepatterson/grape_ape_rails): Wrap the various best practices of integrating your API within the context of a Rails app.
* [napa](https://github.com/bellycard/napa): A simple framework for building Rack based APIs using Grape, Roar and ActiveRecord to feel similar to what you would expect from a Rails app.
* [grape-transformations](https://github.com/codescrum/grape-transformations): A gem that works with Rails and Grape to organize and make possible the use of multiple Grape entities per model, while at the same time, decoupling them from your models.

### Contribute

Please [contribute a project](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/CONTRIBUTING.md) to [this page](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/projects/index.md).

We encourage you to develop and support your Grape ecosystem project, expand its maintainers and help a community thrive. Some projects do become quite popular and you might want to donate them to the community at large. If you want to move a project to the [ruby-grape Github organization](https://github.com/ruby-grape) please make a succinct proposal on [the mailing list](https://groups.google.com/forum/#!forum/ruby-grape). A member of the [core team](/team) will make the call.
