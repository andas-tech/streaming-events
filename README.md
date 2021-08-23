# Streaming Event Streaming Service

Included in this repo is everything needed to run a small-form Apache Kafka service.

Important note: If you're intending to use this on a network, make sure to change the broker node IP/hostname addresses to allow for external comms.

## Standards

To minimize incompatibilities between consumers and producers, a few standards will be defined up-front.

### Message Formatting

JSON. Just use JSON.

### Topics

Topics can be anything, but should be formatted using snakecase (e.g.: interesting_topic)
