**Simple Sucumber Project For Selenium Grid**
-


- **Local Run**
<br>
In order to run this project locally and generate HTML reports, use this maven goal verify. 
```
mvn verify
```
- HTML reports should be generated under target/cucumber-html-reports

**Jenkins Setup**
-
<br>
- Created one jenkinsfile in project level you can find in. There are some configure in that.
- In order to run.

```
mvn test
````

**Tags**
-
<br>
- You can pass a custom tag using terminal. Available tags are @smoke, @regression.

- In order to use 

```
mvn test -Dcucumber.filter.tags="@smoke"
```


**Browser**
-
- You can pass change using command line argument BROWSER
- In order to use
```
mvn test -DBROWSER=firefox
```

