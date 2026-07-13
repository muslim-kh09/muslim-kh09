# Khaled Hani

Software developer focusing on Go, memory optimization, and system utilities.

---

## Featured Project

### Sentinel
A high-performance Git secret scanner and pre-commit hook written in Go, optimized for low-resource environments.

* **Repository:** [sentinel-cli/sentinel](https://github.com/sentinel-cli/sentinel)
* **Availability:** [GitHub Marketplace Action](https://github.com/marketplace/actions/sentinel-git-secrets-scanner)

#### Technical Specifications
* **Architecture:** Implements an 8 MB chunk-based streaming reader to ensure a flat memory footprint regardless of file size.
* **Memory Management:** Designed with a zero-allocation-per-line scanning mechanism to eliminate heap overhead.
* **Analysis Capabilities:** Supports deep historical scanning (`--history`) via Git object traversal and false-positive suppression logic.
* **Integrations:** Outputs data natively in SARIF and JSON formats, making it compatible with GitHub Code Scanning and standard CI/CD pipelines.
