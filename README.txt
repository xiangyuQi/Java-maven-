1.创建java项目 mvn archetype:generate -DgroupId=com.hand  -DartifactId=javaTest  -DarchetypeArtifactId=maven-archetype-quickstart  -DinteractiveMode=false -DarchetypeCatalog=local
2.编译 cd javaTest
       mvn compile
3.执行  mvn exec:java -Dexec.mainClass="com.hand.App" -Dexec.args="arg0 arg1 arg2"
<properties>  
	        <!-- 文件拷贝时的编码 -->  
	        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>  
	       <project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>  
	        <!-- 编译时的编码 -->  
	        <maven.compiler.encoding>UTF-8</maven.compiler.encoding>  
    </properties>  