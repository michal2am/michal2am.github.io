ORCID iD icon
-------------
The ORCID link in index.html shows the file  icons/orcid.svg
ORCID requires its iD icon to be used exactly as provided, so it is not drawn
in the page code. Download the official green SVG icon from the ORCID brand
library (linked from https://info.orcid.org/documentation/integration-guide/orcid-id-display-guidelines)
and save it in this folder as:

    orcid.svg

Until that file exists, the page shows a plain ID-card symbol instead.

The same works for any other link: put an official logo file here and replace
that link's <svg>...</svg> in index.html with
    <img src="icons/NAME.svg" alt="" width="16" height="16">
