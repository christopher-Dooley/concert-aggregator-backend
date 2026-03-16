# Concert Aggregator Backend

### Concert storage
- some unique id, probs uuid
- Date
- Event name
- Venue
- Artist
- link to listing/ticket purchase page

| ID   | Date | Name   | Venue  | Artist | Link   |
|------|------|--------|--------|--------|--------|
| UUID | Date | String | String | String | String |


### Scrape config
- time ahead

| Config item name | Config Item Value |
|------------------|-------------------|
| String           | String            |

### Venue 
- id
- Venue name
- City
- main listings url
- last scrape datetime

| ID   | Venue name | City   | Listings link | last scrape |
|------|------------|--------|---------------|-------------|
| UUID | String     | String | String        | Timestamp   |

Might also need (later):
- pagination config
- scrape template?

haven't figured out the scraping yet

Future ideas:
- genre identification