# hello-java

A simple hello world Java app with some errors for testing with Coverity and Polaris

Build on CLI
- mvn clean package (pom.xml)

Build with CI
- ado-build.yml - normal build (Maven) on Azure DevOps
- ado-coverity.yml - Coverity (Maven) on Azure DevOps
- ado-polaris.yml - Polaris (Maven) on Azure DevOps
- Jenkinsfile.coverity - Coverity (Maven) on Jenkins
- Jenkinsfile.polaris - Polaris (Maven) on Jenkins
- polaris.yml - Polaris project configuration (Maven)
- .gitlab-ci.yml - GitLab CI pipeline (Maven)
