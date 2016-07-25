1.创建java项目 mvn archetype:generate -DgroupId=com.hand  -DartifactId=javaTest  -DarchetypeArtifactId=maven-archetype-quickstart  -DinteractiveMode=false -DarchetypeCatalog=local
2.编译 cd javaTest
       mvn compile
3.执行  mvn exec:java -Dexec.mainClass="com.hand.App" -Dexec.args="arg0 arg1 arg2"