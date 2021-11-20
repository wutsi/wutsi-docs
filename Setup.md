# Setup Dev Environment

## Github
- Generate a Github Personal Token for accessing packages from GibHub:
  - Goto https://github.com/settings/tokens
  - Click on Generate New Token
  - Give a value to your token
  - Select the permissions `read:packages`
  - Generate the token

- Set the following environment variables:
  - GITHUB_TOKEN = `your-token-value`
  - GITHUB_USER = `your-github-user-name`

## Maven
- Download and Install [Maven](https://maven.apache.org/download.cgi)
- Edit the file `~/.m2/settings.xml`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
                      http://maven.apache.org/xsd/settings-1.0.0.xsd">
    
  <servers>
    <server>
      <id>github</id>
      <username>wutsi</username>
      <password>${GITHUB_TOKEN}</password>
    </server>
  </servers>

</settings>
```

## Database Setup
- Download and Install [PostgeSQL](https://www.postgresql.org/download/)
- Create account with username/password: `postgres/postgres`
