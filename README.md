= Atpay

Atpay.net Payment Class.

To user class
/config/initializers/atpay.rb

```ruby
ATPAY.configure do |config|
  config.username = 'username'
  config.password = 'password'
  config.host = 'http://test.com'
end
```
== Contributing to Atpay
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Copy config/development.example.yml to config/devlopment.yml
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

== Copyright

Copyright (c) 2012 Paul Kruger. See LICENSE.txt for further details.

Thanks to Josh TOYOTA for the origional class

Thanks to ♆Sir Dante Elrik(theInferno)♆ the  for the configuration and module support
