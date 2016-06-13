## pganalyze Snapshots

Snapshots are the format in which the pganalyze collector and the statistics processor
communicate. Snapshots are encoded using Protocol Buffers.

The collector takes statistics data from a PostgreSQL database server, puts it into an
easy-to-consume format, and encodes it using Protocol Buffers.

See also the [collector](https://github.com/pganalyze/collector) output/ directory.

## LICENSE

Copyright (c) 2016 pganalyze<br>
Licensed under the MIT License.
