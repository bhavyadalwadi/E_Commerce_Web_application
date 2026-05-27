# E_Commerce_Web_application Graph Relationships

       ## Service Dependency Graph
       E_Commerce_Web_application
-> primary application under `easy_online_shop`
-> Database: MySQL
-> Queues/Events: not present
-> Deployment: No standardized deployment command is documented; treat this as a local/manual project.

       ## Runtime Dependency Graph
       E_Commerce_Web_application
-> Runtime: Java
-> Runtime: JSP
-> Runtime: Servlets
-> Runtime: Tomcat
-> Runtime: MySQL
-> Runtime: XAMPP

       ## Database Relationship Graph
       E_Commerce_Web_application
-> MySQL

       ## API Consumer / Provider Graph
       E_Commerce_Web_application
-> no formal API contract visible

       ## Queue Publisher / Consumer Graph
       E_Commerce_Web_application
-> no broker or queue layer visible

       ## Shared Package Dependency Graph
       E_Commerce_Web_application
-> no notable shared package layer beyond app-local dependencies

       ## Deployment Relationship Graph
       E_Commerce_Web_application
       - No standardized deployment command is documented; treat this as a local/manual project.

       ## Cross-Repo Relationship Graph
       E_Commerce_Web_application
-> no runtime dependency on sibling repos by default
