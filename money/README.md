# money

Pictures for the money app (money.sanglam.cc, repo kinhsman/money-hub).

- `merchants/`: each merchant logo the owner added, as a 128 by 128 PNG named by a fingerprint
  of its content. The money-hub helper publishes them (server/drive-backup/lib/publicLogos.js)
  when a merchant is added or its logo changes, and removes the ones no merchant uses any more.
  Friends' photos are never published here, only brands.

- `app/icon.png`: the money app's own icon (the one on the home screen, Wealthfolio's), 256 by 256.
  Alerts with no merchant logo show it instead (server/drive-backup/lib/alerts.js). Placed by hand;
  link it pinned to a commit.

`merchants/` is written by a program: changes made by hand there are undone by the next publish.
