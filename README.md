# jenkins_documentation

Jenkins Learning Roadmap for DevOps Engineers

---

# 1. Jenkins Basics (Foundational)

* **Jenkins Architecture**: Master vs. Agents (build nodes), scheduling.
* **Jobs/Pipelines**: Freestyle jobs, Declarative vs. Scripted pipelines.
* **Plugins**: Git, Maven, SonarQube, Docker, Slack, Blue Ocean.
* **SCM Integration**: GitHub, GitLab, Bitbucket.
* **Credentials Management**: Username/password, SSH keys, tokens.
* **Environment Variables**: Global, job-level, pipeline.

**Practice:** Connect Jenkins to a GitHub repo and trigger a build automatically.

---

# 2. Pipelines (Core Skill)

* **Declarative vs Scripted Pipelines**
* **Stages & Steps**: Sequential, conditional, parallel execution.
* **Post-actions**: always, success, failure, unstable.
* **Environment & Tools blocks**: Configure Java, Maven, Docker.
* **Shared Libraries**: Reusable code across pipelines.
* **Credentials Binding**: Use withCredentials safely.

**Practice:** Create a pipeline that compiles, tests, and packages a project.

---

# 3. Integrations

* **Source Control**: GitHub, GitLab, Bitbucket.
* **Build Tools**: Maven, Gradle, npm.
* **Code Quality / Testing**: SonarQube, JUnit/TestNG reports.
* **Artifact Management**: Nexus, Artifactory.
* **Containerization**: Docker build, push, Kubernetes deployment.
* **Notifications**: Slack, Email, MS Teams.
* **Secrets Management**: Vault, Jenkins Credentials, Kubernetes Secrets.

**Practice:** Integrate Jenkins with SonarQube and Nexus for a Java project.

---

# 4. Advanced Jenkins Skills

* **Distributed Builds**: Master-slave setup, labels, node selection.
* **Pipeline as Code**: Store Jenkinsfile in Git.
* **Parameterized Builds**: Build with user inputs (e.g., version number).
* **CI/CD Best Practices**: Branch-based pipelines, automated testing, deployment gating.
* **Monitoring & Maintenance**: Logs, plugin updates, performance tuning.
* **Backup & Recovery**: Job configs, credentials, pipeline history.
* **Blue/Green & Canary Deployments**: Jenkins + Docker/Kubernetes.

**Practice:** Implement branch-based pipelines with approvals for production deployment.

---

# 5. Hands-on Real Projects

1. CI pipeline for Java project: Maven + Unit tests → WAR deploy to Tomcat.
2. Dockerized app: Build Docker image → push to Docker Hub → deploy to Kubernetes.
3. Branch-based pipeline: Feature branches build, main branch deploy.
4. Multi-environment deployment: dev/staging/prod with approvals.
5. Integrate SonarQube + JUnit reports: Pipeline fails if quality gate fails.

---

# 6. Optional Advanced Skills

* Jenkins REST API usage.
* Shared libraries for pipelines.
* Jenkins integration with Terraform / Ansible / Helm.
* Containers + cloud CI/CD pipelines.

---

# Recommended Learning Path

1. **Weeks 1-2**: Jenkins Basics (jobs, plugins, SCM, builds)
2. **Weeks 3-4**: Pipelines (stages, steps, post actions, environment)
3. **Weeks 5-6**: Integrations (Git, Maven, SonarQube, Nexus, Docker, Slack)
4. **Weeks 7-8**: Advanced (distributed builds, CI/CD best practices, multi-env deployment)
5. **Weeks 9+**: Hands-on projects & production-ready pipelines.
