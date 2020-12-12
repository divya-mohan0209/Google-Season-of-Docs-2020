# Documentation Development Phase (September 14, 2020 - November 30, 2020)

As with the Community Bonding phase, the Documentation Development phase has primarily been one of
experimentation. Since the existing documentation required a new look & feel alongwith restructuring,
our primary goal was to narrow down on the simplest possible User Interface.

## Goals

### Prototyping from a UI/UX perspective  :heavy_check_mark:

As in the [Community Bonding phase](Community-Bonding.md), we continued experimenting with various
Sphinx themes keeping the HTML files separate from the entire Docusaurus CSS. However we realized
that in addition to being counter-inuitive to our goal of removing the Sphinx dependency, it was
also a very complicated mechanism to maintain & publish via GH actions.
This is why we shifted to converting **EVERYTHING** to Markdown & placing it under docs instead
of doubling our work.

- [Solar theme for Sphinx](https://divya-mohan0209.github.io/docusaurus-solar/rucio/)
- [Alabaster theme for Sphinx](https://divya-mohan0209.github.io/docusaurus-alabaster/rucio/)
- [Primary prototype for utilizing only Docusaurus](https://divya-mohan0209.github.io/docusaurus-nature/docs/)

### Centralizing  :heavy_check_mark:

The project's aim was to centralize all the different sources of documentation & be the one-stop shop
for everything Rucio. Lofty as it was, the amount of documentation that required conversion and
appropriate qualitative modification was large. Therefore it has been agreed upon to link the other
sources of documentation residing in [dockerhub](https://hub.docker.com/u/rucio), [wikis](https://login.cern.ch/adfs/ls/?wa=wsignin1.0&wreply=https%3A%2F%2Ftwiki.cern.ch%2FShibboleth.sso%2FADFS&wct=2020-10-19T06%3A52%3A41Z&wtrealm=https%3A%2F%2Ftwiki.cern.ch%2FShibboleth.sso%2FADFS&wctx=cookie%3A1603090361_ae8d), 
[scientific articles](https://arxiv.org/abs/1902.09857), & [Google Drive](https://drive.google.com/drive/folders/1EEN8l1dFjDSgavPrAMMooDjEodHP7aU7) on the landing page
while working upon removing the documentation dependency on source code. If time permits, the 
redundancy would be worked upon & addressed.

### Structuring of Documentation :heavy_check_mark:

The final documentation structure was ascertained with two  goals:

- Ease of Navigation
- Removal of Source Code dependency

With the [final prototype from this stage](https://divya-mohan0209.github.io/rucio-doc/), we've aimed to
leverage the capabilities of Docusaurus by utilizing the pandoc utility available for conversion from RST to MD.

### Fleshing out Content :heavy_check_mark:

Content was required to be restructured & in some places, there was a requirement for addition of content
to simplify it for new users. We've done that with the help of the existing content from different sources.

### Adding a Documentation Contributor Guide :heavy_check_mark:

A [contributing guide](http://rucio.cern.ch/documentation/docs/Contributing.html) was introduced so that users could better understand our repository structure & 
help in the maintenance/upkeep effectively.

### Revamping the contribution structure :heavy_check_mark:

The current setup was made more contributor-friendly by separating the documentation from the source.
This would lower the contribution barrier by allowing for the requester to familiarize themselves with
just the static site generators rather than starting off by knowing the entire technology. It would also
promote community-driven contributions.

### Final Design Touches :hourglass:

Some of the final design touches that we added were

- Integrating the Algolia Search Bar
- Setting up of GitHub actions for ease of community-driven maintenance & upgrade
- Setting up of Navigation bars in the Docs section
