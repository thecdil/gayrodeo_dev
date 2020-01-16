---
layout: default
title: About
object-id: about
---

<h1 class="py-2">About</h1>

Partnering with the International Gay Rodeo Association to collect and preserve people's experiences as LGBTQ+ westerners, this project seeks to protect endangered histories and relocate LGBTQ+ people back into the American West as people continue to build resilient communities.

The Gay Rodeo Oral History Project was created in 2016 with the aid of a University of Idaho Seed Grant which purchased basic equipment and funded travel to several rodeos over the course of a year. Having conducted archival research on the International Gay Rodeo Association at the Autry Museum of the American West, I was struck by the precarious future of the association, the deep commitment of its members, and the rarity of public-facing projects engaged with rural LGBTQ+ communities. I quickly discovered that interviewing at a rodeo presents its own special challenges. Rodeoers often have only 20 minutes to spare between bronc-riding and barrel-racing and rarely is there a place that provides optimal recording conditions. Wanting to capture people’s everyday experiences, I sought a wide cross-section of members: old-timers and newcomers; members of all sexual and gender identities; and competitors and organizers. 

With the aid of University of Idaho’s [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/){:target='_blank'}, we have curated many of these interviews in order to highlight the points of convergence and departure that gay rodeoers experience. 

Currently funded by the Whiting Foundation, student collaborators will be traveling to rodeos during the spring of 2020 to expand our oral history collection and, in turn, the stories available in this exhibit.

This project would not be possible without the tireless historical and organizational work conducted by IGRA’s leadership and royalty teams, and individuals like Frank Harrell, Roger Bergmann, Patrick Terry, and so many more.

For information on the history of gay rodeo, see: [http://gayrodeohistory.org/](http://gayrodeohistory.org/){:target='_blank'}.

For IGRA’s upcoming schedule, see: [https://www.igra.com/CalendarRodeo.htm](https://www.igra.com/CalendarRodeo.htm){:target='_blank'}.

<div class="py-2"><strong>
<p><em>Rebecca Scofield</em><br>  
Assistant Professor of History<br>
University of Idaho</p>
</strong></div>  

---

# Our Team

{%- assign people = site.data.people -%}
{% for p in people %}

<div class="row py-2">
    <div class="col-md-2 text-center">
        {%- assign photo = p.indexid | append: '.jpg' -%}
        {% capture caption %}{{ p.name }}{% endcapture %}
        {% include figure.html img=photo caption=p.name width="100%" %}
    </div>
    <div class="col-md-10 align-self-center">
        <strong>{{ p.name }}</strong> {{ p.description }}
    </div>
</div>
    
{% endfor %}

