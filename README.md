# Mongoid::Uuid

[![Build Status](https://travis-ci.org/badlamer/mongoid-uuid.png)](https://travis-ci.org/badlamer/mongoid-uuid) [![Coverage Status](https://coveralls.io/repos/badlamer/mongoid-uuid/badge.png?branch=master)](https://coveralls.io/r/badlamer/mongoid-uuid?branch=master)

Создаёт фиксированное UUID поле для моделей mongoid < 4.0

## Installation

Add this line to your application's Gemfile:

    gem 'mongoid-uuid'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mongoid-uuid

## Usage

```ruby
require 'mongoid'
require 'mongoid/uuid'

class Model
  include Mongoid::Document
  include Mongoid::Uuid
end
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
