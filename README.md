# Apache Maven (apache-maven)
Apache Maven is a software project management and comprehension tool based on the concept of a project object model (POM). It provides a uniform build system, dependency management, project lifecycle, and a comprehensive plugin ecosystem for Java projects. Maven 4 is the current major version with the Maven Daemon for faster builds.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-maven/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Build Tool, Dependency Management, Java, Maven, Project Management

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Maven Core
Maven provides a Java API for programmatic build execution, a Plugin API (Mojo) for extending build capabilities, a Repository API for artifact management via Maven Artifact Resolver, and the Wagon transport API for repository access. Maven 4 introduces improved APIs and the Maven Upgrade Tool for migration.

**Human URL:** [https://maven.apache.org/guides/index.html](https://maven.apache.org/guides/index.html)

#### Tags:

 - Build, Java, Plugins, Project Object Model

#### Properties

- [Documentation](https://maven.apache.org/guides/index.html)
- [GettingStarted](https://maven.apache.org/install.html)
- [APIReference](https://maven.apache.org/ref/current/)
- [Maven Central (Java)](https://central.sonatype.com/artifact/org.apache.maven/maven-core)
- [GitHubRepository](https://github.com/apache/maven)

### Maven Central Repository API
The Maven Central Repository (search.maven.org and central.sonatype.com) hosts millions of Java artifacts and provides a REST API and web interface for searching, browsing, and downloading dependencies. It is the default artifact repository for Maven builds.

**Human URL:** [https://central.sonatype.com/](https://central.sonatype.com/)

#### Tags:

 - Artifact Repository, Dependency Management, Package Registry

#### Properties

- [Documentation](https://central.sonatype.org/publish/)
- [Portal](https://central.sonatype.com/)
- [APIReference](https://central.sonatype.com/api-doc)

## Common Properties

- [Portal](https://maven.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/maven)
- [GitHubRepository](https://github.com/apache/maven-resolver)
- [GitHubRepository](https://github.com/apache/maven-mvnd)
- [GitHubRepository](https://github.com/apache/maven-surefire)
- [GitHubRepository](https://github.com/apache/maven-enforcer)
- [GitHubRepository](https://github.com/apache/maven-assembly-plugin)
- [Wiki](https://cwiki.apache.org/confluence/display/MAVEN)
- [IssueTracker](https://issues.apache.org/jira/projects/MNG/issues)
- [MailingList](https://maven.apache.org/mailing-lists.html)
- [Blog](https://maven.apache.org/news.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Project Object Model (POM) | XML-based project descriptor that defines dependencies, build configuration, plugins, and project metadata in a declarative format. |
| Dependency Management | Automatic resolution and downloading of project dependencies and transitive dependencies from Maven Central and other repositories. |
| Build Lifecycle | Standardized build lifecycle with phases including validate, compile, test, package, verify, install, and deploy. |
| Plugin Architecture | Extensible plugin system (Mojo API) with hundreds of official and third-party plugins for code generation, testing, packaging, and deployment. |
| Maven Daemon (mvnd) | Persistent daemon process that dramatically reduces build startup time by keeping the JVM and Maven warm between builds. |
| Maven Wrapper | Ensures consistent Maven version usage across a project team without requiring separate Maven installation. |
| Artifact Resolver | Maven Artifact Resolver library provides programmatic API for artifact resolution, download, and local repository management. |
| Multi-Module Projects | Support for building complex multi-module projects with inter-module dependency management and coordinated releases. |
| Maven 4 | Latest major version with improved APIs, better performance, consumer POM support, and the Maven Upgrade Tool for migration. |
| Central Repository Publishing | Streamlined artifact publishing to Maven Central via Sonatype's publishing portal with automated checks. |

## Use Cases

| Name | Description |
|------|-------------|
| Java Project Build Automation | Automate compilation, testing, packaging, and deployment of Java projects with standardized build lifecycles. |
| Dependency Management | Declare and automatically resolve project dependencies including transitive dependencies from Maven Central. |
| CI/CD Pipeline Integration | Integrate Maven builds into CI/CD pipelines with reproducible builds via the Maven Wrapper and build cache extension. |
| Multi-Module Enterprise Builds | Manage complex enterprise Java projects with dozens of interdependent modules and shared dependency management. |
| Artifact Publishing | Publish Java libraries and applications to Maven Central or private artifact repositories for team and public consumption. |
| Plugin Development | Develop custom Maven plugins using the Mojo API to extend build capabilities for specialized project needs. |

## Integrations

| Name | Description |
|------|-------------|
| IntelliJ IDEA | Native Maven project support with POM editing, dependency management, and Maven tool window. |
| Eclipse | Maven integration via the m2e plugin for POM-based project management within Eclipse IDE. |
| Jenkins | Jenkins Maven plugin for triggering and monitoring Maven builds in CI/CD pipelines. |
| GitHub Actions | Official GitHub Actions for caching Maven dependencies and running Maven builds in workflows. |
| Sonatype Nexus | Enterprise artifact repository manager fully compatible with Maven for hosting private artifact repositories. |
| JFrog Artifactory | Enterprise artifact repository with full Maven repository protocol support and build integration. |
| Apache Tomcat | Tomcat Maven Plugin enables deploying web applications to Apache Tomcat directly from Maven builds. |
| GraalVM | Maven plugins for building native images from Java applications using GraalVM Native Image. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
