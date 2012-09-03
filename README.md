# jQuery UI Bootstrap for Rails asset pipeline

See [jquery-ui-bootstrap](https://github.com/addyosmani/jquery-ui-bootstrap)

## Install

`gem 'jquery-ui-bootstrap-rails'`

## Assets

Include the main CSS into the application stylesheet manifest:

```
 *= require ui-bootstrap/jquery-ui-bootstrap
```

This file is linked with the correct `/assets/` path to the custom ui images theme that is included (see `assets/images/ui-bootstrap/custom-theme`). This version is based on jquery UI 1.8.16. If you want to live life on the edge, you can try `jquery-ui-bootstrap.latest` which is based on UI v. `1.8.23` (merged with updates by @grinn).

## UI Wijmo

The gem also comes with Wijmo integration. Currently only tested for version 1.5, but wijmo 2.2.0 are included. Please see if the wijmo css files need a facelift a make me a pull request of the changes required to make it look right ;)

In application stylesheet manifest:

```
 *= require ui-bootstrap/ui-wijmo
```

In application js manifest:

```
 //= require wijmo/jquery.wijmo-open.all.min
```

## UI Addons

The gem comes with two add-ons for jQuery UI:

* Date range picker
* Fileinput

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

There is another gem [jquery-ui-bootstrap-theme-rails](jquery-ui-bootstrap-theme-rails) but I don't think it is currently as well designed as this one. I also want to keep the bloat down, and not include lots of less files etc. as there are many other bootstrap related gems out there that provides the bootstrap core files already. No reason for this gem to repackage a version of bootstrap itself!

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

