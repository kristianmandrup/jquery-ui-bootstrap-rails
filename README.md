# jQuery UI Bootstrap for Rails asset pipeline

See [jquery-ui-bootstrap](https://github.com/addyosmani/jquery-ui-bootstrap)

## Install

`gem 'jquery-ui-bootstrap-rails'`

## Assets

Include the main CSS into the application stylesheet manifest:

```
 *= require ui-bootstrap/jquery-ui-bootstrap
```

This file is linked with the correct `/assets/` path to the custom ui images theme that is included (see `assets/images/ui-bootstrap/custom-theme`)

## UI Wijmo

In application stylesheet manifest:

```
 *= require ui-bootstrap/ui-wijmo
```

In application js manifest:

```
 //= require wijmo/jquery.wijmo-open.all.min
```

## Extras

*Date range picker*

In application stylesheet manifest:

```
 *= require ui-date_range_picker/date
 *= require ui-date_range_picker/jquery.daterangepicker.min
```

In application js manifest:

```
 //= require ui-file_input/enhance.min
 //= require ui-file_input/jquery.fileinput
```

*File input*

In application stylesheet manifest:

```
 *= require ui-file_input/enhance
```

In application js manifest:

```
 //= require ui-file_input/enhance.min
 //= require ui-file_input/fileinput.jquery
```

## Important

Just discovered this repo and gem: [jquery-ui-bootstrap-theme-rails](jquery-ui-bootstrap-theme-rails) Please use instead or help merge the various forks into a nice gem for Rails that works with Bootstrap 2.1 :)

## Contributing to jquery-ui-bootstrap-rails
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details.

