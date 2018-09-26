# Pulse Beacon

A GitHub App that is attached to repositories. It emits events to Stargate (which is running in the constellation server, inside the galaxy project). This app connects a repository to the ingest server of the CI/CD tool.


## Notable Events

* First add this app to a repository (unknown event type)

* New PR's are created


## Notable Interactions

* App should notify of missing requirements (`ci/` folder, `pipeline.yml`, `pr.yml`, etc)
