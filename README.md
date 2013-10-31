# TERASOLUNA Global Framework Blank Project

Blank project for web application using TERASOLUNA Global Framework (Spring MVC + Spring + JPA or MyBatis2)


## Getting Started

You can use maven archetype of TERASOLUNA Global Framework.

	$ mvn archetype:generate -DarchetypeCatalog=http://54.248.227.230/nexus/content/repositories/terasoluna-gfw-releases
	[INFO] Scanning for projects...
	[INFO]
	[INFO] ------------------------------------------------------------------------
	[INFO] Building Maven Stub Project (No POM) 1
	[INFO] ------------------------------------------------------------------------
	[INFO]
	[INFO] >>> maven-archetype-plugin:2.2:generate (default-cli) @ standalone-pom >>>
	[INFO]
	[INFO] <<< maven-archetype-plugin:2.2:generate (default-cli) @ standalone-pom <<<
	[INFO]
	[INFO] --- maven-archetype-plugin:2.2:generate (default-cli) @ standalone-pom ---
	[INFO] Generating project in Interactive mode
	[INFO] No archetype defined. Using maven-archetype-quickstart (org.apache.maven.archetypes:maven-archetype-quickstart:1.0)
	Choose archetype:
	1: http://54.248.227.230/nexus/content/repositories/terasoluna-gfw-releases -> org.terasoluna.gfw.blank:terasoluna-gfw-web-blank-archetype (Blank project using TERASOLUNA Global Framework)
	2: http://54.248.227.230/nexus/content/repositories/terasoluna-gfw-releases -> org.terasoluna.gfw.blank:terasoluna-gfw-web-blank-jpa-archetype (Blank project using TERASOLUNA Global Framework (JPA))
	3: http://54.248.227.230/nexus/content/repositories/terasoluna-gfw-releases -> org.terasoluna.gfw.blank:terasoluna-gfw-web-blank-mybatis2-archetype (Blank project using TERASOLUNA Global Framework (MyBatis2))
	Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): : 

Choose number

1. a template project without any db accsess configuration
2. a template project with MyBatis2 configuration
3. a template project with Spring Data JPA configuration 

**Note that 54.248.227.230 is temporary ip, and changed in future.**


## Download

If you don't want to use maven archetype, download manually.
[https://github.com/terasolunaorg/terasoluna-gfw-web-blank/releases](https://github.com/terasolunaorg/terasoluna-gfw-web-blank/releases)