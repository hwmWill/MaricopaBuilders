# MaricopaBuilders
<em>Scraper for Maricopa County, AZ building permits.</em>

I downloaded weekly permit records from Maricopa County Building Department's online archive and filtered that data to only new and production residential permits.

I then created a subset of owner names for owners that own at least five homes and used this list of owner names to scrape business names, addresses and contact information from each owner name's first permit.

I merged this owner information with the permit data, kept only the permits pertaining to the owner names used for the previous step and created dataframe grouped by Business Name with columns for Business Name, sum of permit valuations, count of permits, contact name, contact phone number and contact email address.
