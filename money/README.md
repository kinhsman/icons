# money

Pictures for the money app (money.sanglam.cc, repo kinhsman/money-hub).

- `merchants/`: each merchant logo the owner added, as a 128 by 128 PNG named by a fingerprint
  of its content. The money-hub helper publishes them (server/drive-backup/lib/publicLogos.js)
  when a merchant is added or its logo changes, and removes the ones no merchant uses any more.
  Friends' photos are never published here, only brands.

Written by a program: changes made by hand are undone by the next publish.
