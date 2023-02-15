# Scenario

Using a platform called VirusTotal which allows you to scan different security indicators to see whether or not they have been flagged as malicious. Your task as part of this is to write a Python script that interacts with VirusTotal to bring back information on the below indicators as well as fulfil the required success criteria

Indicators:

* google.com
* myetherevvalliet.com

## Success Criteria

* Must make a request to VirusTotal for both the indicators specified above
* For each indicator, we want a message that indicates whether or not that indicator is safe or not. Make it an obvious print message when the indicator is marked as malicious
* Once you have checked an indicator once, add it to either a list of malicious indicators or safe indicators depending on the result from VirusTotal. Make sure that if the indicator is in one of those lists, we do not check it against VirusTotal

### Challenges

* Can you set an expiry on each indicator? The end goal here, is to store all the indicators you have checked against VirusTotal in a list, with an expiry date. Once you pass this expiry date for that indicator, the indicator is to be checked against VirusTotal again. This can be any duration you like

## Pre-reqs

* You must sign up for an account at VirusTotal. You can sign up [here](https://www.virustotal.com/gui/join-us), it's **free**.
* Read the documentation to familiarise yourself with the API and its purpose. You can view the documentation [here](https://support.virustotal.com/hc/en-us/articles/115002739245-Searching)
