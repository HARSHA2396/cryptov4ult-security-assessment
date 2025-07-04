---

**File: remediation/container-remediation.md**

# 📆 Container Security Remediation

## 1. CVE-2014-6271 (Shellshock)

* **Issue**: Bash vulnerability allowing remote command execution.
* **Remediation**:

  * Update Bash to a patched version:

    ```bash
    apt-get update && apt-get install --only-upgrade bash
    ```
  * Regularly rebuild and redeploy containers to inherit latest patches.

## 2. Outdated Base Images

* **Issue**: Containers are built on vulnerable/unmaintained images.
* **Remediation**:

  * Switch to **minimal base images** like Alpine or Ubuntu LTS.
  * Use Docker multi-stage builds to reduce image size and attack surface.

## 3. No Image Scanning

* **Issue**: No automated checks are in place to detect vulnerable dependencies.
* **Remediation**:

  * Integrate **Trivy**, **Grype**, or **Clair** into your CI/CD pipeline.
  * Prevent deployment of images with critical/high vulnerabilities.
  * Maintain a container image inventory with version tracking.


---
