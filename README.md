<pre>
ilizin@ilizin:~/repos/api-rest-demo$ cat src/main/resources/banner.txt 
 ________________________________________
/ Hi,                                    \
\   I'm a springboot lover and you?      /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
ilizin@ilizin:~/repos/api-rest-demo$
</pre>

# 🍃springboot-demos

As part of my career path, I've been using *spring* and its extension *spring boot* plenty of time, and I'm amazed from how easy is to write
a complete application and how much code (and time) you can save compared with a traditional J2EE application.

This didactic repository's goal is to provide a set of projects to demonstrate the use of this powerful framework (aka spring boot) and covering
as much detail as possible of it.

The code is plenty of comments, pay attention to them, but their scope is purely didactic, so don't use them in a real project, they're just illustrating
to you the use of the framework.
```java
/** Doesn't have the Component annotation, instead we configure it as a Spring bean using the Bean annotation:
   {@link me.ilizin.spring_demo.springboot_demo.api_rest_demo.config.ApiRestDemoConfig} 
   The Bean annotation is useful when we take an existing third-party class and expose it as a Spring bean. */
public class SqrtEroneService implements SqrtService {

    @Override
    public int sqrt(int value) {
        //...
    }
}
```
 
This repository is the parent project for several spring boot demo projects which are summarized in the following table:

|         Repository          |                        Description                         |                                                    Github link                                                    |
|:---------------------------:|:----------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
|        api-rest-demo        | A demo project for setting up an api rest with Spring Boot |                [https://github.com/ilizin/api-rest-demo](https://github.com/ilizin/api-rest-demo)                 |
|   api-rest-with-jpa-demo    |    A CRUD API rest with Jpa/hibernate (h2) demo project    |       [https://github.com/ilizin/api-rest-with-jpa-demo](https://github.com/ilizin/api-rest-with-jpa-demo)        |
|       thymeleaf-demo        |     A web demo project with thymeleaf template engine      |               [https://github.com/ilizin/thymeleaf-demo](https://github.com/ilizin/thymeleaf-demo)                |
