# CS305_Software_Security	

  In this project our client Artemis Financial was looking to update their server with more robust security.  Throughout the project we looked at their current security server configuration and code. We used dependency checks to find vulnerabilities within the NVD.  We also researched into these vulnerabilities to see if any were false positives and then ran the check again.  This led us to manually review the code to see if we found any errors that may have caused a security risk.  Artemis also was not using any form of encryption on the data that was being stored on their server, so we recommended that they use the NIST standard of AES.  Then we made sure that the server communications were secured with HTTPS by getting a security certificate and attaching it to the server.  This was all completed, and we created a report to send back to the company for them to review changes that we recommend.
