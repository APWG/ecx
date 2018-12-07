# eCrime eXchange (eCX) Code Repository

<h2>Overview</h2>

<br>
A repository of code and command line examples to interact with the APWG's eCrime eXchange API (eCX API).  Each script requires an eCX API token key to provide access to the eCX APi<br> 

If you hae code to contribute via a fork, please <a href="mailto:support@ecrimex.net">contact us</a>.<br>
<br>

<br>
<h2>Getting Started</h2>
You can find documentation about the eCX API <a href="https://www.ecrimex.net/api">here</a>.<br>
<br>
We also suggest you take a look the <a href="https://github.com/APWG/ecx-api-client">eCX API client</a> written in PHP by the developers of eCX.<br>
<h2>Testing</h2>
We have a sandbox for the eCX API located at https://api.sandbox.ecrimex.net for you to test your code on.  It is updated nightly at midnight GMT with new data from production. 
<br>

<h2>Repositories</h2>
<br>
<h3>Available</h3>
<h4>GET</h4>
<ul>
<li><a href="https://github.com/APWG/get-cli-curl">Example of how to GET data from the eCX /phish endpoint using cURL on the command line</a></li>
<li><a href="https://github.com/APWG/get-cli-wget">Example of how to GET data from the eCX /phish endpoint using wget on the command line</a></li>
<li><a href="https://github.com/APWG/ecx-api-pagination-python">GET data from eCX, using pagination (Python)</a></li>
<li><a href="https://github.com/APWG/csv-export-with-date-range">GET CSV data from eCX using a date range</a></li>

</ul>
<h4>POST</h4>
<ul>
<li><a href="https://github.com/APWG/post-cli-curl">Example of how to POST data to eCX /phish endpoint using cURL on the command line</a></li>
<li><a href="https://github.com/APWG/post-cli-wget">Example of how to POST data to eCX /phish endpoint using wget on the command line</a></li>
<li><a href="https://github.com/APWG/crypto-bulk-import-csv-from-command-line">Bulk upload CSV data into the Virtual Currency Workgroup</li>
</ul>
<h4>PATCH</h4>
<ul>

</ul>
<h3>Awaiting Development</h3>
<p>We've split this up by eCX API REST verbs, GET to grab data, POST to send new data into eCX, and PATCH to update existing data, and some extended examples</p>
<ul>

<li><a href="https://github.com/APWG/ecx/#">GET all data from eCX that is newer (date modified) than the last GET</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET all data from eCX that is newer (ID) than the last GET</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a single phish entity by ID</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a single phish entity by exact URL</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a single phish entity by wildcard URL</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by TLD</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by Domain</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by wilcard Domain</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by ASN</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by Brand</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by wildcard Brand</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by ASN</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by IP</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET a list of phish by CIDR</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET data from eCX, and export into Splunk</a></li>
<li><a href="https://github.com/APWG/ecx/#">GET data from eCX, and export into Syslog</a></li>
<li><a href="https://github.com/APWG/ecx/#">Maltego Xforms/scripts to pull data elements from eCX and visualize in Maltego</a></li>
</ul>
<ul>
<li><a href="https://github.com/APWG/ecx/#">POST a phishing URL to eCX</a></li>
<li><a href="https://github.com/APWG/ecx/#">POST data to eCX via a bulk CSV uploader</a></li>
</ul>
<ul>
<li><a href="https://github.com/APWG/ecx/#">PATCH existing eCX data using ID</a></li>
<li><a href="https://github.com/APWG/ecx/#">PATCH existing eCX data using URL</a></li>
</ul>
<ul>
<li><a href="https://github.com/APWG/ecx/#">Find an IP pulled out of /phish in the /mal_ip endpoint (* must have access into both modules)</a></li>
</ul>
<br>
<h4>eCX API Documentation</h4>
The eCX API documentation is built in OpenAPI/Swagger format

<br>
<h2>Questions or Concerns?</h2>
Please <a href="mailto:support@ecrimex.net">contact us</a>.

