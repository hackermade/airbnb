# notes

The `model` is the layer that communicates with the database.

The center of all in a MVC application is the `controller`.

When you generate a new `controller`, beside the controller itself a `view` and a `helper` are also created.

Because the root route is special route you use `#` instead of `/`.

The controller class name must match the `.rb` file name.

Every controller must inherit from the `ApplicationController`.
```ruby
class HomeController < ApplicationController
  ...
end
```

ERB consists of 3 main parts:
- The logic part: `<% %>`
- The rendering part: `<%= %>`
- The commenting part: `<%# %>`
