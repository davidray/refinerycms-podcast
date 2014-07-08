# Podcasts engine for Refinery CMS.

## How to build this engine as a gem

    cd vendor/engines/podcasts
    gem build refinerycms-podcasts.gemspec
    gem install refinerycms-podcasts.gem
    
    # Sign up for a http://rubygems.org/ account and publish the gem
    gem push refinerycms-podcasts.gem

## After install
    rails generate acts_as_taggable_on:migration