# Docker / Kubernetes / Microservice Workshop

## Prerequisites

* Java (JDK) 11 or 17 - https://adoptium.net/
* Docker - https://docs.docker.com/get-docker/
* Minikube - https://minikube.sigs.k8s.io/docs/start/

## The journey 

* [001 - Docker Workshop](docker/001-docker.adoc)
* [101 - Kubernetes Workshop - Containers](kubernetes/101-kubernetes.adoc)
* [102 - Kubernetes Workshop - Applications](kubernetes/102-deployment.adoc)
* [103 - Kubernetes Workshop - Observability and Resilience](kubernetes/103-observability.adoc)
* [201 - Microservice Workshop](microservices/201-microservices.adoc)

## Resources

### Quarkus 

* Quarkus guides: https://quarkus.io/guides
* _Supes_ Workshop: https://quarkus.io/quarkus-workshops/super-heroes/
* Books about Quarkus: https://quarkus.io/books/
* Understanding Quarkus: https://developers.redhat.com/books/understanding-quarkus
* Practising Quarkus: https://developers.redhat.com/books/practising-quarkus

### Devops Books

* The Phoenix Project: https://www.goodreads.com/book/show/17255186-the-phoenix-projec
* The DevOps Handbook: https://www.goodreads.com/book/show/26083308-the-devops-handbook
* Accelerate: https://www.goodreads.com/book/show/39080433-accelerate
* Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment Automation: https://www.goodreads.com/book/show/8686650-continuous-delivery

### Software and Distributed Systems:

* Release It: https://www.goodreads.com/book/show/1069827.Release_It_
* Distributed systems - Principles and Paradigms: https://www.goodreads.com/book/show/405614.Distributed_Systems
* Seminal Papers on distributed systems: https://github.com/papers-we-love/papers-we-love/tree/master/distributed_systems

  * Note on distributed computing: https://github.com/papers-we-love/papers-we-love/blob/master/distributed_systems/a-note-on-distributed-computing.pdf
  * Paxos Made Simple: https://github.com/papers-we-love/papers-we-love/blob/master/distributed_systems/paxos-made-simple.pdf
  * Paxos Made Moderately Complex: https://github.com/papers-we-love/papers-we-love/blob/master/distributed_systems/paxos-made-moderately-complex.pdf 
  
### Kubernetes

* Kubernetes - Up and Running: https://www.goodreads.com/book/show/26759355-kubernetes
* Kubernetes Patterns - https://www.goodreads.com/book/show/44144501-kubernetes-patterns
                 
  
### Tools

* Automation

    * Bash
    * JBang - https://github.com/jbangdev/jbang
    
* Performances

    * wrk2 - https://github.com/giltene/wrk2
    * Gatling - https://gatling.io/ (there is an open source version)
    * Siege - https://github.com/JoeDog/siege
    
* Tests

    * junit 5 - https://junit.org/junit5/docs/current/user-guide/
    * Wiremock (to test integration point resilience) - http://wiremock.org/docs/getting-started/
    * Selenium (Web UI Test) - https://www.selenium.dev/

* Kubernetes

    * Stern (get logs) - https://github.com/wercker/stern
    * kubectlx (better kubectl when dealing with multiple context) - https://github.com/ahmetb/kubectx
    
* Chaos Engineering

    * Chaos Monkey - https://github.com/Netflix/chaosmonkey
    * Pumba - https://github.com/alexei-led/pumba             