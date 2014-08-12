# spring-commands-cucumber

This gem implements the `cucumber` command for
[Spring](https://github.com/jonleighton/spring).

## Usage

Add to your Gemfile:

``` ruby
gem "spring-commands-cucumber"
```

## Changing environment

By default, cucumber is being run in `test` Rails environment. If you want to change it, add the following to `config/spring.rb`:

```ruby
Spring::Commands::Cucumber.environment = 'cucumber'
```
