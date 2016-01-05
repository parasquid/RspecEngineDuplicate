```
[~/parasquid/rspec_engine_duplicate] (master) tristan$ rspec

/home/tristan/.rvm/gems/ruby-2.2.2/gems/actionpack-4.2.3/
    lib/action_dispatch/routing/route_set.rb:557:in `add_route':
    Invalid route name, already in use: 'root'  (ArgumentError)

You may have defined two routes with the same name using the `:as` option, or you may be overriding
a route already defined by a resource with the same naming. For the latter, you can restrict the
routes created with `resources` as explained here:

http://guides.rubyonrails.org/routing.html#restricting-the-routes-created
```
