Pulls "Yes" RSVPs from a meetup.com event and create a [CSV file suitable for uploading to envoy.com](https://developers.envoy.com/#bulk-visitor-pre-registration)

Usage
=====

```
export MEETUP_API_KEY=abc

./generate-envoy-csv <meetup-event_id> <meetup-host-name>

e.g.
./generate-envoy-csv 234262445 'Richard Paul'
```

This will pull all 'yes' RSVPs out of the given meetup and bulk pre-register them into envoy.com using the start time of the meetup event.

API Keys
--------

To get your meetup.com API key see, https://secure.meetup.com/meetup_api/key/
NB, this doesn't use an envoy.com API key, you can simply upload in a browser using "Import invites from CSV".

TODO
====

If you import the CSV list twice (e.g. to add any new RSVPs) you get everyone double. Could switch to the envoy.com API to only sync the changes.
