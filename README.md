# tealiumTMS with Criteo One tag

- the implemt guide (public)
https://community.tealiumiq.com/t5/Client-Side-Tags/Criteo-OneTag-Tag-Setup-Guide/ta-p/12381#toc-hId--445779444

- Go to the my.tealiumiq.com then config these:
  - Add new tag --> select criteo OneTag
  - input the account id 
  - setup the load rules
  - mapped the utag.data to Onetag
    - trigger with the matched value from the data source (utag.data.xxx)
    - Gerneral info data: site_type, hashed_email ... 
    - other specific data based on the specific tag type such as product ID for product tag