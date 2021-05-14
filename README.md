Author Mahmoud
------
This code is used to download SAR data fro SSARA API using python you sould update the password_config.py with your earthdata login credentials.
The source code is downloaded from [here.](https://www.unavco.org/gitlab/unavco_public/ssara_client)
1. fix the ploblem of unicoding using urllib.
2. change the url for downloading orbit files from (https://qc.sentinel1.eo.esa.int/) to [current url.](http://step.esa.int/auxdata/orbits/Sentinel-1/)
3. add jupyter notebook file containg some exaple and work flow to extract .EOF file from zipped archive. 


Seamless SAR Archive (SSARA) project 
------

This repository contains software developed as part of the SSARA project, most notably will be a command line client used to perform federated queries with the API and utilities for data formatting and conversion.  Check out the Wiki for more information about specific elements of the project and you can create issues to let us now about any bugs or if you have a feature request.

For more information on the project and details about the API, [see the WIKI](https://www.unavco.org/gitlab/unavco_public/ssara_client/-/wikis/Home)

The API root for the SSARA federated query is:
http://web-services.unavco.org/brokered/ssara/




