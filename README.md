# Chinachu4J
Wrappter of Chinachu API

## Download
###Gradle
```
repositories {
  jcenter()
}

dependencies {
  compile 'net.mizofumi:chinachu4j:0.1.0'
}
```

## How to Use
```
Chinachu4J chinachu4J = new Chinachu4J("http://hogefuga:10772/api/",new BasicAuthenticator(
  "username",
  "password"
));

Program[] programs = chinachu4J.getNowChannelSchedule();
```
