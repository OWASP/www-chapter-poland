---
layout: col-sidebar
title: OWASP Poland
tags: poland
region: Europe
meetup-group: owasp-poland
country: Poland
---

<!-- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) -->

![Poland Chapter Logo](assets/images/OWASP_Poland_logo.png)

## Welcome

Witamy wszystkich bardzo serdecznie na stronie polskiej grupy OWASP. Obecnie prowadzimy działania w regionach wymienionych poniej.

You are welcome on the Polish OWASP Chapter website!
We currently act in following regions:

* Warszawa
* Kraków
* Poznań
* Wrocław
* Śląsk
* Trójmiasto

## Who are we

The original Polish Chapter was founded in June 2007 by Andrzej Targosz and Robert Pająk.
Current chapter leader is [Daniel Krasnokucki](mailto:daniel.krasnokucki@owasp.org).

## Check our Upcoming Meetup Events
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });

  
</script>

## Continuous CfP
Zapraszamy do ciągłego zgłaszania się do kolej nych MeetUpów - na razie on-line, ale po zniesieniu obostrzeń wracamy do normalnych spotkań. 

Please fill CfP whenever you want to share your research!

[Call for Papers - OWASP Poland MeetUp](https://forms.gle/F33n4PMqMdUFDR1z5)

