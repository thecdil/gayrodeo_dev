---
layout: page-narrow
title: About
---

{:.py-2}
# About

The Gay Rodeo Oral History Project was created in 2016 with the aid of a University of Idaho Seed Grant.
Having conducted archival research on the International Gay Rodeo Association at the Autry Museum of the American West, I was struck by the precarious future of the association, the deep commitment of its members, and the rarity of public-facing projects engaged with rural LGBTQ+ communities.
My initial grant helped fund the purchase of audio equipment and travel to seven rodeo events over the course of a year.
In 2019, I also received a Whiting Foundation Public Humanities Project grant.
This $50,000 grant helped fund training for six students who conducted oral histories and helped with transcription, tagging, and uploading these stories.

To date, our team has conducted more than 60 interviews with members of the International Gay Rodeo Association.
We have recorded on hay bales, in hotel lobbies, and in the bleachers.
We have stories as short as eight minutes and some almost three hours long.
With the aid of the University of Idaho’s [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/){:target="_blank" rel="noopener"}, we have curated many of these interviews to highlight the points of convergence and departure that gay rodeoers experience.
Over the next several years, we hope to continue to grow the oral history collection and this web exhibit.

This project would not be possible without the tireless historical and organizational work conducted by IGRA’s leadership and royalty teams, and individuals like Frank Harrell, Roger Bergmann, Patrick Terry, Brian Helander, Candy Pratt, and so many more.

For information on the history of gay rodeo see: <http://gayrodeohistory.org/>   
To see IGRA’s upcoming schedule see: <https://www.igra.com/CalendarRodeo.htm>

{:.pt-3}
***Rebecca Scofield***  
**Associate Professor of History**  
**University of Idaho**

---

# Our Team

{%- assign people = site.data.people -%}
{% for p in people %}

<div class="row py-2">
    <div class="col-md-3 text-center">
        {%- assign photo = p.indexid | append: '.jpg' -%}
        {% capture caption %}{{ p.name }}{% endcapture %}
        {% include figure.html img=photo caption=p.name width="100%" %}
    </div>
    <div class="col-md-9 align-self-center">
        <strong>{{ p.name }}</strong> {{ p.description }}
    </div>
</div>

{% endfor %}

---

## Student Interns and Research Assistants
{:.pb-3}

- Renae Campbell
- Revulai Detiv
- Saraya Flaig
- Dusty Fleener
- Court Fund
- Cameron Martin
- Christine Packer
- Kenwyn Richards
- Jacob Rudd
{:.pb-3}