flapjack-diner-test
===================

This is an extremely simple-minded and rather hacky test harness for flapjack-diner.

The idea is to do simple end to end testing of the API calls in flapjack via flapjack-diner, that is excercising each API function in a fairly simple minded way.  There's bound to be better ways to do this but I found this useful while developing the notification rules API functions in flapjack and flapjack-diner.

Requirements
------------

* a flapjack api gateway running on http://127.0.0.1:4091/
* flapjack-diner gem checked out locally (you'll need to update the path in Gemfile)

Setup
-----

* update the path to flapjack-diner in Gemfile
* run `bundle install`

Running the test calls
----------------------

bundle exec bin/test

