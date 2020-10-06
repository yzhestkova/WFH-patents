## Parsing XML patent bulk and identify patents related to WFH technologies

The codes in this depository take weekly published XML patent application data from USPTO bulk downloads, parse them into a dataframe, extract key information about the patent and identify patents related to WFH technologies using text analysis.

<p>&nbsp;</p>

__wfh_patents_biography_data.ipynb__ parses patent application bibliographic data and extracts WFH patents based on patent title and abstract only. The final output is a dataframe with patent application number, title, abstract, class, application date, application publishing date, assignee and a flag for WFH technologies.

<p>&nbsp;</p>

__wfh_patents_full_text_data.ipynb__ parses full text of patent applications and extract WFH patents based on full text of an invention description.

<p>&nbsp;</p>

### Libraries needed:
* pandas
* pandas_read_xml as pdx
* numpy
* re
* os
