# FLiP-CloudQueries
StreamNative Flink SQL Cloud Queries


## Queries

```

select cputempf, gputempf, diskusage, cpu, systemtime, uuid
from iotjetsonjson
where cputempf > 105

select *
from iotjetsonjson

select cputempf, gputempf, diskusage, cpu, systemtime, uuid
from jetsoniot2
where cputempf > 105



```
