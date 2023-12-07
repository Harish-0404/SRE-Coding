Health Check Script for Google Colab

Overview  

This script performs regular health checks on web endpoints, useful for monitoring the
health of APIs or web services. It's designed to be run in Google Colab, offering an easy and
accessible way to track the availability and responsiveness of these endpoints.

Features  

1. Supports GET and POST requests.
2. Utilizes a local YAML file for endpoint configuration.
3. Logs the status and latency of each endpoint.
4. Calculates and logs the availability percentage over time.
5. Easy to run in Google Colab.

Prerequisites:  

● A Google Colab account.  
● A local copy of the sample.yaml configuration file.  

Configuration:  

Prepare the sample.yaml File:  
● Create a sample.yaml file on your desktop or download in this repo
● Define the endpoints you wish to monitor. End points fetch are written.  

Upload to Google Colab:  

● When you run the notebook, upload this file to the Colab environment using
the file upload feature.  

Running the Script in Google Colab:  

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
