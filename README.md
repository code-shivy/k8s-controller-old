# k8s-controller

In Kubernetes, a controller is a core concept responsible for managing and ensuring the desired state of your applications, services, and other resources within a cluster. Controllers work to maintain the system's state as specified by the user or application, and they take automated actions to reconcile the actual state with the desired state.


Kubernetes provides several built-in controllers that handle various aspects of the cluster's resources and services. Here are a few examples of Kubernetes controllers:

**ReplicaSet Controller:** Ensures that the specified number of pod replicas is running at all times. It scales pods up or down based on defined rules to maintain the desired replica count.

**Deployment Controller:** Manages the lifecycle of applications by allowing you to define rolling updates, scaling changes, and rollbacks. It uses ReplicaSets to achieve these updates seamlessly.

**StatefulSet Controller:** Used for stateful applications that require stable network identifiers and persistent storage. It ensures ordered and unique deployment of pods and handles scaling and updates.

**DaemonSet Controller:** Ensures that a specific pod runs on each node in the cluster. It's commonly used for monitoring, logging, and other node-specific tasks.

**Job Controller:** Manages batch tasks that run to completion, ensuring that they are completed successfully before being marked as complete.

**CronJob Controller:** Creates jobs on a scheduled basis, similar to a cron job in Unix-like systems. This is useful for running periodic tasks.

**Namespace Controller:** Manages namespaces, which are virtual clusters within the physical Kubernetes cluster. It ensures that namespaces are created, modified, or deleted as specified.

**Service Controller:** Ensures the availability and discoverability of services within the cluster. It manages the creation and deletion of virtual IPs and DNS entries for services.
