## **Basic Concept**

### _Java & Other_

![Alt concept: basic](pic/11.jpg)

### _Can I use root?_

![Alt concept: root](pic/12.jpg)

- Create Tomcat with root, if hacked it means all privileges are taken away.
  - So we create a new user with limit privileges to prevent it.

### _Commands_

![Alt concept: create user](pic/13.jpg)

![Alt concept: tar](pic/14.jpg)

## **Actual Work Flow**

### _Download binary files_

**OpenJDK**

> The lecturer uses 14, I use the latest version 19.

![Alt dl openjdk](pic/01.jpg)

![Alt dl openjdk](pic/02.jpg)

**Tomcat**

> The latest version is 10, I follow the lecture video using 9.

![Alt dl tomcat](pic/03.jpg)

![Alt dl tomcat](pic/04.jpg)

### _Create New User & Disk Slice_

![Alt create user and disk slice](pic/05.jpg)

### _Tar binary files_

![Alt tar tomcat](pic/06.jpg)

![Alt tar openjdk](pic/07.jpg)

### _set JAVA_HOME & launch Tomcat_

![Alt set JAVA_HOME and launch tomcat](pic/08.jpg)

![Alt verify tomcat on browser](pic/09.jpg)

### _shutdown Tomcat_

![Alt shupdown tomcat](pic/10.jpg)
