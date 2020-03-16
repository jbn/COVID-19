# COVID-19 Projects

## Communication

- [Generativists: COVID-10](http://generativists.com/postorius/lists/covid-19.generativists.com/): This is a mailing list for COVID-19 discussions. It is trans-disciplinary, albeit with a computational focus (think computational social science or epidemiology). It is open to anyone, not just academics. The goal is to accelerate and facilitate collaborati

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
