# openapi-tms-server

OpenAPI Specification for TMS Credential Server

Contains this README file and the openapi specification file: tms_server_openapi.yml

There are four branches: local, dev, staging and prod.

All changes should first be made in the branch *local*. Work in progress can be pushed to local
without impacting live-docs.

Updates can then be moved from *local* to *dev* when the code in *tms_server* is updated to match
the openapi spec and deployed to the DEV kubernetes environment on tms-dev@login-shared.tacc.utexas.edu

Moving from *dev* to *staging* and finally *staging* to *prod* should proceed in the same manner.

The links in the live-docs repostiory index file located at
```
https://github.com/tms-trust-project/tms-live-docs/blob/main/live-docs.js
```
should point to the `yaml` file located here.

