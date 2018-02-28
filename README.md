# BlogApp

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

In this application we will write the test cases for the rails application with following tools.

  - capybara
  - rspec
  - RuboCop

### Tech

* [capybara] - Capybara is a web-based test automation software that simulates scenarios for user stories and automates web application testing for behavior-driven software development. It is a part of the Cucumber testing framework written in the Ruby programming language that simulates various aspects of a web browser from the perspective of a real user.
* [rspec] - RSpec is a 'Domain Specific Language' (DSL) testing tool written in Ruby to test Ruby code.[4] It is a behavior-driven development (BDD) framework which is extensively used in the production applications. The basic idea behind this concept is that of Test Driven Development (TDD) where the tests are written first and the development is based on writing just enough code that will fulfill those tests followed by refactoring.
* [RuboCop] - RuboCop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community Ruby Style Guide.

### Installation

Add the following gems in Gemfile

```sh

group :test do 
 gem 'capybara', '2.4.4'
end

group :development, :test do
  gem 'rspec-rails', '3.2.3'
end

```

Run the bundle install

```sh
$ cd <Path_to_Application>
$ bundle install
```


Install the rspec

```sh
$ rails generate rspec:install
```
This will create the following files and directories 
```sh
      create  .rspec
      create  spec
      create  spec/spec_helper.rb
      create  spec/rails_helper.rb
```

