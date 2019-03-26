---
title: "Beacon - Discovery Services for Genomic Data"
layout: default
date: 2016-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://info.progenetix.org/beaconplus.html'
permalink: '/resources/beaconplus.html'
www_link:
www_links_formatted:
image_file: 'logo_beacon.png'
category:
  - resources
tags: # please delete unneeded options
  - databases
  - tools
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 40px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{page.title}}

The Beacon protocol defines an open standard for genomics data discovery, developed by members of the Global Alliance for Genomics & Health. Since 2016, the Beacon protocols is being developed through the [ELIXIR Beacon project](https://beacon-project.io) as a GA4GH driver project.

As part of the project, the [Baudis group](http://info.baudisgroup.org) at the University of Zurich develops the [Beacon<sup><span style="color: #d00;">+</span></sup> demonstrator](https://beacon.progenetix.org), to demonstrate options for future Beacon protocol extensions.

<!--more-->

The Beacon<sup><span style="color: #d00;">+</span></sup> implementation is a custom front end on top of the - among others - [Progenetix](https://progenetix.org) and [arrayMap](https://arraymap.org) datasets, with emphasis on structural genome variations from cancer samples.
