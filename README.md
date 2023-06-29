# BioHackrXiv Publication Template

Minimal example of a [BioHackrXiv](https://biohackrxiv.org/) publication that can be generated with the
[Preview Service](http://preview.biohackrxiv.org/).

## Step 1: Clone this Template Repository

This repository is a template repository. This means you can hit the green "Use this template"
button to use it as a template to start a new BioHackrXiv Publication:

![Screenshot of the green "Use this template" button.](paper/use-this-template.png)

## Step 2: Configuring the Markdown

The publication Markdown is found in the `paper/paper.md` file. At the top you can edit the
YAML code with metadata. It is important to get this part correct, because otherwise the PDF
generation will fail. The metadata looks like this:

```yaml
title: 'BioHackEU22 Report for Project 26: Shedding the light on unknown chemical substances'
title_short: 'BioHackEU22 #26: unknown chemical substances'
tags:
  - cheminformatics
  - PubChem
  - unknown chemical substances
authors:
  - name: Egon Willighagen
    affiliation: 1
affiliations:
  - name: Dept of Bioinformatics - BiGCaT, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 1
date: 7 November 2022
cito-bibliography: paper.bib
event: BH22EU
biohackathon_name: "BioHackathon Europe 2022"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Paris, France, 2022"
group: Unknown chemical substances group
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Egon Willighagen \emph{et al.}
```

### Which metadata to update?

#### To change

The following fields should be changed:

* title
* title_short
* tags
* authors
* affiliations
* date
* group
* authors_short

Particularly important to update is the following field, which should point to
your clone of the template, instead of the template itself:

* git_url: https://github.com/biohackrxiv/publication-template

#### Only update for other BioHackathons

The following fields should only be changed if you are not writing for the BioHackathon Europe 2022:

* event: BH22EU
* biohackathon_name: "BioHackathon Europe 2022"
* biohackathon_url:   "https://biohackathon-europe.org/"
* biohackathon_location: "Paris, France, 2022"

## Step 3: Previewing the paper as PDF

This repository can be converted into a preview PDF with BioHackrXiv [Preview Server](http://preview.biohackrxiv.org/).
The preview website asks for the link to your repository and will automatically find the `paper.md` and create an PDF.

