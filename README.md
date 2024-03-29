# Midata Hackathon 2012
## Open Data Institute
http://www.theodi.org/events/midata-hackathon-2012

These are the generated files for the "Data Suckathon" project (using D3.js http://d3js.org/):
http://davidcarboni.github.io/midata-hackathon-2012/ (use next/back links to navigate)

The dataset is the headings (or keys) found in several thousand .csv files downloaded from http://data.gov.uk/ by crawling the site via the CKAN API (http://data.gov.uk/data/api).

There are two visualisations of this dataset, which you can click and drag. The visualisations are:
 * frequency with which a heading appears. This is a free-floating bubble visualisation where the biggest bubbles represent the headings found in the largest number of CSV files. The colour of the bubbles relates to the exact number of files in which a particular heading occurs.
 * relationships between files containing similar headings. This one may take a few seconds to render. It is a force-directed network visualisation. Here all nodes are the same size and represent either a single CSV file, or a heading. CSV files are pink and headings are shown using the same colours as the first visualisation. In this visualisation, links between nodes represent headings that nodes have in common. This gives you an idea of how many files share the same headings.

The idea is to demonstrate how visualisation instantly draws attention to features of a dataset which are not apparent from the raw data.

In this case we have a view of which attributes are most commonly recorded in open government data and how files are clustered around commonly-recorded attributes.

And it's quite pretty too.

David
