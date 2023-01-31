1) payload String from jwt token is fetched.
2) The encoded payload is Decoded.
3) The decoded payload String is then mapped to a Java Object using Jackson library's 
   ObjectMapper.
4) By using JAVA object we are displaying the exp data in payload or use the data for the functionalities.
5) The exp data is comapared to the current Time and showing the desired Output.

Dependencies:

Following dependencies is added to the pom.xml File

 <dependency>  
    <groupId>com.fasterxml.jackson.core</groupId>  
    <artifactId>jackson-core</artifactId>  
    <version>2.14.1</version>  
</dependency>  
<dependency>  
    <groupId>com.fasterxml.jackson.core</groupId>  
    <artifactId>jackson-databind</artifactId>  
    <version>2.14.1</version>  
</dependency>  
<dependency>  
    <groupId>com.fasterxml.jackson.core</groupId>  
    <artifactId>jackson-annotations</artifactId>  
    <version>2.14.1</version>  
</dependency>