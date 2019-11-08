# TokenBucket

A simple C# token bucket interface and implementation. The token bucket was originally
created for clients trying to obey an external rate limit. Because of this there is
emphasis on spreading requests and avoiding fenceposts.

Originally created for use in [Camille](https://github.com/MingweiSamuel/Camille),
a Riot API library.
