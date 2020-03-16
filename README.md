# COVID-19 Projects

## Volunteering / Capabilities

If you have capabilities or need help, send an announcement email to 
[subscribe to COVID-19-Help-Needed](http://generativists.com/postorius/lists/covid-19-help-needed.generativists.com/). Also, add yourself to 
[this google sheet to announce your capacity to help](https://docs.google.com/spreadsheets/d/1Vb3fKE68b0AlKyfQU28DOJeBtyHP6giNOVXmz2_ErkI/edit#gid=0).


## Contributing

Anyone can open a pull request to add a category or a link.

If you don't know how to do so, please message me at
[@generativist](https://twitter.com/generativist) on twitter or
via email [jbn@abreka.com](mailto:jbn@abreka.com) and I'll either
help you learn or add it directly if that's what you want.

## Mailing Lists

- [Generativists: COVID-19](http://generativists.com/postorius/lists/covid-19.generativists.com/): This is a mailing list for COVID-19 discussions. It is trans-disciplinary, albeit with a computational focus (think computational social science or epidemiology). It is open to anyone, not just academics. The goal is to accelerate and facilitate collaborati

## Twitter Lists

- [Ellie Murray, Ph.D.'s COVID-19 List](https://twitter.com/i/lists/1220869298631200769): A list of experts working on or tracking the coronavirus outbreak.  
- [Jeff Jarvis' COVID-19 List](https://twitter.com/i/lists/1237834151694303234): Experts on the disease and its spread and reporters covering it.

## Facebook Groups

- [Open Source COVID19 Medical Supplies](https://www.facebook.com/groups/670932227050506/)

## Data

- [Novel Coronavirus (COVID-19) Cases, provided by JHU CSSE](https://github.com/CSSEGISandData/COVID-19)
	- [Christopher D. Long's Fork](https://github.com/octonion/COVID-19)

## Hardware

- [Project OpenAir](https://www.projectopenair.org/): Open source ventilators in order to have a fast and easy solution to be reproduced and assembled locally worldwide.

## Donate Compute Time

### Folding At Home

Note [you can't do *only* COVID-19](https://foldingforum.org/viewtopic.php?f=24&t=32463).
Instead you select `Any` cause preference and COVID-19 is a priority.

- [Installation Guides](https://foldingathome.org/support/faq/installation-guides/)

#### Linux

Tested on: Ubuntu 18.04

```bash
take fah  # mkdir fah && cd fah

# Get -------------------------------------------------------------------------
wget https://download.foldingathome.org/releases/public/release/fahclient/debian-testing-64bit/v7.4/fahclient_7.4.4_amd64.deb
wget https://download.foldingathome.org/releases/public/release/fahcontrol/debian-testing-64bit/v7.4/fahcontrol_7.4.4-1_all.deb
wget https://download.foldingathome.org/releases/public/release/fahviewer/debian-testing-64bit/v7.4/fahviewer_7.4.4_amd64.deb

# Install ---------------------------------------------------------------------
sudo dpkg -i --force-depends fahclient_7.4.4_amd64.deb

# This will ask for user input.
# For group, if you so desire, use 241238: Psychohistorians
sudo dpkg -i --force-depends fahcontrol_7.4.4-1_all.deb

sudo dpkg -i --force-depends fahviewer_7.4.4_amd64.deb

# Admin ----------------------------------------------------------------------
# The web client needs a lot of permissions so make sure you put shields
# down in your browser if need be.
open https://client.foldingathome.org/  # In browser
```
