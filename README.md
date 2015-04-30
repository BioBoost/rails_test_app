# rails_test_app
Basic rails setup to test if RoR and passenger are working on Debian.

# Just clone to server and run
```
sudo su railsapps
cd ~
git clone git@github.com:BioBoost/rails_test_app.git
sudo chmod -R git:railsapps rails_test_app
bundle install --without test development
```
