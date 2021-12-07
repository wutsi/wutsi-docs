# Setup Dev Environment
## Java
- Install Java 11.

## Github
- Generate a Github Personal Token for accessing packages from GibHub:
  - Goto https://github.com/settings/tokens
  - Click on Generate New Token
    - Give a name to your token (Ex: 'Wutsi Token`)
    - Select the expiry
    - Select the permissions `write:packages` and `read:packages`
    - Click the button `Generate Token` to create the token
  - Copy the Token in a safe place!

- Add into your shell `rc` file (`.bashrc` or `.zshrc` etc.) the github authentication information
```shell
export GITHUB_USER = <your-github-user-name>
export GITHUB_TOKEN = <your-token-value>
```

## Maven
- Download and Install [Maven](https://maven.apache.org/download.cgi)
- Edit the file `~/.m2/settings.xml`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"  
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"  
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
          http://maven.apache.org/xsd/settings-1.0.0.xsd"
>
  <activeProfiles>
    <activeProfile>github</activeProfile>
  </activeProfiles>

  <profiles>
    <profile>
      <id>github</id>
      <repositories>
        <repository>
          <id>central</id>
          <url>https://repo1.maven.org/maven2</url>
        </repository>
        <repository>
          <id>github</id>
          <url>https://maven.pkg.github.com/wutsi/*</url>
          <snapshots>
            <enabled>true</enabled>
          </snapshots>
        </repository>
      </repositories>
    </profile>
  </profiles>
  
  <servers>
    <server>
      <id>github</id>
      <username>${env.GITUB_USER}</username>
      <password>${env.GITHUB_TOKEN}</password>
    </server>
  </servers>
</settings>
```

## IDE
- Install IntelliJ

## Database (Required for backend service)
- Download and Install [PostgeSQL](https://www.postgresql.org/download/)
- Create account with username/password: `postgres/postgres`

## Swagger-CLI (Required for wutsi-openapi)
- Install `swagger-cli` for generating code from Open-API
```
npm install -g @apidevtools/swagger-cli
```