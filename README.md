### Mend Global Repo Configuration

This repository contains your Mend Global Repo Configuration.
It can be configured via the following configuration files: repo-config.json and global-config.json.

The [global-config.json](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html#GlobalRepoConfiguration-global-config.json) file lets you define global configurations for the integration.
<br/><br/>
The [repo-config.json](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html#GlobalRepoConfiguration-repo-config.json) file lets you apply configuration parameters for a Mend scan across all of your integrated repositories. All integrated repositories will inherit the configuration parameters set in this file, unless explicitly overridden by a local .whitesource file in the relevant repository.


---

:question: Got questions? Check out the Global Repo Configuration [docs](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html).
If you need any further assistance then you can also [request help here](https://whitesourcesoftware.force.com/CustomerCommunity/s).
Adding "enableLicenseViolations": true to enable License policy checks in the scanSettings{} section

Adding "enableReachability": true to enable Reachability Analysis in the scanSettings{} section

Change "enableScan":false to true to enable SAST scanning in the "scanSettingsSAST"{} section

Change "scanPullRequests":false to true to enable scanning on pull requests in the "scanSettingsSAST"{} section

Add "strictMode": "warning" to enable partial scan warnings in the checkRunSettings{} section
Add a proactive remediation strategy - Renovate with Smart Merge

Add Code Source

Do NOT modify "baseBranches": [],
