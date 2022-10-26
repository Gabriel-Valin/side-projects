## API WITH CACHE 

Implements a simple project (API) that should contains cache to show results.

Cache can be implemented with InMemoryDB, Redis, node-cache, SQLITE, others...

Description:

    -   endpoint should returns 1000 results with no-cache
    -   endpoint should returns 1000 results with cache
    -   endpoint should returns results and message saying that cache is enabled
    -   if the return from endpoint is not cached should return message saying that cache is disabled