## **Concept**

### _Location of context.xml and web.xml_

![Alt where](pic/01.jpg)

![Alt can be in the war](pic/02.jpg)

- If there is a context.xml under both war and conf, war will override the conf effect, and you can treat the context.xml under conf as a global setting.

### _What context.xml and web.xml for?_

![Alt context.xml for](pic/03.jpg)

![Alt web.xml for](pic/04.jpg)

## **Demo**

### _context.xml_

![Alt demo: context.xml](pic/05.jpg)

- I don't see jdbc related settings...

### _web.xml_

![Alt demo: view web.xml](pic/06.jpg)

**Session timout**

![Alt demo: session](pic/07.jpg)

**Servlet**

![Alt demo: servlet](pic/08.jpg)

**Welcome-file**

![Alt demo: welcome-file](pic/09.jpg)
