Todays Task: Namespaces, Deployments and Services

Create a new namespace k8s-challenge-2-a and assure all following operations (unless different namespace is mentioned) are done in this namespace.

Create a deployment named nginx-deployment of three pods running image nginx with a memory limit of 64MB.

Expose this deployment under the name nginx-service inside our cluster on port 4444, so point the service port 4444 to pod ports 80.

Spin up a temporary pod named pod1 of image cosmintitei/bash-curl, ssh into it and request the default nginx page on port 4444 of our nginx-service using curl.

Spin up a temporary pod named pod2 of image cosmintitei/bash-curl in namespace k8s-challenge-2-b, ssh into it and request the default nginx page on port 4444 of our nginx-service in namespace k8s-challenge-2-a using curl.
