# lib-bis

Lets tackle running a small business and getting a job in banking / financial services which means one thing: Java. 
Together with a web frontend.

This is meant to run locally - it does have a local host web system but that does not directly connect to the dataStore. Instead it que updates via a file system. It should have a cache of data, that is then incrementally updates or receives the current state.

# data
- pivot into entities - turn anything into the system so we can track and use the rest of the system
- normalise for ai friends and humans
- ....

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

## connecting to existing data systems

- handle two factor // multi factor
- handle open banking
- handle investment systems
- handle trading

## create a simulation and prediction system

- predict performance, markets, simulations and how to survive on zero budget!
- highlight unusual things within the system, data and locality
- do some fun stuff

### since we want a job do some really fancy graphics
- fancy graphics
- huge data and real time elite level coding
- realtime stuff

