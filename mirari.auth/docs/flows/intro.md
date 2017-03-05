# Auth Flows

### User interaction flows
There flows requires a human interaction at some point.

- [Authorization Code Flow](AuthorizationCodeFlow.md)
  1. Request authorization
  2. Request token
  3. Access resource

- Implicit Flow
  1. Request authorization and token 
  2. Access resource

### Non-User Interaction flows 
These are none human flows that are user for machine-machine scenarios.


- Resource Owner Password Credential Flows
  1. Request token with resource owner credentials
  2. Access resource

- Client Credential Flow
  1. Request token with client credentials
  2. Access resource
