# elk-iis
ELK stack to import and parse IIS logs


### Setup

- Put logs in ./logs as *.log
- Adjust grok pattern in iis.conf

```cli
> docker compose up
```
Open http://localhost:5601 in a browser

# References
- https://github.com/JimmyHurrah/iis-elk-logs
- https://knowyourtoolset.com/2018/09/quick-analysis-of-web-logs-iis-or-nginx-with-the-elk-stack
- https://github.com/spujadas/elk-docker
