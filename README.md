## Find more details in official link [Staqlab tunnel](https://tunnel.staqlab.com/)

   - Oe Step Connect Using NPX npm
     ```
     npx staqlab-client <port> hostname=<desired-hostname>
     ```
   - Use in your NodeJs Code
     ```
   
     const StaqlabTunnelClient = require("@staqlab/staqlab-tunnel/StaqlabTunnelClient");
   
     //3000 is desired port and hostname is desired hostname you want
     let staqlab-tunnel-arguments="3000 hostname=spider-man";
   
     new StaqlabTunnelClient().init;
     ```  

-  How To Connect Using System binaries
   - Download sarkaribabu-tunnel.sh using below command<br>
      ```
     Linux:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/linux/staqlab-tunnel.zip
     Mac:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/mac/staqlab-tunnel.zip
     Windows:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/windows/staqlab-tunnel.zip --no-check-certificate
     ```
   - Unzip Downloaded File<br>
 
    - Run Agent by typing command<br>
      ```    
      Linux / MacOs:
      ./staqlab-tunnel <port>
      
      Windows:
      staqlab-tunnel <port>
       ```
         - port is desired port where you local server is listening
     - Optional Parameters
       <br>
         ```
       ./staqlab-tunnel port=<port> hostname=<desired-domain>
       ```
         - desired-domain is domain of your choice which you want to point to your localhost
         
         
   What is staqlab tunnel?<br/>
   Staqlab tunnel is a alternative to ngrok.com or serveo.com which allows you to expose your localhost to
   the public internet and get a public url which you could share anywhere and get a public domain name for it. ,i.e, 
   keeping it simple you could host server on your local machine.<br/>
   It also does have support for custom domain which makes it easy to develop webhooks integrations for shopify, nexmo,
   facebook, github, wordpress or similar 3rd party app developments <br/><br/>
   Another miscellaneous usages includes<br/>
   - Hosting server on your machine
   - Creating public link for QA or beta users for pre-release testing
   - IOT development 
   - ESP8266 Integration
   - Devopps Purposes
   - Debugging code issues
   
   Supported/Tested Webhook Integrations(not limited to, but includes)
   - Zoom Webhook integration
   - Shopify Webhook Integartion
   - Zapier Hooks
   - Zendesk Hooks
   - IFTTT Automation and DIY
   - Airtable Webhhoks     