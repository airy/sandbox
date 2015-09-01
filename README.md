# sandbox

Ruby development sandbox.

## Getting started

clone this repository

    $ git clone https://github.com/airy/sandbox.git

get in sandbox directory

    $ cd sandbox

install dependencies

    $ bundle install

## Testing

Sandbox uses rspec test framework. You can run specs by rspec command.

    $ bundle exec rspec

### Coverage Report

Sandbox uses simplecov to generate coverage reports.

    $ bundle exec rspec -r simplecov

*You can add coverage directory to your global .gitignore file.*

### Continuous Testing

Sandbox uses guard rspec to run test continuously.

    $ bundle exec guard
