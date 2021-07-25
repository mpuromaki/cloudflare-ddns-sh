# cloudflare-ddns-sh
Shell script for dynamically updating cloudflare DNS ip-address.

Adapted from gist by Tras2 (https://gist.github.com/Tras2/cba88201b17d765ec065ccbedfb16d9a).

Uses Cloudflare DNS:Edit bearer token to update Cloudflare DNS entry to current IP-address.
Run this from a cron job to automatically update Cloudflare DNS. In Truenas, this can be done
under Advanced settings. Remember to "chmod +x" this file.