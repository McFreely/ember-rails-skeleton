#Ember Rails Skeleton Application

I was tired of seting up again and again all the application environment when creating new app with rails. So I decided to create a robust skeleton, with absolutely no files for decoration. You download it and can work right away. No need to delete dozens of useless files.

I have configured it to please my tastes for development. Feel free to fork the project and install what you prefer. 

##Version
The application uses Rails 4.0.0

Ember.js and Ember-data have been installed from the beta channel (1.1.2), for ember-data to work correctly.

[Foundation](https://github.com/zurb/foundation) is the brand new version 5

##Testing
The application uses [JasmineRice](http://github.com/bradphelan/jasminerice.git) to test the frontend.

The application uses [Rspec](https://github.com/rspec/rspec-rails)+
[Guard](https://github.com/guard/guard)+[Spork](https://github.com/sporkrb/spork) to test the backend.

##Download
Theorically, you just have to clone the repo with to have the starter app.

    git clone https://github.com/McFreely/ember-rails-skeleton.git

Just rename the main folder to the name of your choice for maximum comfort.

    mv /ember-rails-skeleton /brandNewName

A bundle install inside the app folder might be also good idea too. Go make yourself a coffee, it's gonna take a while.

    cd /path/to/app
    bundle install

You are now ready to code something for real!

##Important Info
The namespace of the rails app is "app" , so is the namespace of the ember app, mainly for convienience while writing code.


