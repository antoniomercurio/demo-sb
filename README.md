# Applicazione dimostrativa in Spring Boot

Questa applicazione può essere assemblata ed eseguita localmente con il seguente comando:

```
$ mvn clean spring-boot:run
```

Per il deploy su OpenShift con Source2Image:

```
$ oc new-app redhat-openjdk18-openshift:1.1~https://github.com/zedr/demo-sb.git
```
