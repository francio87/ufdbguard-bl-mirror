# :flying_saucer: ufdbGuard blacklist mirror :flying_saucer:

### Simple :robot: Github Workflow :robot: that sync `ufdbGuard` blacklists

These are the actions that will be performed every `4 hours` :

- download the file from :fr: [Blacklists UT1](https://dsi.ut-capitole.fr/blacklists/index_en.php) :fr:
- verify the `md5` of the file
- if a new update is found, the file `blacklists.tar.gz` will be saved on the repo root folder