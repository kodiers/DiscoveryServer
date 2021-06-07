### RUN AXON:
```docker run --name axonserver -p 8024:8024 -p 8124:8124 -v "./axonserver/data":/data -v "./axonserver/eventdata":/eventdata -v "./axonserver/config":/config axoniq/axonserver```