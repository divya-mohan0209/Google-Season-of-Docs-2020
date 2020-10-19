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

While prototyping, we first focussed on converting the Sphinx-generated RST files to a more widely used format. HTML & Markdown
were the two options that were immediately narrowed down due to their simplicity. For initial prototyping, we attempted to 
utilize various themes within Sphinx and place the file as static content under the website directory for Docusaurus.

One of the earliest [prototypes](https://divya-mohan0209.github.io/docusaurus-current-theme/rucio/) we created was utilizing the existing ReadTheDocs theme.







