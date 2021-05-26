# Uipath_AmazonBookData
This bot works following the Robotic Framework Template and orchestrator.
This bot was created using Uipath community license (free) and trial version of Office 365

Exercise in Uipath that retrieves book´s data from Amazon, using Chrome.
Then add the non-zero price books to excel file.
Finally send the excel file via email using Outlook.

Programs needed:
Excel (2020)
Outlook (2020)
Chrome (plugin compatible)
Uipath - Chrome Plugin

Files needed:
Config.xlsx (included)

Orchestrator:
Queue - name according to the Config file and orchestrator
  For the records to be processed.
  
Assets - name according to the Config file and orchestrator
  webpageURL
  emailDestinatary
  searchCriteria
  
Permissions:
Uipath Plugin: Enable
Outlook: Trust center - No permission requests
  
