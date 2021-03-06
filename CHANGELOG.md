## 1.5.2
Security update

## 1.5.1
* Open source edition

## Reactor 1.3.2
* Fix a bug in `#super_objects` occuring for objects without super links
* Support for Rails 3.2.8

## migrations 1.2.5
* Support for Rails 3.2.8

## Meta 0.1.1
* Support for Rails 3.2.8

## Reactor 1.3.1
* Fix possible bug when force reloading attributes for lowercase obj class

## Reactor 1.3.0
* Introduce AttributeHandlers: dramaticaly improve class loading time in development mode
* Remove broken validation
* Default values for attributes, that have not been set
* Fix user caching bug resulting in repeating requests to CM
* Support for Rails 3.2.7

## Migrations 1.2.4
* Support for Rails 3.2.7

## Meta 0.1.0
* Introduce `obj_class_definition` caching
* Support for Rails 3.2.7

## Reactor 1.2.0
* Support for Rails 3.2.6
* Fixed bug when storing html links (error when passed ActiveSupport::SafeBuffer instead of String)
* Handle storing RailsConnector links with query strings and url fragments

## Meta 0.0.6 / Migrations 1.2.3
* Support for Rails 3.2.6

## Meta 0.0.4
* Beta support for CMS 6.8.0

## Reactor 1.1.1 / Migrations 1.2.1
* 'Hidden' support for `reasons_for_incomplete_state`

## Reactor 1.1.0
* Added built-in validation for `linklist`/`multienum` size limited attributes
* Passing empty string to date attribute clears set date
* Support for Rails 3.1

## Migrations 1.2.0
* Executing requests with disabled Reactor results in Reactor::Cm::MissingCredentials exception being raised
* Support for Rails 3.1

## Meta 0.0.3
* `min_size` and `max_size` for `RailsConnector::Attribute`
* Support for Rails 3.1

## Rector 1.0.0
* Two new file upload modes: streaming from memory, streaming from file (minimal memory usage)
* new API method in Persistence: Image.upload(File.open('image.jpg'), 'jpg', :name => image, :parent => '/')

## Migrations 1.1.0
* Low-level class for file upload introduced (Reactor::Tools::Uploader)
