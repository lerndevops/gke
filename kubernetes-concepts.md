## Pods
* Pods are the smallest deployable units of computing that you can create and manage in Kubernetes
* Pod is an abstraction that manages a single/group of containers 
* we can not create two containers from image in a pod 
* pod gets an ip / network and is shared by all containers inside it 
* [know more & Examples](https://github.com/lerndevops/educka/tree/master/pods)


## CONTROLLERS
* In Kubernetes, controllers are control loops that watch the state of your cluster, then make or request changes where needed. Each controller tries to move the current cluster state closer to the desired state.
* simply, controller is an abstraction that manages a single / group of pods 
* [know more & Examples](https://github.com/lerndevops/educka/tree/master/controllers)

## SERVICES
* An abstract way to expose an application running on a set/group of Pods as a network service.
* simply, helps us to access application running single/group of pods
* [know more & Examples](https://github.com/lerndevops/educka/tree/master/services-networks)
