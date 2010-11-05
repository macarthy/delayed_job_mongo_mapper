# delayed_job Mongoid backend

## Installation

Add the gems to your Gemfile:

    gem 'delayed_job', '2.1.0.pre2'
    gem 'delayed_job_mongoid', '1.0.0.rc'

Create the indexes:

    script/rails runner 'Delayed::Backend::Mongoid::Job.create_indexes'

That's it. Use [delayed_job as normal](http://github.com/collectiveidea/delayed_job).
