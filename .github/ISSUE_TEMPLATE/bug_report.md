---
name: Bug report
about: Create a report to help us improve
title: "[BUG]"
labels: bug
assignees: dec05eba

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
The GPU Screen Recorder command you ran.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - X11 or Wayland:
- Desktop environment/Window Manager:
 - Distro:
 - GPU:
 - Version: (latest flatpak version, aur or source)

**Additional context**
Add any other context about the problem here, such as terminal output of running GPU Screen Recorder and if there was an issue in the video then run the command `sudo drm_info > log.log` and attach that log.log file in this bug report. drm_info can be installed from your package manager or from https://gitlab.freedesktop.org/emersion/drm_info.

- [ ] I played the video with the command `mpv --no-config video.mp4` (if applicable)
- [ ] I use a laptop with integrated GPU and dedicated GPU
