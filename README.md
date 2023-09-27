<body>
  <h1>
    <img src="https://raw.githubusercontent.com/he3als/EdgeRemover/main/EdgeRemover.svg" 
      alt="EdgeRemover Icon"
      style="vertical-align:middle;display:inline;height:1.2em;margin-bottom:.2em">
    EdgeRemover
  </h1>
<body>

A PowerShell script that aims to non-forcefully remove Microsoft Edge in a user-friendly manner on Windows 10 and 11, based upon [ave9858's uninstallation method](https://gist.github.com/ave9858/c3451d9f452389ac7607c99d45edecc6).

## ⬇️ Usage
You can use this command in the Run dialog or Command Prompt for quick access. Alternatively, get the script from the GitHub releases.

For people that want to implement this in scripts, run `Get-Help .\RemoveEdge.ps1`. You can append these arguments to the `get.ps1` snippet.

```powershell
powershell iex(irm https://raw.githubusercontent.com/he3als/EdgeRemover/main/get.ps1)
```