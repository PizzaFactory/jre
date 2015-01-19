JRE features for PizzaFactory
=============================

Settings before builds
----------------------

Add the mirror setting below to your settings.xml

```
  <mirrors>
    <mirror>
      <id>internal-repository</id>
      <name>Nexus on monami-ya.com</name>
      <url>http://builder.monami-ya.com:8080/nexus/content/groups/public</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
  </mirrors>
```

Of course you can resolve it by forking and adding ```<repositories>``` element into ```parent/pom.xml```

How to build
------------

Run maven on the top of our repository like:

```
mvn -f parent/pom.xml clean install
```

You may fail building with validate, compile, or other target.
(I think it is caused by limitations around Tycho.)

Question?
---------
Please create the ticket on our GitHub issues for your any question.
