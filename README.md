# Keycloak Connector

* Using additions from [inalogy/connector-keycloak](https://github.com/inalogy/connector-keycloak) to associate client roles with groups
* Updated keycloak-admin-client to v. 26.0.7

## Description

[MidPoint](https://github.com/Evolveum/midpoint) Connector for [Keycloak](https://keycloak.org).

## Capabilities and Features

* Schema: YES
* Provisioning: YES
* Live Synchronization: No
* Password: YES
* Activation: YES
* Script execution: No 

This connector contains support for Keycloak user and group.

## Build

Install JDK 11+ and [maven3](https://maven.apache.org/download.cgi) then build:

```
mvn install
```

After successful the build, you can find `connector-keycloak-*.jar` in `target` directory.

## License

Licensed under the [Apache License 2.0](/LICENSE).
