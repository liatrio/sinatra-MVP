# sinatra-MVP

This repository contains the sample code for a basic sinatra MVP app. It's purpose is to show the basic structure and
requirements for an MVP. It leverages [sinatra](http://www.sinatrarb.com), a lightweight DSL for making ruby web apps.

to run this app simply clone the repo, run bundle install, and run `rackup -o 0.0.0.0`.
You can reach the app by navigating to [http://localhost:9292](http://localhost:9292) in your browser.

The included files are as follows:

`Gemfile` The required gems to run this app.

`Gemfle.lock` The versions of all gems and dependencies required.

`config.ru` The configuration file for rack, the middleware sinatra uses to host the app.

`app.rb` The logic for the app itself. Simply outputs a hello message.

`test.rb` The test file for the app, ensures that the hello function works correctly, and takes parameters from the url.
