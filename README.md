# Polymorphic API Service Manager
### Implemented with Typescript and React

The purpose of an API manager is to handle a web service, from its authentication to making requests and handling responses -  that will either generate a successful result or a failure. 

The manager must ensure type safety along the way; it is fully typed, as are the request and response objects you expect to receive. 

To prevent re-inventing the wheel, requests are sent via Javascript's native `fetch()` API, that works hand-in-hand with the manager.
