# SRE-Coding Challenge 

Overview
This script performs regular health checks on web endpoints, useful for monitoring the
health of APIs or web services. It's designed to be run in Google Colab, offering an easy and
accessible way to track the availability and responsiveness of these endpoints.
Features
● Supports GET and POST requests.
● Utilizes a local YAML file for endpoint configuration.
● Logs the status and latency of each endpoint.
● Calculates and logs the availability percentage over time.
● Easy to run in Google Colab.
Prerequisites
● A Google Colab account.
● A local copy of the sample.yaml configuration file.
Configuration
Prepare the sample.yaml File:
● Create a sample.yaml file on your desktop.
● Define the endpoints you wish to monitor. Here&#39;s a sample format:
yaml
Code:
- headers:
user-agent: fetch-synthetic-monitor
method: GET
name: fetch.com index page
url: https://fetch.com/
- headers:
user-agent: fetch-synthetic-monitor

method: GET
name: fetch.com careers page
url: https://fetch.com/careers
- body: &#39;{&quot;foo&quot;:&quot;bar&quot;}&#39;
headers:
content-type: application/json
user-agent: fetch-synthetic-monitor
method: POST
name: fetch.com some post endpoint
url: https://fetch.com/some/post/endpoint
- name: www.fetchrewards.com index page
url: https://www.fetchrewards.com/

Upload to Google Colab:
● When you run the notebook, upload this file to the Colab environment using
the file upload feature.
Running the Script in Google Colab
Open a New Colab Notebook:
● Navigate to Google Colab and start a new Python 3 notebook.
Upload the Script and YAML File:
● Upload the health check script and your sample.yaml file to Colab.
Install Dependencies:
● Run the following in the first cell to install necessary packages:
● python

!pip install requests pyyaml

Run the Script:
● Run the script in a subsequent cell. The script will start monitoring the
endpoints defined in your YAML file, logging their status and response times.

Customization
You can customize the script by modifying the logging levels, frequency of checks, and the
structure of the YAML configuration file to suit your needs.
Contributing
Feel free to fork and adapt this project. Contributions for additional features or
improvements are welcome.
