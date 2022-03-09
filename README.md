# Mad Maids Data

This repository deals with scraping various intranet pages and keeping scraped data up-to-date.
Currently there are two scraper scripts in the `scrapers` directory:
- `scrape_groups.py`, which gets all the lessons data for undergrad groups. All the data generated by this script is located in the `timetable` directory.
- `scrape_rooms.py`, which obtains the data on all empty rooms by scraping all classrooms' vacant time slots. The relevant data generated by this scraper is in `rooms` directory.

**NOTE:** the latter of the two scripts (`scrape_rooms.py`) is still a work in progress and therefore is likely to be modified in the future.
