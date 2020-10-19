# Community Bonding Phase (August 17, 2020 - September 13, 2020)

As detailed in the [README](https://github.com/divya-mohan0209/Google-Season-of-Docs-2020/blob/main/README.md), the community bonding phase focussed on setting 
the tone for the duration of Google Season of Docs, 2020.

In addition to deciding on the cadence, sectioning, and agility below is the list of high-level goals 
that were to be achieved by the end of this phase. Since most of the timeframes for most of the goals
overlapped, they have not been specified.

## Goals

### Gain a solid understanding of existing toolset :heavy_check_mark:

- [Existing documentation](https://rucio.readthedocs.io/en/latest/) was built using the [readthedocs theme](https://sphinx-rtd-theme.readthedocs.io/en/stable/) on [Sphinx](https://www.sphinx-doc.org/en/master/)
- The source was in the [codebase for Rucio](https://github.com/rucio/rucio/tree/master/doc/source)
- Source code for documentation was in the form of RST files on account of Python environment

### Gathering requirements :heavy_check_mark:

- Separation of source code & documentation hosting
- JSX support
- Overall transition to MD, if possible, & elimination of dependency on Sphinx
- Qualitative improvements

### Research tools fitting the requirement :heavy_check_mark:

The [document assessing potential candidates](Potential candidates for Rucio Documentation.pdf) has been uploaded for ready reference.
Since Docusaurus fit the bill, it was chosen to be the tool we migrate the Rucio documentation to. 

### Prototyping :heavy_check_mark:

While prototyping, we first focussed on converting the Sphinx-generated RST files to static HTML using standard themes provided by Sphinx.
Since this was later found to be counter-intuitive in removing the dependency on Source code & simplifying the process, it was decided to
directly convert the RST files into MD.
A few of the Initial prototypes with Sphinx themes and Docusaurus are listed here:

- [Solar theme for Sphinx](https://divya-mohan0209.github.io/docusaurus-solar/rucio/)
- [Alabaster theme for Sphinx](https://divya-mohan0209.github.io/docusaurus-alabaster/rucio/)
- [Primary prototype for utilizing only Docusaurus](https://divya-mohan0209.github.io/docusaurus-nature/docs/)
- [Final prototype to progress into Doc Development Stage](https://divya-mohan0209.github.io/rucio-doc/)




