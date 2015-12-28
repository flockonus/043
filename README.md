# name it:

Knowledgekeepers

info keepers

data keepers

p2pi --taken

043 (!)


# concept:

1) software that does work [& store data (most of times)]
2) public facing api that:
  2.1) has a defined structure (way to expose and list)
  2.2) can rate limit
  2.3) provide schema for all data sorts
3) 


## idea of operation:

1. install a module
2. configure (with API key / interval)
3. automatically make available through API
4. register at trackers


## cases to thinker about:

Fb community trend;
Self twitter follow;
Previsao do tempo previsto vs. real

### Fb community example:

Read all communities i have access on Facebook, store their basic numeric stats.
Perhaps monitore some more communities i want it to.
Require my FB oauth token
Will run a task daily

npm i --save 043-fb-community-count
Run interactive prompt, like bower or npm:

- Configuration process, will be stored to config/043-fb-community-count
- periodical config:
- this module require to run a task once a day, are you ok with it? (Y/n)
-   [if no just abort it nicely]
- do you allow it to record stats on every community you have access to (Y/n)
- would you like to keep tab on some addicional communities? (y/N)
- paste in the url followed by enter (empty to stop)

on success should register to 043's cron hook

...continue to describe package configuration format and methods required

### common operation example:

obs: cron executes periodically a hook facade to manage registered packages

043 should be running as much as possible (require PC on + online)
043 should register to tracker list (at least 3?), send periodical heartbeat, offer list of packages properly installed along some basic top level stats
043 should be available for requests (via webrtc)

