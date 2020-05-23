# Jenga #

### What is this repository for? ###

* Software to power your organizations, campaigns, and movements. This is a fork of work we started while I (Britone) was still at Swahilipot Hub.

### How do I get set up? ###

* Download the project or clone from the repo
* Ensure you have `pipenv` installed
* Do a `pipenv install` to install dependencies
* Activate virtualenv `pipenv shell`
* You should have an africastalking account https://africastalking.com/.
  get your API key and username from your account
* copy the `sms/local_settings.example` to `sms/local_settings.py` and edit database settings according to your local database settings, africastalking api key & username and SECRET_KEY
* Create a `secrets.py` file on the same directory as `settings.py` and add the following
* Run `python manage.py migrate`
* Run `python manage.py runserver`
