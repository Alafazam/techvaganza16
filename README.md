# Techvaganza16
Website for techvaganza.org

This is the repository we will use for techvaganza'16.

Based on my experience, these are the things from last year that we should keep.

  - User model having 
    - Oneclick registration for events
    - User profiles
    - Different access levels [user,organisor,admin]
    - backdoor api for admin to update and view stuff
    - backdoor api for organisors to view other users who have registered to their event
    - passowrd reset,change and recover from last year
    - RESTful Api for Android, {with proper auth}


  - Event model
    - simlple steps to add new events on the go, just put html file and update in database
    - backdoor api for making an user organisor for an event [most important]
    - backdoor api for collecting stats for admin
    - RESTful Api for Android, {with proper auth} 
  - Lots of admin Magic


These are the things that I wanted to do, but wasn't able to complete

  - Beter front end, with more animations possibly using [this](http://mojs.io/) 
  - More robust apis, so that we can add/edit organisors, events on the go, from mobile site. { like baat karte karte update kar do and eveyone is like how tf that happned so fast}
  - Separate bootstrap based frontend for mobile, minimum data usage.
  - A proper mobile app api, last time android app was not dynamic, this time it should be.
  - Login with facebook and Gmail (awaited for two years now)
  - same theme on all pages. 
  - DEEBUG MODE
  - "Better content". Please, we need a good content writer exclusively for web site, who will change/edit/format all events description/details and write catchy tag-lines. almost half of my time got wasted in spell and grammer checks.


##### And if we have time, a we also should write a simple 'templating-engine' or txt-parser that we can use to genrate our template .html files directly from text.  
  
##### As of now we use jinja-templating to convert ".html" files to views, its pretty good. BUT Jo text organisors dete hai, Its ALWAYS very messed up, Usse html file bnani hoti hai and that is the most boring thing to do, and we have to do it for ~50 events.

##### Sare organisors k liye apan pehle se format dednege ki event proposal web team ko issi format me chahiye, aur usso apne parse k use se sedhe .html files bna lenge jo baad me jinja-templating me kaam ayi gi.


### Version
16.0

### Installation

You need pip and git installed globally:

```sh
$ mkdir techvaganza
$ cd techvaganza
```

```sh
$ git clone https://github.com/Alafazam/techvaganza16.git 
$ cd techvaganza16/ttv

$ pip install virtualenv
$ virtualenv venv
$ source venv/bin/active
$ pip install -r requirements.txt
```

```sh
python run.py
```
