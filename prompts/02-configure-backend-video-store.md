# Configure the backend video store

**Status:** Approved
**Approved on:** 07/10/2026 10:01 (Europe/Madrid)
**Approved by:** Auger
**Task:** #2
**Used for:** Configuring ENV_PROTUBE_STORE_DIR for the Spring Boot application in IntelliJ IDEA.

## Prompt

The video grabber saved the sample videos in `C:/protube-videos/`.
Explain how to configure `ENV_PROTUBE_STORE_DIR` so the Spring Boot backend can
find them. Check the project's configuration and setup documentation. Guide me
step by step through adding the variable to the `ProtubeBackApplication` run
configuration in IntelliJ IDEA, including the required trailing separator.
Explain how each teammate should configure their own store location and how to
check any shared run configuration for assumptions about the checkout location.
Do not edit project files or change the selected module automatically.

## Notes

This reusable prompt was drafted after troubleshooting; it is not a verbatim
record of the prompts used during the original session.

Original user requests (verbatim):

> Should the environment variable "$env:ENV_PROTUBE_STORE_DIR" be the same that we used right now for executing the script via PowerShell? We used "C:/protube-videos/" in the downloading videos case.

> Where can I add this to the run configuration's environment variables?

