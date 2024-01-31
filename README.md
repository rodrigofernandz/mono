# mono

**Please check the primer.pdf file**

Each service should have it's own Makefile with the specified targets:
- test
- deploy
- run 

The ideia it's to have a pattern where the workflows will be able to deal with specific deployment for some applications. In this case the services specific makefile need to have the required named targets having it's own implementation. 

Deployments and tests are executed by Github Actions workflows.  

Please, note that this is a very high level implementation on what the repo should look like. 

The ideia it's not to go deep on the service and k8s implementation details, but to provide a general overview on services, deployments and tests work on the suggested monorepo implementation.
