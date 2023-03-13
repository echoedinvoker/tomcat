## **logging.properties**

> The general logs are set in the logging.properties file.

![Alt loggin.properties](pic/01.jpg)

![Alt its contents](pic/02.jpg)

## **check /logs**

![Alt check logs files](pic/03.jpg)

- Except for the logs files marked in the figure, the names of other logs are set according to logging.properties.

## **catalina.sh**

> catalina.out is set in catalina.sh instead of logging.properties.

![Alt catalina.sh](pic/04.jpg)

![Alt find catalina_out](pic/05.jpg)

![Alt find true logic](pic/06.jpg)

## **catalina.out**

> catalina.out is a record of tomcat launch logs, we go in and look at its contents.

![Alt vim catalina.out](pic/07.jpg)

![Alt contents of it](pic/08.jpg)

- Because the default is to use append, so every time you launch tomcat, it will increase the catalina.out data, which will soon become extremely large.
