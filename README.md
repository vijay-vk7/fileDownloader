# Objective

This script is intended to download the latest files from the [TNPSC](https://www.tnpsc.gov.in/English/press_releases.aspx) website which is greater than the last downloaded document id (it is assumed to be 26/2024 and this can be modified to any value between 1/24 and 35/24)
## Document list Table from TNPSC website
![enter image description here](https://drive.google.com/uc?export=view&id=1ziyRJHdwnOwdFrIrlAeTmIYkT_emdRoY)

# Setup

Ensure that selenium-side-runner and chrome driver is installed

# Cmd to Run the script

    selenium-side-runner -c "goog:chromeOptions.args=[headless,disable-plugins, disable-extensions, disable-popup-blocking, plugins.always_open_pdf_externally]" DownloadDocs.side

# Logs
![enter image description here](https://drive.google.com/uc?export=view&id=1Ukz7aAJFkAAqdBSAUtf45I_U0Qek2j4G)

# Downloaded files from the same project directory

![enter image description here](https://drive.google.com/uc?export=view&id=1O-h8yFxJjDSQP75xxFuw52KIQg1Xv-pZ)
