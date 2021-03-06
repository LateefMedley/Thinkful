### Automated Fatal Encounter Modeler

#### Defining a Fatal Encounter

Fatal Encounter - an encounter in which a US civilian made contact with representatives from one or more law enforcement agencies and died 
   - Does not include civilians who died in law enforcement custody

### Content - Files
* Powerpoint Presentation of what this model addresses, how it can be used, and quick exploration of the data
* Presentation Folder
    * Contains a notebook that compares an ARIMA model to a fbProphet model (a walkthrough of model EDA and more)
    * Contains a fbProphet model plot comparing the actual observed values to 121 predict values and includes an additional 50-day projection forecast
    * Contains an ARIMA model plot comparing the actual observed values to 121 predict values and includes an additional 50-day projection forecast
* The Product
    * Python notebook that can be run to request a report of fatal encounters in the US as a whole or any state, and most cities, most counties, and most zip codes.
    * fbProphet model tuned to the fatal encounter data I have available regarding the state of California (as an example, but you can request any of the above-listed areas by replying to the prompt generated)
    * 3 Spreadsheets
        * A time series of actual fatal encounters
        * A time series of predicted fatal encounters
        * A spreadsheet of those encounters including the full record on file of the encounter

### The Purpose

The goal of this work is to provide a look into what has happened regarding civilian fatal encounters with police over the last 20 years by region and to predict what may happen based on the trends and seasonality we have already observed. It is my hope that this information will enlighten civilians and law enforcement, and overseeing agencies of the risk of ignoring problems in policing, not only as it pertains to minority groups, but as it pertains to all the stakeholders regarding the crucial work of policing. These encounters, when negatively viewed by the public make the line of this work more dangerous, but comprehensive reporting and analytics regarding this matter on a national scale is scarce. That may be because there are over 10,000 law enforcement agencies and major inconsistencies in reporting which lends itself to the unhealthy narrative of secrecy regarding public policing. “Secrecy in police work is not only undesirable but unwarranted. Accountability means being responsive to the problems and needs of citizens. It also means managing police resources in the most cost-effective manner. It must be remembered that the power to police comes from the consent of those being policed.” The Community Relations Service (CRS), a component of the U.S. Department of Justice.

Quick Note about the availability of this data 

“The nation’s leading law enforcement agency [FBI] collects vast amounts of information on crime nationwide, but missing from this clearinghouse are statistics on where, how often, and under what circumstances police use deadly force. In fact, no one anywhere comprehensively tracks the most significant act police can do in the line of duty: take a life,” according to the Las Vegas Review-Journal in its series Deadly Force (Nov. 28, 2011) During my search for this data I can say that some summary statistics are available to the public, but I had a hard time finding a tabular form of encounters. 

Fatal Encounter’s word about the data

The data I am using comes from the non-profit “fatal-encounters.org.” Here’s a note from their website, “A quick word about the data: At over 28,000 records, it’s tempting to consider this a comprehensive dataset. It’s not. While we completed the systematic states-by-year searches of the United States on November 3, 2017, we know we’ve missed some. This set was never intended to do anything except identify the names, demographic information, dates, and locales of the dead and to give us direction for categories that needed further research.” 

### Acknowledgements
Special Thanks to the founder of FatalEncounters.org, D. Brian Burghart 

Read more about him here: https://fatalencounters.org/about-me/
