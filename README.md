ruby_code_analyzer_rake_tasks
=============================

This a simple rake-task-file in which I listed some code analyzing tools. It can be used e.g in a git commit hook, a test or deployment script or used stand alone.

Usage
-----

For ease of usage, make sure Bundler is installed. If not run:

    gem install bundler

Now install the gems via bundler:

    bundle install

Remember to update the gems from time to time:

    bundle update

Now Check the available rake tasks with:

    rake -T
    rake analyzer:all                   # run all code analyzing ...
    rake analyzer:flay                  # run flay and analyze ...
    rake analyzer:flog                  # run flog and find the ... 
    rake analyzer:rails_best_practices  # run rails_best_practices ..
    rake analyzer:reek                  # run reek and find code ...
    rake reek                           # Check for code smells


