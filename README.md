get-hired-quickly
=================

## Deploying the site
Before you deploy, you must have stored your secret credentials in the .env
file at the root of this repository. Copy .env.example and fill it with your own
secret credentials.

Once you've done that...
``
bundle install

dotenv s3_website push --headless
``
