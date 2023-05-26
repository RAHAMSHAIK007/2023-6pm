NOTES:

maven : build tool
org: Apache software foundation
main file: POM.XML 
pom contains: Infromation about project
used: java projects 
dependency: java-1.8.0-openjdk 
home path: .m2 
release: 2004
programming: java
automatin project management: create code -- > creating war file

java code -- > add : dependencies -- > build tool -- > maven

jar : java archive  : backend 

.java -- > compile -- > .class 
(normal)                 (executable file)

10 .class -- > pack -- > jar file -- > backend

war	: Web Archive -- > frontend + backend
hmtl css js + java  -- > package of our application (tomcat server)

ear	: Enterprise archive -- > war + jar

Build tools: 
C, C ++  : make file
.Net     : Visual studio 
Java     : Ant, Maven, Gradle
Python		: gradel


plugin: a small software with automates manual work.
Goal : a command used to perform the tasks.

MAVEN SETUP:
STEP-1: Get a repo (dlcdn.apache.org)
wget https://dlcdn.apache.org/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.tar.gz

STEP-2: UNTAR THE REPO
tar -zxvf apache-maven-3.6.3-bin.tar.gz
cd apache-maven-3.6.3

STEP-3: INSTALLING JAVA AND MAVEN
yum install java-1.8.0-openjdk -y
yum install maven -y

STEP-4: SETUP THE PROJECT STRUCTURE
mvn archetype:generate


groupid: swiggy
artifactId: raham
version: 
package: 

cd raham

STE-5: PERFORMING MAVEN LIFECYCLE
yum install tree -y

cat src/main/java/swiggy/App.java
cat src/test/java/swiggy/AppTest.java


mvn compile		: to compile the soure code (.java -- > .class)
mvn test			: to test the source code (AppTest.java -- >  AppTest.class)
mvn package		: to create a jar file 
mvn install		: to copy the jar file to .m2 folder
mvn deploy		: to generate war file (no ui files)
mvn clean 		: to remove the target folder


NOTE: goals will work where the pom.xml file is present.

HISTORY:
  1  ll
    2  wget https://dlcdn.apache.org/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.tar.gz
    3  tar -zxvf apache-maven-3.6.3-bin.tar.gz
    4  cd apache-maven-3.6.3/
    5  yum install java-1.8.0-openjdk -y
    6  java -version
    7  yum install maven -y
    8  mvn --version
    9  maven --version
   10  mvn archetype:generate
   11  ll
   12  cd raham
   13  ll
   14  yum install tree -y
   15  tree
   16  cat src/main/java/swiggy/App.java
   17  cat src/test/java/swiggy/AppTest.java
   18  mvn compile
   19  ll
   20  tree
   21  mvn test
   22  tree
   23  mvn package
   24  tree
   25  mvn install
   26  pwd
   27  cd /root/.m2/repository/swiggy/raham/1.0-SNAPSHOT/
   28  ll
   29  pwd
   30  cd -
   31  mvn deploy
   32  ll
   33  mvn clean
   34  ll
   35  mvn compile
   36  tree
   37  mvn test
   38  tree
   39  mvn package
   40  mvn install
   41  mvn clean
   42  ll
   43  mvn install
   44  ll
   45  cat pom.xml
   46  ll
   47  cd
   48  mvn clean
   49  ll
   50  cd -
   51  mvn clean
   52  history
