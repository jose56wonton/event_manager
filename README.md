# Event Manager

This is a command line based project that was designed to work with `.csv` files.

It has 3 files:
* `lib/event_manager.rb` is where all my ruby code is
  * `clean_zipcode` is a method I made for correcting erroneous zipcode formatting
  * `legislators_by_zipcode` is a method that uses the Sunlight import to get the
senators that live in a given zipcode
  * `save_thank_you_letters is a method that creates thank you letters that are
attendee specific.

* `event_attendees.csv` is where my attendee information is located

* `form_letter.erb` is the template for my thank you letters

Use `ruby lib/event_manager.rb` to run the project

For more information on [Event Manager](http://tutorials.jumpstartlab.com/projects/eventmanager.html#eventmanager)
This project is part of [TheOdinProject's](http://www.theodinproject.com) Ruby track.
The project itself can be seen [here](http://tutorials.jumpstartlab.com/projects/eventmanager.html#eventmanager)!
