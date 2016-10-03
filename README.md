Pulls "Yes" RSVPs from a meetup.com event and bulk pre-registers them into envoy.com

Usage
=====

```
export MEETUP_API_KEY=abc
export ENVOY_API_KEY=xyz

./pre-register-meetup-in-envoy <meetup-urlname> <meetup-event_id>
```

This will pull all 'yes' RSVPs out of the given meetup and bulk pre-register them into envoy.com using the start time of the meetup event.
