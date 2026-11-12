# Kit Explorer

A single-file tool (`index.html`) for checking Epicor kits: parts, sub-parts, quantities,
revisions, customers, and reference pictures. No install and no internet needed. Open
`index.html` in Chrome or Edge.

## Load a kit from Epicor
1. In Method Tracker click an assembly (kit, box, or a part with an arrow), then Materials > List.
2. Right-click the grid > **Copy All Include Labels**.
3. In the tool open **Add from Epicor**, type the part number, revision and effective date,
   paste, and press **Save revision**.
4. Repeat for each box, sub-assembly and kit revision. Parts are linked by part number.

## Tabs
- **Kits**: tree of a kit revision with totals, repeats, compare two revisions.
- **Part lookup**: where a part is used (kit, revision, dates, customers) and its pictures.
- **Cross reference**: compare any number of kit revisions side by side, export CSV.
- **Add from Epicor**: save, edit and delete revisions. Customers list.
- **Backup**: automatic backup to a folder inside OneDrive (Chrome/Edge), or manual file backup.

## Your data
Saved in the browser on that computer, plus the OneDrive backup file
`kit-explorer-backup.json` if you connect a folder. The backup also holds pictures.

## Version history
See `CHANGELOG.md`. The current version is shown in the page header.
