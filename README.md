# POLS W4732 lecture slides

This repository contains the generated public HTML presentations and printable
handouts for POLS W4732.

The editable lecture sources are maintained separately. Files in this repository
are updated by the course's `publish.ps1` workflow.

Do not edit generated files in this `site` folder directly.

To publish already-built lecture files, open PowerShell and run:

```powershell
cd "C:\Users\pratino\Dropbox\POLSW4732\2026 Course\Lectures 2026"
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass -Force
.\publish.ps1
```

To publish already-built problem-set PDFs:

```powershell
cd "C:\Users\pratino\Dropbox\POLSW4732\2026 Course\Problem Sets 2026"
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass -Force
.\publish.ps1
```

The execution-policy bypass applies only to the current PowerShell window and
does not change the machine-wide Windows policy.
