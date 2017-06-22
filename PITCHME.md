## GraphQL Learnings

#### Donald Plummer

---

## Where did we use it

* Used GraphQL instead of REST for the server->mobile app API interface: **Inception**
* Evaluated it in **content**, ended up removing it

---

## Refresher

* One POST endpoint
* Client specifies what data they want
* Server builds custom response for the client

---

## Bad

* Maintainability. The additional graphql code is a whole additional API that needs to be maintained.
* Caching. The graphql requests can't be cached effectively.
* Performance. The graphql API is slower because it has to parse and build the response new for each request.
* Lack of client in Elixir
* Maintenance of multiple code paths

---

## Good

* Client-side libraries (Swift & Javascript)
* Client-side updates
* Automatically-generated schema
* Easy batching
* Client & Server separation

---

## Unexpected

* Acceptance testing

---

## When to use

* When you have good client support (JS & Swift)
* Client-side (mobile & react)

## When not to use

* Server-server
