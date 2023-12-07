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
● A local copy of the sample.yaml configuration file and code.ipynb file. 

Running the Script:
1. Open the Google Colab  
2. From File Select the Upload Notebook option and Upload the code.ipynb file
3. From the files tab on left toolbar upload the sample.yaml file
4. Run the Script using play button

Sample Output:  

![Screen Shot 2023-12-07 at 3 24 10 PM](https://github.com/Harish-0404/SRE-Coding/assets/82347301/279cd2b0-04f2-4866-9cf3-f1c971afcc83)  


 
Customization  
You can customize the script by modifying the logging levels, frequency of checks, and the
structure of the YAML configuration file to suit your needs.
Contributing
Feel free to fork and adapt this project. Contributions for additional features or
improvements are welcome.
