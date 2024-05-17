# spring_boot_init
Example of a Java Project initialized in Spring Boot

## Configuration

### Database

The project requires a database (PostgreSQL or MySQL) in order to build the application using Maven.  You must set up a database with a username and password for use in the configuration.  The DB URL will be used in the configuration also.

### Local

Local configuration is done through a properties file to contain the secret properties in separately from the general application properties.

To set up a local environment, create a file “***secrets.yml***” under the java/resources folder. Add the following parameters and the values you want them to be:

```yaml
spring:
  datasource:
    url: [replace_with_db_url]
    username: [replace_with_db_username]
    password: [replace_with_dp_password]
```

