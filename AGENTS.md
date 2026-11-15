# CLAUDE.md

Dockerized Snoop OSINT username-search tool. Fork / vendored copy of upstream snooppr/snoop; remote `andrius/snoop`.

- Base: `python:3-alpine`; installs `requirements.txt`, entrypoint `docker-entrypoint.sh` -> `snoop.py`.
- App data: `data.json`, `domainlist.txt`, `websites.md`.
- Last commit: 2020-07-20.
