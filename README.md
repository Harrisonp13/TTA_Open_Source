Fixing Documentation Links for Bokeh
This repository hosts our contributions to the Bokeh open source project, specifically aimed at addressing certain documentation inaccuracies. Bokeh is an interactive visualization library for modern web browsers. It provides elegant, concise construction of versatile graphics, and affords high-performance interactivity over large or streaming datasets.

Overview
The focus of this contribution is to correct two broken links found in the advanced programming with Bokeh section of the Bokeh documentation. These incorrect links lead users to 404 pages, reducing the quality and accessibility of the documentation.

Incorrect Links Identified:
Developing with JavaScript: Incorrectly directed to a non-existing page.

Current (Broken) URL: https://docs.bokeh.org/en/dev/docs/user_guide/bokehjs.html
Correct URL: https://docs.bokeh.org/en/latest/docs/user_guide/advanced/bokehjs.html
Jupyter Notebooks: Incorrectly linked, leading to a 404 error.

Current (Broken) URL: https://docs.bokeh.org/en/latest/docs/user_guide/jupyter.html
Correct URL: https://docs.bokeh.org/en/latest/docs/user_guide/output/jupyter.html
Goals
Correct the Broken Links: Update the links to point to the correct URLs.
Improve Link Maintenance: Suggest and implement the use of Sphinx :ref: links where applicable to prevent similar issues in the future.
Review Additional Links: Although not currently broken, review and potentially update the "Bokeh server" link to use the Sphinx referencing system as a preemptive measure.
