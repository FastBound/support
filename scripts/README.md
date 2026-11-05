# The scripts have moved

FastBound's API scripts now live in their own repository:
**<https://github.com/FastBound/scripts>**

The PowerShell scripts were renamed to standard Verb-Noun names, so the old file names
no longer exist:

| Old name | New name |
|----------|----------|
| `Update-FastBound-Items.ps1` | `Update-FastBoundItem.ps1` |
| `Import-FastBoundItems.ps1` | `Import-FastBoundItem.ps1` |
| `Import-FastBoundContacts.ps1` | `Import-FastBoundContact.ps1` |
| `Merge-FFLContacts.ps1` | `Merge-FastBoundContact.ps1` |
| `FastBound-UpdateExternals.ps1` | `Update-FastBoundExternalId.ps1` |
| `Clean-UPC.ps1` | `Repair-FastBoundUpc.ps1` |
| `Bound Book Download/Download-BoundBook.ps1` | `Save-FastBoundBoundBook.ps1` |
| `Bound Book Download/Download-BoundBooks.ps1` | `Save-FastBoundBoundBookAll.ps1` |

Every script is at the root of the new repository. `download-boundbook.py` and
`download-boundbook.sh` keep their names.

Several parameter names changed as well, so update existing command lines and scheduled
tasks before running the new versions. `Get-Help <script> -Full` lists each script's
current parameters.
