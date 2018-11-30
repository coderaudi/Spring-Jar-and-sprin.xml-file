# Spring-Jar-and-sprin.xml-file
Here, we are going to create a simple application of spring framework using eclipse IDE. Let's see the simple steps to create the spring application in Eclipse IDE.

create the java project
add spring jar files
create the class
create the xml file to provide the values
create the test class


the jar files are spring.xml file is provided 


spring.xml --> 

<beans xmlns="http://www.springframework.org/schema/beans"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://www.springframework.org/schema/beans
           http://www.springframework.org/schema/beans/spring-beans-3.0.xsd">
           
           
           <bean name="pojoClassName" class="org.audi.autowiringsample.yourpackage" autowire="byName">
               <property name="name" value="userONe"></property>
               <property name="age" value="25"></property>
           </bean>
           
           <bean name="car" class="org.audi.autowiringsample.Car">
               <property name="brand" value="my_audi"></property>
           </bean>
           
     </beans>
