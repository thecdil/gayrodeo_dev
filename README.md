# Voices of Gay Rodeo

This repository holds the source code for <https://voicesofgayrodeo.com/>.

Coding Instructions: <https://uidaholib.github.io/gayrodeo-coding/>

## About:

The Gay Rodeo Oral History Project was created in 2016 with the aid of a University of Idaho Seed Grant. Having conducted archival research on the International Gay Rodeo Association at the Autry Museum of the American West, I was struck by the precarious future of the association, the deep commitment of its members, and the rarity of public-facing projects engaged with rural LGBTQ+ communities. My initial grant helped fund the purchase of audio equipment and travel to seven rodeo events over the course of a year.

To date, I have conducted 33 interviews with 34 members of the International Gay Rodeo Association. During the 2016-2017 collection process, I quickly discovered that interviewing at a rodeo presents its own special challenges. Rodeoers often have only 20 minutes to spare between bronc-riding and barrel-racing and rarely is there a place that provides optimal recording conditions. Wanting to capture people’s everyday experiences, I sought a wide cross-section of members: old-timers and newcomers; members of all sexual and gender identities; and competitors and organizers. With the aid of University of Idaho’s [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/), we have curated many of these interviews in order to highlight the points of convergence and departure that gay rodeoers experience. Over the next several years, we hope to continue to grow the oral history collection and this web exhibit.

This project would not be possible without the tireless historical and organizational work conducted by IGRA’s leadership and royalty teams, and individuals like Frank Harrell, Roger Bergmann, Patrick Terry, and so many more.

For information on the history of gay rodeo see: [http://gayrodeohistory.org/](http://gayrodeohistory.org/)  
To see IGRA’s upcoming schedule see: [https://www.igra.com/CalendarRodeo.htm](https://www.igra.com/CalendarRodeo.htm)

Rebecca Scofield, Assistant Professor of History  
University of Idaho

---

## This site was created with Oral History as Data (OHD) - a Lib-STATIC Tool

The Oral History as Data (OHD) tool is a static website generator that allows users to analyze and publish coded oral history or qualitative interview files. By turning transcriptions into tagged/coded CSV files, adding a list of filters, and creating a simple markdown file for each interview (to be included in the _transcipt collection), OHD will provide filterable transcripts and a color coded visualization for all transcripts included. 

Use this site and the demo files included to learn how to use and deploy the code. Direct any questions here: 
<libstatic.uidaho@gmail.com>

## oral-history-as-data

<https://github.com/uidaholibrary/oral-history-as-data>

A project to generate analyses, discovery and publication tools for oral histories and qualitative interviews, given:

- a CSV representation of the interview transcript, coded by cell - CSV Transcript file example here
- a folder (_transcripts) markdown files for each transcript - MD file example here
- a CSV list of coded topics, listing shorthand reference and full description - CSV Filters example here

See [Getting Started Docs](docs/index.md) for detailed information (coming soon!).

### Get Started Way too Quickly

1. Fork this repository
2. Create (or copy) an example csv file (you can use your own or take one from the /examples/ folder)
3. If you haven't added subject coding to your transcript CSV file, do so.
4. Put the csv file in the _data/transcripts/ directory
5. Create a Markdown (.md) file, use the example file as a model. The minimum fields to be included at the top: object-id, 
first-name, last-name. If you can, add: last-name, date-interviewed, location, interviewer. 
6. If you're working on the web, go to your GitHub repository [Settings](/settings), and enable GitHub Pages

Check out your new site by hitting the link that the enabled GH-Pages Settings sections provides. Should be something like: [GitHub Username].github.io/[Repository Name].

### Technologies and Workflows used:

- Git and GitHub basics
- [Markdown](https://guides.github.com/features/mastering-markdown/), plaintext writing and content creation
- HTML, CSS, and JS literacy
- commandline literacy
- GitHub collaboration and project management
- [Jekyll](https://jekyllrb.com/) basics
- working in the Open, open source and open data
- digital libraries concepts such as "collections as data", minimal computing, data-driven design

> We prefer commonly understood formats (such as CSV spreadsheets over YAML), and convention over configuration (follow the example over learn all the options).

## Features

- [Jekyll](https://jekyllrb.com/) for GitHub Pages 
- Layout using [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/).
- [jQuery](https://jquery.com/)
- Simple [lunr](https://lunrjs.com/) search 
- Rich markup using [Schema.org](http://schema.org) and [Open Graph protocol](http://ogp.me/) standards.

## Build your Own Oral History Collection! 

Check out the [Docs](docs/index.md).


