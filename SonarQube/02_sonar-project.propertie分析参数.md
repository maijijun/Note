## 强制参数
### Server
sonar.host.url

### Project Configuration

sonar.projectKey

## 可选参数
### Project Identity
sonar.projectName
sonar.projectVersion

### Authentication
sonar.login
sonar.password

### Web Services

sonar.ws.timeout

### Project Configuration
sonar.projectDescription
sonar.links.homepage
sonar.links.ci
sonar.links.issue
sonar.links.scm
sonar.sources
sonar.tests
sonar.sourceEncoding
sonar.externalIssuesReportPaths
sonar.projectDate
sonar.projectBaseDir
sonar.working.directory
sonar.scm.provider
sonar.scm.forceReloadAll
sonar.scm.exclusions.disabled
sonar.scm.revision
sonar.buildString
sonar.analysis.[yourKey]
sonar.newCode.referenceBranch

### Duplications

sonar.cpd.${language}.minimumtokens
sonar.cpd.${language}.minimumLines

### Analysis Logging
sonar.log.level
sonar.verbose
sonar.scanner.metadataFilePath

### Quality Gate
sonar.qualitygate.wait
sonar.qualitygate.timeout

## 过期参数
sonar.links.scm_dev(since SQ 7.1)