1. [Kubernetes Design Principles: Understand the Why - Saad Ali, Google](https://www.youtube.com/watch?v=ZuIQurh_kDk)

Notes:
* declarative model
* No single point of failure - even if the master node fails application still be served
* Extensioble - i.e. custom scheduler, custom API objects using CRDs
* More portable - i.e. storage - pv, pvc - move across different environments
* Even if only one node is alive out of all the nodes, application will still run without any downtime
