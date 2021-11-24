# c-helloworld-minikube
A simplest possible, remotely debugged c program for a docker container deployed inside minikube.

## Notes:
* It is not possible to reliably hardcode an ip address in `launch.json` file (this address is dynamically assigned to the service by minikube).
* Visual studio code launch and tasks configurations for remote debugging are intentionally included in this repository.