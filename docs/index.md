---
layout: default
title: Hidden Berkeley
---

# A Newcomer's Guide to Berkeley Resources

This guide collects campus services and places around Berkeley that new students may not hear about right away, from research help and student support to museums and gardens. Hours, reservations, and eligibility can change, so check each place's official link before you go.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
