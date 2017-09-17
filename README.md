# WATchTower
Threat notifications direct to you.

## Inspiration
Everyday, thousands of pieces of malware go live on the internet. Some of them rely on user inexperience. The most successful of these are those that exploit vulnerabilities in the code running on a device in order to extract information. Anything from SQL injection, API abuse, to downright backdoors into operating systems cracked open by a couple clever lines of code. We decided to do somthing about it

## What it does
Our firebase application is a full package. It is primarily a provider of accurate and personalized vulnerability and threat alerts to the user's specific systems. But also is available to directly intervene and update packages on remote servers on command.

## How we built it
We built this app on the google firebase API which combines databases and hosting services in one. The app uses the Cymon API to track malicious instances within physical proximity, as well as custom webscraper which allows us to access the vast online vulnerability databases. Furthermore, we have created a linux environment daemon which is able to provide up to date information on the systems we protect. It even has the capability to execute certain whitelisted commands upon a server's checkin.

## Challenges we ran into
We found that the firebase API is incredibly powerful, so much in fact that we managed to overload the databases and crash the instance for a few minutes. Furthermore, we found the need to supplement the information provided by cymon. The intricacies of firebase were many, but we bested them.

## Accomplishments that we're proud of
A big app with a ton of features and a lot of code diversity

## What we learned
Firebase is amazing. Webscraping is notoriously hard, and so are cloud functions with an obfuscated data retrieval system.

## What's next for WATchTowr
Expansion and more features. More ability to edit remotely and automating the process of fixing the issues. 
