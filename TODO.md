## Nautical TODO

1. Finish prek setup

  - prek should add license to each source file
  - prek should make sure go codebase is properly formatted and linted
  - prek should prevent committing to main

2. Finish mise setup

  - mise should include tasks for building
  - mise should include tasks for testing

3. Init all services

  - All services should be started. EX: base CLI tool, REST APIs, and UI should be initialized

4. Init container files

  - Container files should be created for building and running the application
  - Should utilize my OpenShift compliant images
  - docker-compose.yml should be created for running the application locally

5. GitHub actions

  - GitHub actions should run the same tests as mise
  - Beta tag should be used until initial release for each component is ready
  - Once initial release is ready, semantic release should be used to tag and release

6. Helm charts

  - Helm charts should be created for deploying the application to Kubernetes
