# EduStream Web Application

EduStream is a Java web application for online course management, including lectures, polls, comments, and role-based access control.

## Tech Stack

- Java (Spring Boot)
- JSP / Servlet web layer
- Gradle and Maven wrapper files are both present in this repository

## Project Structure

- `src/main/java` - Java source code (controllers, models, repositories, config, security)
- `src/main/resources` - application configuration and i18n message bundles
- `src/main/webapp` - JSP views, static assets, and web deployment descriptors
- `src/test/java` - test sources

## Current Repository State

Many core files in this repository are currently stored as Git LFS pointer files rather than full source content.  
If you see files starting with:

```text
version https://git-lfs.github.com/spec/v1
```

you need to restore full content from LFS.

## Restore Full Source From Git LFS

1. Install Git LFS:

```bash
git lfs install
```

2. Fetch and checkout LFS content:

```bash
git lfs pull
```

3. Verify that source files contain real code (not pointer text).

## Run (after LFS restoration)

Use one build tool path depending on your project setup.

### Maven

```bash
./mvnw spring-boot:run
```

### Gradle

```bash
./gradlew bootRun
```

## Notes

- `.DS_Store` and Gradle local cache files are safe to remove and can be regenerated.
- Keep build and dependency lock files under version control as required by your workflow.
