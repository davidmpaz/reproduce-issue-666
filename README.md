Reproduce Error
===============

Repo to reproduce issue: https://github.com/prometheus/jmx_exporter/issues/666

## Running as http server

1. `git clone git@github.com:davidmpaz/reproduce-issue-666.git`
2. `git checkout exporter-as-server`
3. `docker-compose up -d`

## Running as java agent

1. `git clone git@github.com:davidmpaz/reproduce-issue-666.git`
2. `git checkout exporter-as-agent`
3. `docker-compose up -d`

## Notes

If changing branches to test after executing `docker-compose up-d`, be sure to take down the stack with: `docker-compose down` in order to start fresh again.
