# watchtower-config

## Roadmap
- [ ] Extract and provision Emby configuration
- [ ] Enforce ufw rules
  - [ ] Add rules for Emby ports
  - [ ] Add rules for Samba ports
- [ ] Require login for Samba shares
- [ ] Backup emails from main accounts
- [ ] Install BitTorrent client
- [ ] Install Newsgroup client
- [ ] Benchmark and performance tweak RAID array
- [ ] Setup and test RAID monitoring
  * http://linuxbsdos.com/2015/02/10/how-to-configure-ubuntu-14-04-server-to-forward-root-mails-to-your-email-address/
  * https://github.com/xcezx/ansible-aliases
  * https://wiki.archlinux.org/index.php/msmtp
- [ ] Set hostname
- [ ] Setup bootstrap role
  - [ ] Disable SSH password login
- [ ] Experiment with Mopidy
- [ ] Research using Dynamic DNS to make server externally reachable
  * http://perceptionistruth.com/2013/05/running-your-own-dynamic-dns-service-on-debian/
  * http://andrwe.org/linux/own-ddns
  * http://dyn.com/dns
  * https://entrydns.net
  * https://github.com/troglobit/inadyn
- [ ] Verify that Emby packages aren't signed and report bug if so
