# DataQuery-Repository

## ** Notice **
- This Project is forked from [trinodb/trino](https://github.com/trinodb/trino) and customized for [**NCP Data Query Service**](https://www.ncloud.com/product/analytics/dataQuery).
- Only client-related code(`/clients/**`) is customized.

---

## Usage
- Add a repository in your build configuration
- Import a dependency in your build configuration

### for maven
`pom.xml`
```
<repository>
  <id>ncp-dataquery-release</id>
  <url>https://raw.githubusercontent.com/NaverCloudPlatform/DataQuery-Repository/main/releases/</url>
</repository>
```
```
<dependency>
  <groupId>com.ncp.dataquery</groupId>
  <artifactId>dataquery-jdbc</artifactId>
  <version>101-437</version>
</dependency>
```

### for gradle
`build.gradle`
```
maven { url "https://raw.githubusercontent.com/NaverCloudPlatform/DataQuery-Repository/main/releases/" }
```
```
implementation 'com.ncp.dataquery:dataquery-jdbc:101-437'
```

## More Information
- [NAVER CLOUD PLATFORM > Data Query](https://www.ncloud.com/product/analytics/dataQuery)
- [User Guide](https://guide.ncloud-docs.com/docs/ko/dataquery-overview)

## Release Note
| version | date | note |
| --- | --- | --- |
| 101-437 | 2024.08.16 | First Release |
