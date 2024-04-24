---
layout: page-narrow
title: About
permalink: /about.html
---

{:.pt-5 .pb-2}
## History

_The Voices of Gay Rodeo_ online exhibit was developed as part of the Gay Rodeo Oral History Project. Created by Dr. Rebecca Scofield in 2016 with the aid of a University of Idaho Seed Grant and expanded in 2019 with a Whiting Foundation Public Humanities Project grant, this project has sought to preserve and share the history of gay rodeo as it has evolved over the past 45 years. In collaboration with the International Gay Rodeo Association (IGRA), the project has collected over sixty-five interviews with gay rodeo participants. Recorded on hay bales, in hotel lobbies, and in the stands, these oral histories have captured the raw experiences of a group of people who were forced to consistently fight prevailing social stereotypes to define themselves as cowboys and cowgirls.

 

This project would not be possible without the tireless historical and organizational work conducted by IGRA’s leadership and royalty teams, and individuals like Frank Harrell, Roger Bergmann, Patrick Terry, Brian Helander, Candy Pratt, and so many more.

For information on the history of gay rodeo see: [http://gayrodeohistory.org/ \
](http://gayrodeohistory.org/)To see IGRA’s upcoming schedule see: [https://www.igra.com/CalendarRodeo.htm](https://www.igra.com/CalendarRodeo.htm)

{:.pt-5 .pb-2}
## Design

In 2019, the project teamed up with the [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/) to curate many of these interviews into this exhibit, working to highlight the points of convergence and departure of gay rodeoers’ experiences. We approached this work carefully, trying to think of this site less as a simple repository and more as an interactive exhibit that would draw in readers and help them make their own connections across individual stories. Most importantly, we tried to ensure that the portions of narrators’ transcripts that were shared with the broader public captured the aspects they deemed most crucial of their gay rodeo experience. Some transcripts were further edited upon narrators’ request, and we have only shared each narrator’s preferred pseudonym, removing sensitive data. We then put these individual life histories into conversation with each other through our visualization pages. Though this was an imperfect process, as Devin Becker and Rebecca Scofield discuss here: [“Visualizing Subjects: Successes and Failures in Data Tagging Gay Rodeo Oral Histories,”](https://clioandthecontemporary.com/2023/04/21/visualizing-subjects-successes-and-failures-in-data-tagging-gay-rodeo-oral-histories/) _Clio and the Contemporary_ (2023).   

 

{:.pt-5 .pb-2}
## Larger Project

_The Voices of Gay Rodeo_ is one part of our larger Gay Rodeo Oral History Project, which incorporates the oral history collection, the web exhibit, and a verbatim play. While a large number of our oral histories have been included in the site, some histories were simply too sensitive or narrators elected to not have their stories widely available. The full audio files and transcripts are held both by the University of Idaho, and in 2023, with the help of a California State Library grant the bulk of these oral histories were permanently donated to the Autry Museum of the American West to sit alongside the institutional archive of IGRA. Therefore, researchers and the public can access the original files at any time.

 

Also, as part of the larger project, in 2020 Dr. Robert Caisely of UI’s Department of Theatre and project members Rebecca Scofield and Court Fund teamed up to write “That Damn Horse,” a verbatim theater piece drawn almost entirely from these oral histories. Braiding together these life stories in yet another format, “That Damn Horse,” brings together the many voices who represent the diversity of gay rodeo, from old timers to newcomers and across gender and sexual identities. By bringing together imagination and fact through verbatim theater, the playwrights combine gay rodeoers’ broader individual experiences to capture a message about joy, survival, and family.

The play has enjoyed a zoom reading hosted by the University of Idaho in 2021 and an in-person reading at the Autry Museum in 2023.

Here is some of the promotional press on the play!

# Our Team

{%- assign people = site.data.people -%}
{% for p in people %}

<div class="row py-2">
    <div class="col-md-3 text-center">
        {%- assign photo = p.indexid  -%}
        {% capture caption %}{{ p.name }}{% endcapture %}
        {% include figure.html img=photo caption=p.name %}
    </div>
    <div class="col-md-9 align-self-center">
        <strong>{{ p.name }}</strong> {{ p.description }}
    </div>
</div>

{% endfor %}

---

## Student Interns and Research Assistants
{:.pb-3}

<div class="row">
<div class="col-md-4" markdown="1">
- Renae Campbell
- Revulai Detiv
- Saraya Flaig
- Dusty Fleener
- Court Fund
- Cameron Martin
- Christine Packer
- Kenwyn Richards
- Jacob Rudd
{:.pt-4}
</div>
<div class="col-md-8" markdown="1">
{% include figure.html img="/team/gayrodeo-students.jpg" caption="Student Interns at an IGRA Convention" %}
</div>
</div>


