# Proxy Comparator
Moving from AzureAD only to On-Premise sync is a process that no System Administrator really wants to do, and small variances can bring catastrophic consequences that may not be apparent for a long time. One of the areas of this conversion that often brings issues is the process of pulling all Proxy Addresses into Local AD so that when sync enables, you keep all email aliases. That's what this application is for; to check that proxy addresses in one location matches with proxy addresses in another.

## Features
:white_check_mark: All calculations are local only, so no sharing data with servers

## Prerequisites
To run this application, you will need:
- A web server to host the app