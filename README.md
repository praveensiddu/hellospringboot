# hellospringboot
My first experiment with spring boot
Objective
A webapplication which uses 
* ldap authentication  
* UI 
  * Built in angular or jquery
  * display a table
  * CURD entries in the table
* RestController
* JpaRepository using H2 database
* Containerize using jib( https://medium.com/javarevisited/containerizing-springboot-application-with-jib-716daa3e0850)
* Run in Kubernetes

# Prerequisites
* windows host with sts
* https://medium.com/javarevisited/containerizing-springboot-application-with-jib-716daa3e0850

Using springboot features
@RestController
@JpaRepository extends PagingAndSortingResository which extends CrudRepository

