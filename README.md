# What is this?
A prototype to demonstrate attendance measure of people at large scale events and capture their ethreum addresses.

# How it works?

first a machine connected to local network will host the webpage

next a machine connected to same local network will be able to access the site

a machine not connected to this local network but connected to internet won't be able to access the website

this way people who are present at particular event can only access the page and register their attendance 

Event needs to have a local network like WiFi access provided to attendees to connect and interact with the page(Most of events now provide free Wifi access) 

# Requirements

python >= 3

django >= 2

Laptop or PC connected to local network

# How to run 

cd into mycheckin folder

type command->python manage.py runserver 0.0.0.0:8000

now open http ://your pc ip:8000 on other device connected to same local network

for getting your host ip type ipconfig command in command line and address under ipv4 will be your ip address

note:please watch guide folder for video explanation

# Why are Google forms used?

Google forms provide easy way for creation of forms and saving data without need to learn code or any hassle for normal organizers

its also better to used readymade form system rather than building one from scratch


# TO-DO

- [x] video guides
- [ ] better way to display google forms
- [ ] front end for one click deployment
- [ ] integration with Poap
- [ ] metamask integration
- [ ] possible integration with Foam

# Useful Links

https://stackoverflow.com/questions/15471173/accessing-django-project-in-lan-systems

https://www.wikihow.com/Find-the-IP-Address-of-Your-PC


