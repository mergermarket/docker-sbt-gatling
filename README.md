# Environment where you can run SBT Gatling tests

### How to use
Example dockerfile: 

```
FROM mergermarket:sbt-gatling

ADD ./project ./project
ADD ./src ./src
ADD ./build.sbt .

CMD echo 'DONE!'
```

Example: https://github.com/mergermarket/parr-homepage-subscriber/tree/master/test/performance
