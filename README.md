# maven-repository

Maven central repository

Profile settings:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
  <profiles>
    <profile>
	  <id>aliceinnets</id>
	  <repositories>
        <repository>
          <id>central</id>
          <name>master</name>
          <url>https://raw.github.com/aliceinnets/maven-repository/master/</url>
          <layout>default</layout>
          <snapshotPolicy>always</snapshotPolicy>
        </repository>
      </repositories>
    </profile>
  </profiles>
  <activeProfiles>
    <activeProfile>aliceinnets</activeProfile>
  </activeProfiles>
</settings>
```

