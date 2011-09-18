## Using processes and tools to make a team more efficient

## This is how we do it at Engine Yard

## Pick up a ticket
* Consistent naming
* Tagging of commits

## Pairing
* Tete-a-tete (susser)

## Run focused specs locally
* CI gets the whole suite
* Only run the obvious ones locally

## Push to CI
* Show ensemble
* UI is Campfire
* Web is read only
* Picks up new branches
* Show rebuilds
* Describe Units
* Describe Ensemble

## EyBot
* HTTP Endpoints
* Small Library
* Ensemble doesn't talk to the bot, it's just one of the endpoints

## An aside about CI
* CI is simple
* Just a job runner, basically
* CI is not the hard pard
* CI is not the interesting part
* Integration is what matters

## Ticketing system
* Integration is important
* How we use youtrack (mark things merged)

## Describe release/deploy
* Tag the release
* Merged tickets get assigned to the release

## Deploy the release
* Standard style deploy
* Just uses mason, (it's just a job runner)

## Non-destructive migrations <-- super important!
* Run migrations post deploy
* No maintenance page

## Notifications
* Mark tickets in the release as deployed
* Send email with changelog
* Notify -Hoptoad- Airbrake
* Notify New Relic

## What's next
* This has always been a side project at Engine Yard
* Make deploys faster, be smarter about migrations
* Automate merging, currently have tons of branches that hang around, due to not cleaning up
* Streaming logs from mason
