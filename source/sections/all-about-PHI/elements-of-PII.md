Obviously protection and privacy come into play once the individual can / has been uniquely identified. [There are after all 25.8 million Americans who have diabetes](http://ndep.nih.gov/diabetes-facts/). Which leads to the question of what data can be used to uniquely identify an individual. The generally accepted set of individually unique data elements include the [following](http://www.oshpd.ca.gov/Boards/CPHS/HIPAAIdentifiers.pdf):

| **ID** | **DATA ELEMENT** | **DESCRIPTION** |
|------|--------------|---------------|
| 1 | Name | Well, of course i.e. first name, last name, maiden name combinations. One could argue that just any <strong>one</strong> of the above doesn&#39;t uniquely identify an individual after all &quot;James&quot; is a pretty common name. But it could be possible to identify an individual using a combination of data i.e. first name, zipcode, street address etc. |
| 2 | Geographic locators | Everything (street address, city, precinct, zipcode, lat long coordinates etc.) are considered PII. The first three digits of the zipcode are usually considered ok for use except in the case of certain zipcodes which cover a small population (less than 20,000). There are currently 17 zipcodes that fit that profile - 036, 692, 878, 059, 790, 879, 063, 821, 884, 102, 823, 890, 203, 830, 893, 556, 831. So three digit zipcodes are ok to be used except for the above listed ones. |
| 3 | Dates | Pertaining to significant events in an individual&#39;s life - birth, death, marriage, admission, discharge etc. Just the year is generally considered fine for use except in the case of the very elderly (&gt;89 years of age; in which case they would be represented by an aggregate category e.g. =&gt;90 ) |
| 4 | Phone numbers | Well, of course. |
| 5 |Fax numbers | This is, IMHO, a carryover from the old days. Do you know a lot of people with a personal fax number? But, it does make sense. |
| 6 | Electronic mail addresses (email) | Check |
| 7 | Social Security Numbers | Check |
| 8 | Medical record numbers | This is usually a &quot;random&quot; number and could be used if one also knew the institution that assigned it. |
| 9 | Health plan beneficiary numbers | This is your insurance card / member ID. |
| 10 | Account numbers | Bank numbers etc. |
| 11 | Certificate/license numbers | Drivers license, birth certificate number etc. |
| 12 | Vehicle identifiers and serial numbers, including license plate numbers | If it&#39;s good enough for the police to track someone down... |
| 13 | Device identifiers and serial numbers | Medical devices have unique serial numbers. Your computer&#39;s MAC id is unique as well. |
| 14 | Web Universal Resource Locators (URLs) | This is a bit murky but is in here to cover all possibilities. <a href="http://www.facebook.com" rel="nofollow">http://www.facebook.com</a> isn&#39;t very unique. But if logged within a specific application, could indeed be very unique to an individual. |
| 15 | Internet Protocol (IP) address numbers | Your IP address can be used to easily identify your address. There are several free services that offer this (do a quick google search for <a href="https://www.google.com/search?q=address+from+ip&amp;oq=address" rel="nofollow">address from ip</a> and try this as an <a href="http://geobytes.com/get-city-details-api/" rel="nofollow">example</a> |
| 16 | Biometric identifiers, including finger and voice prints | Don&#39;t forget retinal images. |
| 17 | Full face photographic images and any comparable images | Check |
| 18 | Any other unique identifying number, characteristic, or code | Re: code - note this does not mean the unique code assigned by the system to code the data. |

These 18 elements are the core set of data elements that individually or in combination can be used to uniquely identify an individual. And, considering the fact that the above list of identifiers has **fax numbers** and not Twitter @usernames, Facebook IDs, or a host of other modern, more common identifiers, it's clear that the PII list is not the most up to date and some more thought should go into recognizing and protecting identifiable information. However, since patient data is valuable in clinical trials, medical case studies etc., the above list is used as a guideline to ensure privacy.
