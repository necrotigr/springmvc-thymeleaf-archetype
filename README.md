**Simple starter for projects**

Included:

 - Spring 4 MVC
 - Thymeleaf
 - Lombok
 - jetty maven plugin
 - Bootstrap 4
 
 View resolver set as default servlet
 
 To create a project:
 
 - go to archetype dir
 - mvn clean install 
 - go to new project folder
 - mvn archetype:generate -DarchetypeGroupId=nl.necrotigr.archetypes -DarchetypeArtifactId=spring-thymeleaf-archetype 
    -DarchetypeVersion=1.0 -DgroupId=<groupId> -DartifactId=<artidactId> -Dversion=<version>
    
 To run:
 mvn jetty:run