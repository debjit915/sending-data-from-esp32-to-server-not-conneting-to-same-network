Replace your_SSID, your_PASSWORD, and http://your-server.com/upload with your actual WiFi credentials and server URL.
Ensure your server-side script at http://your-server.com/upload is set up to handle incoming POST requests and store the data appropriately.



Create a Google Apps Script:

In the Google Sheet, go to Extensions -> Apps Script.
Delete any code in the script editor and replace it with the following:
paste the script given 

Deploy the Script as a Web App:

Click on Deploy -> New deployment.
In the "Select type" dropdown, select "Web app".
Set Execute as to Me and Who has access to Anyone.
Click Deploy.
Authorize the script with the required permissions.
After deployment, you will get a URL for the web app. Note this URL, as it will be used in the ESP32 code.


replace the server url with the url it will provide after completeing the steps 
