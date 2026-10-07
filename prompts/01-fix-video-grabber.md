# Diagnose video grabber failures on Windows

**Status:** Approved
**Approved on:** 07/10/2026 09:45 (Europe/Madrid)
**Approved by:** Auger
**Task:** #1
**Used for:** Diagnosing the video grabber's dependencies and executable configuration.

## Prompt

I installed the project's Python dependencies and ran this command from
`tooling/videoGrabber` in Windows PowerShell:

```powershell
python main.py --store="C:\protube-videos" --id=1 --videos="../../resources/video_list.txt" --recreate
```

Every selected video prints `Error with video: <video-id> -- Skipped`.
Inspect the script, dependency versions, and executable configuration. Explain
the cause and propose the minimum changes needed on Windows. Verify current
yt-dlp requirements against its official documentation. Provide the dependency
installation command and a way to verify the fix. Do not edit files or run
`--recreate` automatically.

## Notes

This reusable prompt was drafted after troubleshooting; it is not a verbatim
record of the prompt used during the original session.

Original user request (verbatim excerpt):

> Please find a solution. The professors says that it might be due to the dependencies which could be outdated or something related...

