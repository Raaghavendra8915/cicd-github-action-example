# cicd-github-action-example
[![Quality Gate](https://sonarcloud.io/api/project_badges/quality_gate?project=judebantony_cicd-github-action-example&branch=main)](https://sonarcloud.io/project/overview?id=judebantony_cicd-github-action-example)
[![SonarCloud Coverage](https://sonarcloud.io/api/project_badges/measure?project=judebantony_cicd-github-action-example&metric=coverage)](https://sonarcloud.io/component_measures/metric/coverage/list?id=judebantony_cicd-github-action-example)
[![SonarCloud Bugs](https://sonarcloud.io/api/project_badges/measure?project=judebantony_cicd-github-action-example&metric=bugs)](https://sonarcloud.io/component_measures/metric/reliability_rating/list?id=judebantony_cicd-github-action-example)
[![SonarCloud Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=judebantony_cicd-github-action-example&metric=vulnerabilities)](https://sonarcloud.io/component_measures/metric/security_rating/list?id=judebantony_cicd-github-action-example)
[![SonarCloud Code Smell](https://sonarcloud.io/api/project_badges/measure?project=judebantony_cicd-github-action-example&metric=code_smells)](https://sonarcloud.io/component_measures/metric/code_smell/list?id=judebantony_cicd-github-action-example)

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjudebantony%2Fcicd-github-action-example.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjudebantony%2Fcicd-github-action-example?ref=badge_shield)

[![Main Branch](https://github.com/judebantony/cicd-github-action-example/actions/workflows/test.yml/badge.svg)](https://github.com/judebantony/cicd-github-action-example/actions/workflows/test.yml)

[![codecov](https://codecov.io/gh/judebantony/cicd-github-action-example/branch/main/graph/badge.svg?token=E3O3NABP1H)](https://codecov.io/gh/judebantony/cicd-github-action-example)


## CICD - SecDevOps using GitHub Action 

SecDevOps automatically bakes in security at every phase of the software development lifecycle, enabling development of secure software at the speed of Agile and DevOps. It integrates application and infrastructure security seamlessly into Agile and DevOps processes and tools. It addresses security issues as they emerge, when they're easier, faster, and less expensive to fix and also makes application and infrastructure security a shared responsibility of development, security, and IT operations teams.

This is a sample project to demonstrate the E2E Github Action release workflow with all Security Controls Gates and integrated with different Cloud SaaS CI/CD tools chain offering.

![releaseworkflow](./doc/releaseworkflow.png)	

##### Tools used are listed below

1. Requirements 
    * JIRA <br />
	  Used atlassian Jira cloud offering to capture the requirements.<br />
	    JIRA Project :: [https://judebantony.atlassian.net](https://judebantony.atlassian.net)<br />
	    Jira Github Integration [More Information](https://support.atlassian.com/jira-cloud-administration/docs/integrate-with-github/)<br />
2. Code
 Build a sample application using below frameworks.<br /> 
    * Spring Boot <br />
    * Java <br />
3. SCM
     * GitHub		
4. Build
     * Mavan - [More Information](https://maven.apache.org) <br/>
5. CI
     * Github Action - [More Information](https://github.com/features/actions) <br/>
6. Code Quality
    * SonarQube [More Information](https://en.wikipedia.org/wiki/SonarQube)
	  [Dashboard Example](https://sonarcloud.io/organizations/judebantony/projects)	<br />
    * Codecov - [More Information](https://docs.codecov.com/docs)
	  [Dashboard Example](https://codecov.io/gh/judebantony/cicd-github-action-example/commit/4b9f0f601ab2feee0e409ede57283d5b99b9182d/build)	<br />
	  	
7. SAST (Static Analysis Security Testing)
     * CodeQL - [More information](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql)
     * HCL AppScan CodeSweep - [More Information](https://www.hcltechsw.com/appscan/codesweep)	
     * Codacy - [More Information](https://www.codacy.com/products/sonarqube-alternatives?utm_term=sonarqube&utm_campaign=SEA+-+Competitors&utm_source=adwords&utm_medium=ppc&hsa_acc=9882323101&hsa_cam=11598890837&hsa_grp=112569261106&hsa_ad=493336668133&hsa_src=g&hsa_tgt=kwd-57815990976&hsa_kw=sonarqube&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAiA4veMBhAMEiwAU4XRr_qVWrji3IRgivxyqqPc3QrEMVwBQmQoACBfPuCL5H0gE0nmn3n2LhoCcgkQAvD_BwE)
     * 42crunch - [More Information](https://platform.42crunch.com)
8. SCA (Software Composition Analysis)
     * Snyk - [More Information](https://snyk.io)
       [Dashboard Example](https://app.snyk.io/org/judebantony)<br />
     * Dependabot - [More Information](https://github.blog/2020-06-01-keep-all-your-packages-up-to-date-with-dependabot/)<br />
     * BlackDuck CoPilot - [More Information](https://www.synopsys.com/blogs/software-security/introducing-black-duck-copilot/) 
       [Dashboard Example](https://copilot.blackducksoftware.com/github/repos/judebantony/cicd-github-action-example/results)<br />
     * FOSSA [More Information](https://fossa.com)
       [Dashboard Example](https://app.fossa.com/projects/git%2Bgithub.com%2Fjudebantony%2Fcicd-github-action-example/refs/branch/main/0116ae3eef023ccfb56995ab2c4b10aaf5ffe1e1)
     * Shift Left [More Information](https://www.shiftleft.io/apps/shiftleft-java-demo/vulnerabilities?scan=1&branch=demo-branch-1638196402&severity=critical)<br />		
9. DAST (Dynamic Application Security Testing)
     * StackHawk - [More Information](https://www.stackhawk.com)<br />
     		[Dashboard Example](https://app.stackhawk.com/applications)
10. IaC Configs Scan
     * Snyk - [More Information](https://snyk.io)<br />
11. Secret Scan
     * Trufflehog - [More Information](https://github.com/trufflesecurity/truffleHog)<br />
     * GitGuardian - [More Information](https://docs.gitguardian.com/internal-repositories-monitoring/integrations/ci_cd_integrations/github_actions)
     [Dashboard Example](https://dashboard.gitguardian.com/workspace/190186/analytics)<br />
12. Maven Repository
     * Jfrog Artifactory - [More Information](https://jfrog.com/artifactory/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog%20artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=Cj0KCQiAhf2MBhDNARIsAKXU5GTNwwGiZx5Msn96nvS7v3kLKexhg50OTeKFkyYJSfFDkmnKLb0OH38aAiOTEALw_wcB)<br />
     * Github Package - [More Information](https://github.com/trufflesecurity/truffleHog)<br />
13. Helm Repository
     * Jfrog Artifactiory - [More Information](https://jfrog.com/artifactory/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog%20artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=Cj0KCQiAhf2MBhDNARIsAKXU5GTNwwGiZx5Msn96nvS7v3kLKexhg50OTeKFkyYJSfFDkmnKLb0OH38aAiOTEALw_wcB)<br /> 
14. Container Scan - Docker Image
      * Snyk - [More Information](https://snyk.io)<br />
      * JFrog Xray - [More Information](https://jfrog.com/artifactory/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog%20artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=Cj0KCQiAhf2MBhDNARIsAKXU5GTNwwGiZx5Msn96nvS7v3kLKexhg50OTeKFkyYJSfFDkmnKLb0OH38aAiOTEALw_wcB)<br />
15. Container Repository
     * JFrog Artifactory - [More Information](https://jfrog.com/artifactory/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog%20artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=Cj0KCQiAhf2MBhDNARIsAKXU5GTNwwGiZx5Msn96nvS7v3kLKexhg50OTeKFkyYJSfFDkmnKLb0OH38aAiOTEALw_wcB)<br />
     * Github Package - [More Information](https://github.com/features/packages)<br />
     * DockerHub - [More Information](https://hub.docker.com/r/judebantony/cigithubaction)<br />
16. Deploying to Azure - AKS
     * GitHub Action & K8S native 
17. Deploying to Azure - AKS
     * GitHub Action & Helm Chart - [More Information](https://helm.sh/docs/topics/charts/)<br />
18. Deploying to GCP - GKE 
     * GitHub Action & Harness - [More Information](https://harness.io)<br />
19. Provisioning AWS - EC2
     * Terraform - [More Information](https://www.terraform.io)<br />
20. Unit Testing
     * Junit - [More Information](https://junit.org/junit5/)<br />
     * Jacoco - [More Information](https://www.baeldung.com/sonarqube-jacoco-code-coverage)<br />
21. Functional Testing
     * Cucumber - [More Information](https://cucumber.io)<br />
     * Xray with Jira for Test Execution [More Information](https://docs.getxray.app/display/XRAY/About+Xray)<br />
     * Selenium - [More Information](https://www.selenium.dev)<br />
     * BrowserStack - [More Information](https://www.browserstack.com)<br />
     * LamdaTest - [More Information](https://www.lambdatest.com)<br />
22. Performance Testing
     * K6 - [More Information](https://k6.io)<br />
23. Create Release Tag

## Release Workflow
[Release workflow](https://github.com/judebantony/cicd-github-action-example/tree/main/.github/workflows/workflow.yml)
![workflow](./doc/workflow.png)	
[Workflow Run](https://github.com/judebantony/cicd-github-action-example/actions/runs/1500211427)	
## Jira and Github Integration
Linking your GitHub account to Jira gives your team the ability to see their branches, commit messages,build, test cases, test result(x-ray) and pull requests right in the context of the Jira tickets they’re working on. [More information](https://github.blog/2018-10-04-announcing-the-new-github-and-jira-software-cloud-integration/)

![jira](./doc/jira.png)

Commit and Build info is added to Jira

![jiragithub](./doc/jiragithub.png)
![githubbuild](./doc/githubbuild.png)

Cucumber feature test case using Gherkin is added to Jira

![githubtest](./doc/githubtest.png)

Test results

![githubtest](./doc/githubtestrun.png)
![githubresult](./doc/githubresult.png)

## Integration with GitHub Action 
Some the sample code for integrating different SaaS tool to CICD using GitHub Action. 

### 1) Maven - Build and Unit Test
Build the code is using [Maven](https://maven.apache.org) and run the [JUnit](https://junit.org/junit5/) unit test cases, upload the test coverage result to [Github Action](https://github.com/features/actions) . Please check [pom.xml](https://github.com/judebantony/cicd-github-action-example/tree/main/pom.xml). 

```yaml

  test:
    name: Build and Unit Test
    runs-on: ubuntu-latest
    
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Build
        run: mvn -B clean package -DskipTests
      - name: Run UnitTest and Verify 
        run: mvn -B verify -DexcludedGroups="Smoke | Staging | BrowserStack | LamdaTest"
      - name: Generate JaCoCo Badge
        id: jacoco
        uses: cicirello/jacoco-badge-generator@v2
      - name: Log code coverage percentage
        run: |
          echo "coverage = ${{ steps.jacoco.outputs.coverage }}"
          echo "branch coverage = ${{ steps.jacoco.outputs.branches }}"
      - name: Upload code coverage report
        uses: actions/upload-artifact@v2
        with:
          name: jacoco-report
          path: target/site/jacoco/
      - name: Adding Junit Report
        uses: ashley-taylor/junit-report-annotations-action@master
        if: always()
        with:
          access-token: ${{ secrets.GITHUB_TOKEN }}          
      - name: Publish Unit Test Results
        uses: EnricoMi/publish-unit-test-result-action/composite@v1
        with:
           files: target/surefire-reports/*.xml

```

![unittest](./doc/unittest.png)

### 2) Sonar Cloud - Code Quality
Inspect the code using [Sonar](https://www.sonarqube.org), enable the quality gate check and upload the result to its Cloud SaaS offering. 

```yaml
  sonar:
    name: Inspect - Using Sonar
    runs-on: ubuntu-latest
    needs: [test]
    
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 11
        uses: actions/setup-java@v1
        with:
          java-version: 11
      - name: Cache SonarCloud packages
        uses: actions/cache@v1
        with:
          path: ~/.sonar/cache
          key: ${{ runner.os }}-sonar
          restore-keys: ${{ runner.os }}-sonar
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Build and analyze
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SONAR_TOKEN: ${{ secrets.SONAR_TOKEN }}
        run: mvn -B verify -DexcludedGroups="Smoke | Staging | LamdaTest | BrowserStack" org.sonarsource.scanner.maven:sonar-maven-plugin:sonar -Dsonar.issuesReport.html.enable=true -Dsonar.projectKey=judebantony_cicd-github-action-example
      - name: SonarQube Quality Gate check
        uses: sonarsource/sonarqube-quality-gate-action@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SONAR_TOKEN: ${{ secrets.SONAR_TOKEN }}   
        timeout-minutes: 5     
        with:
          scanMetadataReportFile: target/sonar/report-task.txt     

```
![sonar](./doc/sonar.png)
Update the sonar quality gate information to github action build.
![qualitygate](./doc/qulitygate.png)

### 3) Codecov - Code Coverage
Upload the code coverage result to [Codecov](https://about.codecov.io) SaaS offering.

```yaml
  codecov:
    name: Inspect - Using Codecov
    runs-on: ubuntu-latest
    needs: [test]
    
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 8
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Build and analyze
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SONAR_TOKEN: ${{ secrets.SONAR_TOKEN }}
        run: mvn -B verify -DexcludedGroups="Smoke | Staging | LamdaTest | BrowserStack" cobertura:cobertura
      - name: Upload coverage to Codecov
        uses: codecov/codecov-action@v2
        with:
          token: ${{ secrets.CODECOV_TOKEN }} 
          flags: unittests 
          name: codecov-umbrella 
          fail_ci_if_error: true 
          verbose: true     

```
![codecov](./doc/codecov.png)


### 4) CodeQL - SAST
Use the native Github Action [CodeQL](https://codeql.github.com) for SAST scan and upload the result to [github security](https://github.com/security) tab

```yaml
  codeqlScan:
      name: SAST Scan using CodeQL
      runs-on: ubuntu-latest
      needs: [sonar, codecov]
      
      permissions:
        actions: read
        contents: read
        security-events: write
      strategy:
        fail-fast: false
        matrix:
          language: [ 'java' ]
          
      steps:
      - name: Checkout repository
        uses: actions/checkout@v2
        with:
           fetch-depth: 0
      - name: Initialize CodeQL
        uses: github/codeql-action/init@v1
        with:
          languages: ${{ matrix.language }}
      - name: Autobuild
        uses: github/codeql-action/autobuild@v1
      - name: Perform CodeQL Analysis
        uses: github/codeql-action/analyze@v1

```
![codeql](./doc/codeql.png)

### 5) AppScan CodeSweep - SAST 
Use the [AppScan CodeSweep](https://www.hcltechsw.com/appscan/codesweep) for SAST scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format


```yaml
  appScan:
    name: SAST Scan using AppScan CodeSweep
    runs-on: ubuntu-latest
    needs: [sonar, codecov]
    
    steps:
      - name: Checkout repository
        uses: actions/checkout@v2
        with:
           fetch-depth: 0
      - name: Run AppScan CodeSweep
        uses: HCL-TECH-SOFTWARE/appscan-codesweep-action@v1
        with:
            asoc_key: ${{secrets.ASOC_KEY}}
            asoc_secret: ${{secrets.ASOC_SECRET}}
        env: 
          GITHUB_TOKEN: ${{secrets.GITHUB_TOKEN}}
```

![appscan](./doc/appScan.png)

### 6) Codacy - SAST 
Use the [Codacy](https://www.codacy.com) for SAST scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format

```yaml
  codacyScan:
      name: SAST Scan using Codacy
      runs-on: ubuntu-latest
      needs: [sonar, codecov]
      
      steps:
        - uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Run Codacy Analysis CLI
          uses: codacy/codacy-analysis-cli-action@master
          with:
            output: codacy.sarif
            format: sarif
            gh-code-scanning-compat: true
            max-allowed-issues: 2147483647
        
        - name: Upload SARIF results file
          uses: github/codeql-action/upload-sarif@main
          with:
            sarif_file: codacy.sarif          
```

![codacy](./doc/codacy.png)

### 7) Snyk - SCA 
Use the [Snyk](https://snyk.io) for SCA scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format

```yaml
  snykScan:
      name: SCA Scan using Snyk
      runs-on: ubuntu-latest
      needs: [codeqlScan, codacyScan, appScan]
          
      steps:
      - uses: actions/checkout@v2
        with:
          fetch-depth: 0
      - name: Set up Maven
        run: mvn -N io.takari:maven:wrapper -Dmaven=3.8.2
      - name: Run Snyk to check for vulnerabilities
        continue-on-error: true      
        uses: snyk/actions/maven-3-jdk-11@master
        env:
           SNYK_TOKEN: ${{ secrets.SNYK_TOKEN }}
        with:
          args: --sarif-file-output=snyk.sarif
      - name: Upload result to GitHub Code Scanning
        uses: github/codeql-action/upload-sarif@v1
        with:
          sarif_file: snyk.sarif

```
![snky](./doc/snyk.png)

### 8) Dependabot - SCA 
Use the github native [Dependabot](https://docs.github.com/en/code-security/supply-chain-security/managing-vulnerabilities-in-your-projects-dependencies/configuring-dependabot-security-updates) for SCA scan and upload the result to [github security](https://github.com/security) tab 

```yaml dependabot.yml

version: 2
updates:
  - package-ecosystem: "maven"
    directory: "/" 
    schedule:
      interval: "daily"
  - package-ecosystem: "docker"
    directory: "/"
    schedule:
      interval: "weekly"

```
![dependabot](./doc/dependabot.png)

### 9) BlackDuck CoPilot - SCA 
Use the [BlackDuck](https://www.blackducksoftware.com) for SCA scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format

```yaml 

  blackduck:
      name: SCA Scan using BlackDuck
      runs-on: ubuntu-latest
      needs: [codeqlScan, codacyScan, appScan] 

      steps:
        - name: Check out the code
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Set up JDK
          uses: actions/setup-java@v1
          with:
            java-version: 1.8
        - name: Set up Maven
          run: mvn -N io.takari:maven:wrapper -Dmaven=3.8.2
        - name: Build with Maven
          run: |
            mvn install -DskipTests=true -Dmaven.javadoc.skip=true -B -V
            mvn test -B
        - name: Upload to CoPilot
          run: bash <(curl -s https://copilot.blackducksoftware.com/ci/githubactions/scripts/upload)


```
![blackduck](./doc/blackduck.png)

### 10) FOSSA - SCA 
Use the [FOSSA](https://fossa.com/variant/homepage) for SCA scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format

```yaml 

  fossaScan:
      name: SCA Scan using FOSSA
      runs-on: ubuntu-latest
      needs: [codeqlScan, codacyScan, appScan]  
      
      steps:
        - name: Check out the code
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Run FOSSA Scan
          uses: fossas/fossa-action@v1
          with:
            api-key: ${{secrets.FOSSA_APIKEY}}


```

![fossa](./doc/fossa.png)

### 11) ShiftLeft - SCA & SAST
Use the [ShiftLeft](https://www.shiftleft.io) for SCA & SAST scan and upload the result to [github security](https://github.com/security) tab using sairf [OWASP](https://owasp.org/www-community/Source_Code_Analysis_Tools) format

```yaml 

   shitLeftScan:
      name: SAST and SCA Scan using ShiftLeft
      runs-on: ubuntu-latest
      needs: [codeqlScan, codacyScan, appScan, rest-api-static-security-testing]
      steps:
      - uses: actions/checkout@v2
      - name: Perform Scan
        uses: ShiftLeftSecurity/scan-action@39af9e54bc599c8077e710291d790175c9231f64
        env:
          WORKSPACE: ""
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SCAN_AUTO_BUILD: true
        with:
          output: reports
      - name: Upload report
        uses: github/codeql-action/upload-sarif@v1
        with:
          sarif_file: reports


```

![shiftleft](./doc/shiftleft.png)

### 12) Snyk - Infrastructure as Code Configs Scan

Use [Snyk](https://snyk.io) to secure the Infrastructure as Code config files.

```yaml 

  snykIaSScan:
      name: SAST - Scan IaC Configs using Snyk
      runs-on: ubuntu-latest
      needs: [dependabot, snykScan, blackduck, fossaScan]
      
      steps:
        - name: Check out the code
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Run Snyk to check configuration files for security issues
          continue-on-error: true
          uses: snyk/actions/iac@master
          env:
            SNYK_TOKEN: ${{ secrets.SNYK_TOKEN }}
          with:
            file: |
              manifests/deployment.yml
              manifests/service.yml
        - name: Upload result to GitHub Code Scanning
          uses: github/codeql-action/upload-sarif@v1
          with:
            sarif_file: snyk.sarif


```
![snky](./doc/snyk.png)

### 13) Trufflehog - Secret Scan

Use [Trufflehog](https://trufflesecurity.com/trufflehog) to find any secret present in the source code. 
 
```yaml 

  trufflehogScan:
      name: Secret Scan Using Trufflehog
      runs-on: ubuntu-latest
      needs: [dependabot, snykScan, blackduck, fossaScan]
      
      steps:
        - name: Check out the code
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: trufflehog-actions-scan
          uses: edplato/trufflehog-actions-scan@master
          with:
            scanArguments: "--regex --entropy=False --max_depth=5" 


```
### 14) GitGuardian - Secret Scan

Use [GitGuardian](https://www.gitguardian.com) to find any secret present in the source code. 
 
```yaml 

 gitguardian:
      name: Secret Scan Using GitGuardian
      runs-on: ubuntu-latest
      needs: [dependabot, snykScan, blackduck, fossaScan, shitLeftScan]
      steps:
        - name: Checkout
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: GitGuardian scan
          uses: GitGuardian/ggshield-action@master
          with:
            args: -v --all-policies
          env:
            GITHUB_PUSH_BEFORE_SHA: ${{ github.event.before }}
            GITHUB_PUSH_BASE_SHA: ${{ github.event.base }}
            GITHUB_PULL_BASE_SHA: ${{ github.event.pull_request.base.sha }}
            GITHUB_DEFAULT_BRANCH: ${{ github.event.repository.default_branch }}
            GITGUARDIAN_API_KEY: ${{ secrets.GITGUARDIAN_API_KEY }}   


```
![gitguardian](./doc/gitguardian.png)

### 15) Snyk - Container Image Scan

Use [Snyk](https://snyk.io) to do container image scan. 

```yaml 

snykImageScan:
      name: Image Scan using Snyk
      runs-on: ubuntu-latest
      needs: [jfrogArtifactPush, gitHubPakageArtifactPush]  
          
      steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 8
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2
      - name: Package
        run: mvn -B clean package -DskipTests
      - name: Build a Docker image
        run: docker build -t your/image-to-test .
      - name: Run Snyk to check Docker image for vulnerabilities
        continue-on-error: true
        uses: snyk/actions/docker@master
        env:
          SNYK_TOKEN: ${{ secrets.SNYK_TOKEN }}
        with:
          image: your/image-to-test
          args: --sarif-file-output=snyk.sarif --file=Dockerfile
      - name: Upload result to GitHub Code Scanning
        uses: github/codeql-action/upload-sarif@v1
        with:
          sarif_file: snyk.sarif     


```
![snyk](./doc/snyk.png)

### 16) Jfrog Artifactory - Publish Artifact(jar)

Upload the Jar to [Jfrog Artifactory](https://jfrog.com/start-free/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog+artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=CjwKCAiAhreNBhAYEiwAFGGKPHkjlShpTBfbPyMgP1l5hGLeiezWo9xCn-3ncNVZCudxMzCdNUhMDhoCIDIQAvD_BwE).

```yaml 

 jfrogArtifactPush:
    name: Publish Artifact to Jfrog Artifactory
    runs-on: ubuntu-latest
    needs: [snykIaSScan, trufflehogScan] 
    
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 8
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2
      - name: Package
        run: mvn -B clean package -DskipTests
      - name: Publish JFrog Artifact
        uses: advancedcsg-open/action-jfrog-cli@master
        with:
          url: 'https://judebantony.jfrog.io/artifactory'
          credentials type: 'username'
          user: ${{ secrets.ARTIFACTORY_USER }}
          password: ${{ secrets.ARTIFACTORY_PASSWORD }}
          args: u "target/*.jar" "/libs-snapshot-repo-libs-release-local" --recursive=true  


```

![jfrogjar](./doc/jfrogjar.png)

### 17) GitHub Package - Publish Artifact(jar)

Upload the Jar to [Github Package](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages).

```yaml 

 gitHubPakageArtifactPush:
    name: Publish Artifact to GitHub Package
    runs-on: ubuntu-latest 
    needs: [snyIaSScan, trufflehogScan] 
    permissions: 
      contents: read
      packages: write 
      
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 8
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2
      - name: Publish package
        run: mvn --batch-mode deploy -DskipTests
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


```

![githubpackage](./doc/githubpackage.png)

### 18) JFrog Artifactory - Build Docker Image and Publish
Upload the Container Image to [Jfrog Artifactory](https://jfrog.com/start-free/?utm_source=google&utm_medium=cpc&utm_campaign=14808689020&utm_term=jfrog+artifactory&utm_network=g&cq_plac=&cq_plt=gp&gclid=CjwKCAiAhreNBhAYEiwAFGGKPHkjlShpTBfbPyMgP1l5hGLeiezWo9xCn-3ncNVZCudxMzCdNUhMDhoCIDIQAvD_BwE).

```yaml 

jfrogImageBuild:
    name: Build Docker Image and Publish to JFrog Artifactory
    runs-on: ubuntu-latest
    needs: [snykImageScan, jfrogXrayImageScan]

    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK 8
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2
      - name: Package
        run: mvn -B clean package -DskipTests
      - name: Set up QEMU️
        uses: docker/setup-qemu-action@v1
      - name: Set up Docker Buildx
        uses: docker/setup-buildx-action@v1
      - name: Login to JFrog  
        uses: docker/login-action@v1
        with:
          registry: 'https://judebantony.jfrog.io'
          username: ${{ secrets.ARTIFACTORY_USER }}
          password: ${{ secrets.ARTIFACTORY_PASSWORD }}        
      - name: Build and Publish Image 
        id: docker_build
        uses: docker/build-push-action@v2
        with:
          context: .
          push: true
          tags: judebantony.jfrog.io/default-docker-local/cigithubaction:latest


```

![jfrogimage](./doc/jfrogimage.png)

### 19) GitHub Package - Build Docker Image and Publish
Upload the Container Image to [Github Package](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages).

```yaml 

gitHubPakageImageBuild:
    name: Push Docker image to GitHub Package
    runs-on: ubuntu-latest
    needs: [snykImageScan, jfrogXrayImageScan]
    permissions:
      contents: read
      packages: write

    steps:
        - name: Check out the repo
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Set up JDK 8
          uses: actions/setup-java@v1
          with:
            java-version: 1.8
        - name: Cache Maven packages
          uses: actions/cache@v1
          with:
            path: ~/.m2
            key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
            restore-keys: ${{ runner.os }}-m2
        - name: Package
          run: mvn -B clean package -DskipTests
        - name: Set up QEMU️
          uses: docker/setup-qemu-action@v1
        - name: Set up Docker Buildx
          uses: docker/setup-buildx-action@v1

        - name: Log in to the Container registry
          uses: docker/login-action@f054a8b539a109f9f41c372932f1ae047eff08c9
          with:
            registry: https://ghcr.io
            username: ${{ github.actor }}
            password: ${{ secrets.GITHUB_TOKEN }}
  
        - name: Extract metadata (tags, labels) for Docker
          id: meta
          uses: docker/metadata-action@98669ae865ea3cffbcbaa878cf57c20bbf1c6c38
          with:
            images: ghcr.io/judebantony/cigithubaction:latest
  
        - name: ghcr.io
          uses: docker/build-push-action@ad44023a93711e3deb337508980b4b5e9bcdc5dc
          with:
            context: .
            push: true
            tags: ghcr.io/judebantony/cigithubaction:latest


```

![githubimage](./doc/githubimage.png)

### 20) Docker Hub - Build Docker Image and Publish
Upload the Container Image to [Docker hub](https://hub.docker.com).

```yaml 

 dockerHubImageBuild:
      name: Push Docker image to Docker Hub
      runs-on: ubuntu-latest
      needs: [snykImageScan, jfrogXrayImageScan]
      
      steps:
        - name: Check out the repo
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Set up JDK 8
          uses: actions/setup-java@v1
          with:
            java-version: 1.8
        - name: Cache Maven packages
          uses: actions/cache@v1
          with:
            path: ~/.m2
            key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
            restore-keys: ${{ runner.os }}-m2
        - name: Package
          run: mvn -B clean package -DskipTests
        - name: Log in to Docker Hub
          uses: docker/login-action@f054a8b539a109f9f41c372932f1ae047eff08c9
          with:
            username: ${{ secrets.DOCKER_USERNAME }}
            password: ${{ secrets.DOCKER_PASSWORD }}
        
        - name: Extract metadata (tags, labels) for Docker
          id: meta
          uses: docker/metadata-action@98669ae865ea3cffbcbaa878cf57c20bbf1c6c38
          with:
            images: docker.io/judebantony/cigithubaction
        
        - name: Build and push Docker image
          uses: docker/build-push-action@ad44023a93711e3deb337508980b4b5e9bcdc5dc
          with:
            context: .
            push: true
            tags: ${{ steps.meta.outputs.tags }}
            labels: ${{ steps.meta.outputs.labels }}


```

![dockerhub](./doc/dockerhub.png)

### 21) CD - Deploy to Azure AKS

Deploy the Container image to [Azure AKS](https://azure.microsoft.com/en-in/services/kubernetes-service/), [kubernetes](https://kubernetes.io) manifest files are available  [here](https://github.com/judebantony/cicd-github-action-example/tree/main/manifests).

```yaml 

  qadeploy:
    name: QA Deployment to AKS 
    runs-on: ubuntu-latest
    needs: [jfrogImageBuild, dockerHubImageBuild, gitHubPakageImageBuild]

    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Login to JFrog  
        uses: docker/login-action@v1
        with:
          registry: 'https://judebantony.jfrog.io'
          username: ${{ secrets.ARTIFACTORY_USER }}
          password: ${{ secrets.ARTIFACTORY_PASSWORD }}        
      - name: Setting AKS Context 
        uses: azure/aks-set-context@v1
        with:
          creds: ${{ secrets.AZURE_CREDENTIALS }}
          cluster-name: 'JudeAKSCluster'
          resource-group: 'DefaultResourceGroup-EUS'
      - name: Create AKS Namespace     
        run: |
            kubectl create namespace cigithubactionqa --dry-run -o json | kubectl apply -f -
      - name: Create Secret     
        uses: azure/k8s-create-secret@v1
        with:
          container-registry-url: 'https://judebantony.jfrog.io'
          container-registry-username: ${{ secrets.ARTIFACTORY_USER }}
          container-registry-password: ${{ secrets.ARTIFACTORY_PASSWORD }}
          namespace: 'cigithubactionqa'
          secret-name: 'cigithubactionqa-crd'
      - name: Deploy app to AKS 
        uses: azure/k8s-deploy@v1
        with:
          manifests: |
            manifests/deployment.yml
            manifests/service.yml
          images: |
             judebantony.jfrog.io/default-docker-local/cigithubaction:latest
          imagepullsecrets: |
            cigithubactionqa-crd   
          namespace: 'cigithubactionqa'         


```

![aks](./doc/aks.png)

### 22) Functional Test - Using Cucumber.

Run the [Cucumber](https://cucumber.io) Test Cases and upload the result to Cucumber.io and github action. The feature files are present [here](https://github.com/judebantony/cicd-github-action-example/tree/main/src/test/resources/com/jba/ci/bdd/).
 
```yaml 

  qatest:
    name: QA Validation and Report
    runs-on: ubuntu-latest
    needs: [qadeploy]
    
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Run Test Automation
        run: mvn -B verify -DexcludedGroups="Staging | LamdaTest | BrowserStack" -Dgroups="Smoke"
        env: 
          CUCUMBER_PUBLISH_TOKEN: ${{secrets.CUCUMBER_PUBLISH_TOKEN}}
      - name: Upload Test Automation Report
        uses: deblockt/cucumber-report-annotations-action@v1.7
        with:
          access-token: ${{ secrets.GITHUB_TOKEN }}
          path: "target/cucumber-reports/cucumber.json"
          check-status-on-error: 'neutral'
          annotation-status-on-error: 'warning'    
      - name: Upload Cucumber report
        uses: actions/upload-artifact@v2
        with:
          name: cucumber-report
          path: target/cucumber-reports/cucumber.html

```

![cucumber](./doc/cucumber.png)

Upload the result to Cucumber.io Report

![cucumberreport](./doc/cucumberreport.png)

### 23) Functional UI Test - Using BrowserStack.

Run the [Selenium](https://www.selenium.dev) UI [Cucumber](https://cucumber.io) Test Cases using [BrowserStack](https://www.browserstack.com) and capture the result. The feature files are present [here](https://github.com/judebantony/cicd-github-action-example/tree/main/src/test/resources/com/jba/ci/bdd/).

```yaml 

  browserStackTest:
    name: 'BrowserStack QA Test Validation'
    runs-on: ubuntu-latest 
    needs: [qadeploy]
    
    steps:

      - name: 'BrowserStack Env Setup'  
        uses: browserstack/github-actions/setup-env@master
        with:
          username:  ${{ secrets.BROWSERSTACK_USERNAME }}
          access-key: ${{ secrets.BROWSERSTACK_ACCESS_KEY }}

      - name: 'BrowserStack Local Tunnel Setup' 
        uses: browserstack/github-actions/setup-local@master
        with:
          local-testing: start
          local-identifier: random

      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Run BrowserStack Test Automation
        run: mvn -B verify -DexcludedGroups="Staging | Smoke | LamdaTest" -Dgroups="BrowserStack"
        env: 
          CUCUMBER_PUBLISH_TOKEN: ${{secrets.CUCUMBER_PUBLISH_TOKEN}}

      - name: 'BrowserStackLocal Stop'  
        uses: browserstack/github-actions/setup-local@master
        with:
          local-testing: stop

```

![browserstack](./doc/browserstack.png)

### 24) Functional UI Test - Using LamdaTest.

Run the [Selenium](https://www.selenium.dev) UI [Cucumber](https://cucumber.io) Test Cases using [LamdaTest](https://www.lambdatest.com/?fp_ref=aliakbar42) and capture the result. The feature files are present [here](https://github.com/judebantony/cicd-github-action-example/tree/main/src/test/resources/com/jba/ci/bdd/).

```yaml 

  lamdaTest:
    name: 'LamdaTest QA Test Validation'
    runs-on: ubuntu-latest 
    needs: [qadeploy]
    
    steps:
      - name: Start Tunnel
        id: tunnel
        uses: LambdaTest/LambdaTest-tunnel-action@v1
        with:
          user: ${{ secrets.LT_EMAIL }}
          accessKey: ${{ secrets.LT_ACCESS_KEY }}
          tunnelName: "testTunnel"
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2     
      - name: Run LamdaTest Automation
        run: mvn -B verify -DexcludedGroups="Staging | Smoke | BrowserStack" -Dgroups="LamdaTest"
        env: 
          CUCUMBER_PUBLISH_TOKEN: ${{secrets.CUCUMBER_PUBLISH_TOKEN}}
          LT_EMAIL: ${{ secrets.LT_EMAIL }}
          LT_ACCESS_KEY: ${{ secrets.LT_ACCESS_KEY }}
      - name: Export Tunnel Logs for debugging
        uses: actions/upload-artifact@v2
        with:
           name: tunnel_logs
           path: ${{ steps.tunnel.outputs.logFileName }}          

```

![lambdatest](./doc/lambdatest.png)

### 25) DAST Scan - Using StackHawk.
Use [StackHawk](https://www.stackhawk.com) for DAST scan for all the [OpenAPI](https://swagger.io/specification/) compliant REST APIs. StackHawk config file is present [here](https://github.com/judebantony/cicd-github-action-example/tree/main/stackhawl.yml).

```yaml 

  stackhawkScan:
    name: DAST Scan using StackHawk
    runs-on: ubuntu-20.04
    needs: [qatest, browserStackTest, lamdaTest]

    steps:
      - name: Checkout code
        uses: actions/checkout@v2
        with:
          fetch-depth: 0
      - name: Download OpenAPI Spec
        run: |
          curl http://20.81.93.165/api-docs > openapi.json
      - name: Run HawkScan
        uses: stackhawk/hawkscan-action@v1.3.2
        continue-on-error: true
        with:
          apiKey: ${{ secrets.HAWK_API_KEY }}
          configurationFiles: stackhawk.yml
          codeScanningAlerts: true
          githubToken: ${{ secrets.GITHUB_TOKEN }}   
          environmentVariables: |
            APP_HOST
            APP_ENV
            APP_ID
        env:
          APP_HOST: http://20.81.93.165
          APP_ENV: Development
          APP_ID: ea0079f1-648e-4bdb-aa2d-233696082b4e

```

![stackhawk](./doc/stackhawk.png)

### 26) Setting up Approval Gates and Email.

Set up approval gates for deployment using [Github Environment](https://docs.github.com/en/actions/deployment/targeting-different-environments/using-environments-for-deployment).

```yaml 

 stagingdeployapproval:
    name: Waiting for Staging Deployment Approval
    runs-on: ubuntu-latest
    needs: [stackhawkScan]
    environment: staging
    
    steps:
      - name: Email Status
        uses: dawidd6/action-send-mail@v3
        with:
          server_address: smtp.gmail.com
          server_port: 465
          username: ${{secrets.MAIL_USERNAME}}
          password: ${{secrets.MAIL_PASSWORD}}
          subject: Stage Deployment ${{github.repository}} waiting for your approval.
          to: judebantony@gmail.com
          from: judebantonyofficial@gmail.com
          body: Please review the test result and approve it.
          reply_to: judebantonyofficial@gmail.com
          in_reply_to: judebantonyofficial@gmail.com
          ignore_cert: true
          convert_markdown: true
          priority: low

```

### 27) CD - Deploy to Azure AKS using Helm.
Deploy the Container image to [Azure AKS](https://azure.microsoft.com/en-in/services/kubernetes-service/) using [Helm](https://helm.sh), manifest files are available  [here](https://github.com/judebantony/cicd-github-action-example/tree/main/helm).

```yaml 

 stagingdeploy:         
    name: Staging Deployment Using Helm To AKS
    runs-on: ubuntu-latest
    needs: [stagingdeployapproval]

    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Install Helm
        uses: Azure/setup-helm@v1
        with:
          version: v3.7.1    
      - name: Login to JFrog  
        uses: docker/login-action@v1
        with:
          registry: 'https://judebantony.jfrog.io'
          username: ${{ secrets.ARTIFACTORY_USER }}
          password: ${{ secrets.ARTIFACTORY_PASSWORD }}        
      - name: Setting AKS Context 
        uses: azure/aks-set-context@v1
        with:
          creds: ${{ secrets.AZURE_CREDENTIALS }}
          cluster-name: 'JudeAKSCluster'
          resource-group: 'DefaultResourceGroup-EUS'
      - name: Create AKS Namespace     
        run: |
            kubectl create namespace cigithubactionstaging --dry-run -o json | kubectl apply -f -
      - name: Create Secret     
        uses: azure/k8s-create-secret@v1
        with:
          container-registry-url: 'https://judebantony.jfrog.io'
          container-registry-username: ${{ secrets.ARTIFACTORY_USER }}
          container-registry-password: ${{ secrets.ARTIFACTORY_PASSWORD }}
          namespace: 'cigithubactionstaging'
          secret-name: 'cigithubactionstaging-crd'
      - name: Run Helm Deploy
        run: |
         helm upgrade \
              --install \
              --create-namespace \
              --atomic \
              --wait \
              --namespace cigithubactionstaging \
              cigithubaction \
              ./helm/aks \

```

### 28) CD - Deploy to Google GKE using Harness.
Deploy the Container image to [Google GKE](https://cloud.google.com/kubernetes-engine/?utm_source=google&utm_medium=cpc&utm_campaign=japac-IN-all-en-dr-bkws-all-all-trial-e-dr-1009882&utm_content=text-ad-none-none-DEV_c-CRE_468709677813-ADGP_Hybrid%20%7C%20BKWS%20-%20EXA%20%7C%20Txt%20~%20Containers%20~%20Kubernetes%20Engine_Kubernetes-gke-KWID_43700033867246010-aud-970366092687%3Akwd-372556496315&userloc_9299054-network_g&utm_term=KW_google%20gke&ds_rl=1264446&gclid=CjwKCAiAhreNBhAYEiwAFGGKPBhVfsfPwkEB1Yzehiow3pcsq-P9Pv78G4P28anuVF9HtSPtoNZCFxoCqr0QAvD_BwE&gclsrc=aw.ds) using [Harness](https://harness.io).

```yaml 

  uatdeploy:
    name: UAT Deployment using Harness
    runs-on: ubuntu-latest
    needs: [uateployapproval]

    steps:
      - name: Run Harness UAT Deployment
        run: |
          curl -X POST -H 'content-type: application/json' --url https://app.harness.io/gateway/api/webhooks/Tlugr1ZdISx44rvm4flAiXHMb3uKG3ikyiHSbOks?accountId=aGS5Pi_WSPa9IsdlTlJc7g -d '{"application":"1FYrnQdZROqjpAQdCBIMbw"}'
```
![gke](./doc/gke.png)

Harness
![harness](./doc/harness.png) 

### 29) Load/Performance Testing - K6.
Performance Test using [K6](https://k6.io). Load Test file is present here [here](https://github.com/judebantony/cicd-github-action-example/tree/main/k6-test.js).

```yaml 

  k6_cloud_test:
    name: Perf Testing - k6 cloud test run
    runs-on: ubuntu-latest
    needs: [terraform]
    steps:
      - name: Checkout
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Run k6 cloud test
        uses: k6io/action@v0.1
        with:
          filename: k6-test.ts
          cloud: true
          token: ${{ secrets.K6_CLOUD_API_TOKEN }}

```
![k6](./doc/k6.png)

### 30) Functional Test using Xray and Jira.
Create the test case using [Gherkin](https://cucumber.io/docs/gherkin/) and [Cucumber](https://cucumber.io) in Jira for each story and excute as part of CI/CD. Upload the result back to Jira. XRay Test Execution config file is present [here](https://github.com/judebantony/cicd-github-action-example/tree/main/testexec_cloud_template.json).

```yaml 

  jiraXrayTest:
    name: Functional Test using Xray and Jira 
    runs-on: ubuntu-latest
    needs: [uatdeploy]
        
    steps:
      - name: Check out the code
        uses: actions/checkout@v1
        with:
          fetch-depth: 0
      - name: Set up JDK
        uses: actions/setup-java@v1
        with:
          java-version: 1.8
      - name: Cache Maven packages
        uses: actions/cache@v1
        with:
          path: ~/.m2
          key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
          restore-keys: ${{ runner.os }}-m2    
      - name: Get Xray Cloud API token
        env:
          CLIENT_ID: ${{ secrets.XRAY_CLIENT_ID }}  
          CLIENT_SECRET: ${{ secrets.XRAY_CLIENT_SECRET }}
        id: xray-token
        run: |
          echo ::set-output name=XRAY_TOKEN::$(curl -H "Content-Type: application/json" -X POST --data "{ \"client_id\": \"$CLIENT_ID\",\"client_secret\": \"$CLIENT_SECRET\" }" https://xray.cloud.xpand-it.com/api/v1/authenticate| tr -d '"')
      - name: Get Features from XRAY 
        shell: bash
        run: |
           curl -H "Content-Type: application/json" --output ./features.zip -X GET -H "Authorization: Bearer ${{ steps.xray-token.outputs.XRAY_TOKEN }}"  "https://xray.cloud.xpand-it.com/api/v1/export/cucumber?keys=JUDE-43"
           unzip -o features.zip -d ./src/test/resources/com/jba/ci/bdd/   
      - name: Build
        run: mvn -B clean package -DskipTests
      - name: Run UnitTest and Verify 
        run: mvn -B verify -DexcludedGroups="Smoke | Staging | BrowserStack | LamdaTest"
      - name: Generate JaCoCo Badge
        id: jacoco
        uses: cicirello/jacoco-badge-generator@v2
      - name: Log code coverage percentage
        run: |
          echo "coverage = ${{ steps.jacoco.outputs.coverage }}"
          echo "branch coverage = ${{ steps.jacoco.outputs.branches }}"
      - name: Upload to XRAY 
        shell: bash
        run: |
           curl  -X POST -H "Authorization: Bearer ${{ steps.xray-token.outputs.XRAY_TOKEN }}" -F info=@testexec_cloud_template.json -F results=@"target/cucumber-reports/cucumber.json" "https://xray.cloud.xpand-it.com/api/v1/import/execution/cucumber/multipart"          

```
![xray](./doc/xray.png)

### 31) Release Tag Creation.
Create a release tag for the branch. 

```yaml 

  releaseTag:
      name: Release Tag Creation 
      runs-on: ubuntu-latest
      needs: [k6_cloud_test]
      steps:
        - name: Checkout
          uses: actions/checkout@v2
          with:
            fetch-depth: 0
        - name: Bump version and push tag
          id: tag_version
          uses: anothrNick/github-tag-action@1.26.0
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
            WITH_V: true
        - name: Create a GitHub release
          uses: ncipollo/release-action@v1
          with:
            tag: ${{ steps.tag_version.outputs.new_tag }}
            name: Release ${{ steps.tag_version.outputs.new_tag }}
            body: ${{ steps.tag_version.outputs.changelog }}  

```

![releasetag](./doc/releasetag.png)

### 32) IaC - using Terraform - Create AWS EC2.
Set up the AWS EC2 instances using [Terrform](https://www.terraform.io) , manifest file is available [here](https://github.com/judebantony/cicd-github-action-example/tree/main/terraform).

```yaml 

  terraform:
    name: "Terraform - Create AWS EC2"
    runs-on: ubuntu-latest
    needs: [uatdeploy]
    steps:
      - name: Checkout
        uses: actions/checkout@v2
        with:
          fetch-depth: 0
      - name: Setup Terraform
        uses: hashicorp/setup-terraform@v1
        with:
          cli_config_credentials_token: ${{ secrets.TF_API_TOKEN }}
      - name: Terraform Format
        id: fmt
        run: |
            cd terraform/
            terraform fmt -check
      - name: Terraform Init
        id: init
        run: |
            cd terraform/
            terraform init
      - name: Terraform Validate
        id: validate
        run: |
            cd terraform/
            terraform validate -no-color
      - name: Terraform Plan
        id: plan
        run: |
            cd terraform/
            terraform plan -no-color
        continue-on-error: true
      - uses: actions/github-script@0.9.0
        id: return_plan_outpot
        env:
          PLAN: "terraform\n${{ steps.plan.outputs.stdout }}"
        with:
          github-token: ${{ secrets.GITHUB_TOKEN }}
          script: |
            const output = `#### Terraform Format and Style \`${{ steps.fmt.outcome }}\`
            #### Terraform Initialization ️\`${{ steps.init.outcome }}\`
            #### Terraform Validation \`${{ steps.validate.outcome }}\`
            #### Terraform Plan \`${{ steps.plan.outcome }}\`
            <details><summary>Show Plan</summary>
            \`\`\`\n
            ${process.env.PLAN}
            \`\`\`
            </details>
            *Pusher: @${{ github.actor }}, Action: \`${{ github.event_name }}\`*`;
            return output;
      - name: Create plan result
        uses: "finnp/create-file-action@master"
        env:
          FILE_NAME: "plan.html" 
          FILE_DATA: "${{steps.return_plan_outpot.outputs.result}}"     
        
      - name: Upload Terraform Plan result
        uses: actions/upload-artifact@v2
        with:
          name: terrform-plan-result
          path: plan.html
             
      - name: Terraform Plan Status
        if: steps.plan.outcome == 'failure'
        run: exit 1
        
      - name: Terraform Apply
        run: |
            cd terraform/
            terraform apply -auto-approve  

```

![teraform](./doc/teraform.png)

## Author

Jude Antony ([LinkedIn](https://www.linkedin.com/in/jude-antony-2b208219/))