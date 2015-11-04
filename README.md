# maven_project_example
To avoid running mvn archetype:generate and modify pom.xml and source files (afer upgrade junit version) over and over again. I create this maven example and will update plugins and dependencies as needed.

What I did here:
1, mvn archetype:generate -DgroupId=com.ericzh -DartifactId=example -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
2, upgrade junit dependency
3, add compiler plugin
4, add log4j dependency
5, add log4j.properties
