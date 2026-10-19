# ShopPage

Source for [bhavyam.shop](https://bhavyam.shop/).

The PDF workspace is maintained separately in [AdelanteCodes/PDFViewer](https://github.com/AdelanteCodes/PDFViewer). The Pages workflow verifies and includes that app when assembling this site, preserving `/pdf-viewer/` and all existing download links. No PDF application source is duplicated in this repository.

Deployments run on main pushes, manually through Actions, and every 30 minutes to pick up PDF releases. `/pdf-viewer/source-revision.txt` identifies the included PDF commit. Scheduled runs can be delayed by GitHub.

Rollback: the pre-separation ShopPage snapshot is commit `4898faf1aa63d8879a8cfe6d7f67d5f4a3db51ad`. Restore the old tree and branch-based Pages deployment if reverting the migration.
