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

The goal of this didactic repo is to provide a set of projects to demonstrate the use of this powerful framework covering
as much detail as possible.

The code is plenty of comments, pay attention to them, but don't use them in a real project, they're just illustrating
to you the use of the framework.
```
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

The repo is the parent project for several springboot demo projects organized by topic:

|         Repository          |                        Description                         |                                                  Github link                                                   |
|:---------------------------:|:----------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|
|        api-rest-demo        | A demo project for setting up an api rest with Spring Boot |               [https://github.com/ilizin/api-rest-demo](https://github.com/ilizin/api-rest-demo)               |
|         jpa-h2-demo         |           A CRUD Jpa/hibernate (h2) demo project           |                 [https://github.com/ilizin/jpa-h2-demo](https://github.com/ilizin/jpa-h2-demo)                 |
|   api-rest-with-jpa-demo    |    A CRUD API rest with Jpa/hibernate (h2) demo project    |      [https://github.com/ilizin/api-rest-with-jpa-demo](https://github.com/ilizin/api-rest-with-jpa-demo)      |
| api-rest-with-security-demo |       An API rest demo project with spring security        | [https://github.com/ilizin/api-rest-with-security-demo](https://github.com/ilizin/api-rest-with-security-demo) |
|       thymeleaf-demo        |     A web demo project with thymeleaf template engine      |            [https://github.com/ilizin/thymeleaf-demo](https://github.com/ilizin/thymeleaf-demo)                |
