# OpenShift Lab

This lab is inspired in [Google's Kubernetes lab](https://bit.ly/k8s-lab) by [Ray Tsang](https://twitter.com/saturnism).
We are using an infrastructure specially deployed for Red Hat Japan, so the instructions are tied to this environment. However, if you wish to try a similar version of this lab on your own environment, you can use [Red Hat's CDK](https://developers.redhat.com/products/cdk/overview/) - Container Development Kit, and the instructions provided [here](https://bit.ly/kubernetes-lab).

Furthermore, the microservices use: [WildFly Swarm](http://wildfly-swarm.io/) - A Java [microprofile](http://microprofile.io/) server, and [Vert.x](http://vertx.io/) - A a tool-kit for building reactive applications on the JVM.

   - [Lab Sources](lab/)
   - [Frontend source code](frontend/)
   - [Helloworld Microservice - implemented using Vert.x](helloworld-service/)
   - [Guestbook Microservice - implemented using WildFly Swarm](guestbook-service/)
   - [Kubernetes/OpenShift files](openshift/)

The latest HTML version of this Lab is available [here](http://bit.ly/workshop-openshift-rbc)
