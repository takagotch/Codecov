### codecov
---
https://github.com/codecov

https://codecov.io/

```rb
gem 'codecov', :require => false, :group => :test

require 'simplecov'
SimpleCov.start

require 'codecov'
SimpleCov.formatter = SimpleCov::Formatter::Codecov

CODECOV_TOKEN="your repo token"

if ENV['CI'] == 'true'
  require 'codecov'
  SimpleCov.formatter = SimpleCov::Formatter::Codecov
end

CODECOV_URL="https://codecov.mycompany.com"
CODECOV_SLUG="owner/repo"
CODECOV_TOKEN="repository token or global token"
```

```
```

```
```


