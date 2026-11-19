# lib-bis

Lets tackle running a small business and getting a job in banking / financial services which means one thing: Java. 
Together with a web frontend.

This is meant to run locally - it does have a local host web system but that does not directly connect to the dataStore. Instead it que updates via a file system. It should have a cache of data, that is then incrementally updates or receives the current state.

## auth

- solid auth / protect main data offline store - dont have it reachable via the web service
- make changes to the data, happen via local machine
- expose as little as possible

## message queue / API / Rest / humans

- allow devices and apis to send messages via queue system
- allow any web service to connect and update data

## charts, graphs, tables, plots

- the data we have should be presentable using a web viewer that has ability to reflect data in different formats just by changing the URL. THis is something I used to really like about ServiceNow.
  - so we can change a view just by doing `[HATEOAS]/graph` `[HATEOAS]/table` `[HATEOAS]/sheet` `[HATEOAS]/doc`

