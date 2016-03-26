# Military Installations Data
A dataset containing addresses, phone numbers, and an (imperfect) geocoding for on-base services used by military families--hospitals, gyms, etc.

# Overview
I started with data available at http://www.militaryinstallations.dod.mil/.  The original data was not geo-tagged and contained inconsistent categories.  I cleaned it up for consistency and geo-tagged the addresses with Google's Geocode API.

# Known Issues
The geocoding is wildly off in certain areas, due to addresses in the original data being incomplete.  Addresses and phone numbers are also only as accurate as what was in the original data, meaning many are likely old or incomplete.  
