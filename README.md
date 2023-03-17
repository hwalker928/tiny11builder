# tiny11builder

Scripts to build a trimmed-down Windows 11 image - forked from https://github.com/ianis58/tiny11builder

It's open-source, so feel free to add or remove anything you want! Feedback is also much appreciated.

Current and new Windows 11 builds are supported, but may need some small adjustments. Please report issue or create pull requests if you're able to patch some issues.

Instructions:

1. Download latest Windows 11 ISO (<https://www.microsoft.com/software-download/windows11>).
2. Install the Windows ADK (<https://learn.microsoft.com/en-us/windows-hardware/get-started/adk-install>).
3. Open a Powershell terminal with admin rights and run the following commands:

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\creator.ps1
```

4. Sit back and relax :)
5. When the image is completed, you will see it in C:\Win11Pro-Patched.iso
