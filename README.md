 # Neighbourhood

# Description
This is a a web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts.

# Author 
Adlight Akinyi

# Live link


# User story
As a user I would like to:

Sign in with the application to start using.

Set up a profile about me and a general location and my neighborhood name.

Find a list of different businesses in my neighborhood.

Find Contact Information for the health department and Police authorities near my neighborhood.

Create Posts that will be visible to everyone in my neighborhood.

Change My neighborhood when I decide to move out.

Only view details of a single neighborhood.

# Set-up/Installation requirements
git clone  https://github.com/AdlightAkinyi/Neighbourhood.git

cd Neighbourhood

python3 -m venv virtual

source virtual/bin/activate

pip install -r requirements

python3 manage.py makemigrations neighbourhood

python3 manage.py migrate

# Running the app
python3 manage.py runserver

Open the application on your browser 127.0.0.1:8000.

# Technologies used
Django

python3

Bootstrap3



heroku

# Support & Contact details
adlightakinyi1@gmail.com

# Licence
AdlightAkinyi/Neighbourhood is licensed under the

MIT License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed unde  r different terms and without source code

Copyright (c) 2022 Adlight  Akinyi


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


