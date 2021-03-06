# shorewall_ng CHANGELOG

## 0.6.0

** BREAKING CHANGE **

- Migrate from masq to snat configuration, see http://docs.swarmlab.io/SwarmLab-HowTos/labs/os2/ex-4_iptables.adoc.html#_snat_shorewall_snatmasquerade_definition_file
- Migrate tests to dokken for faster tests

## 0.5.0

** BREAKING CHANGE **

- Remove debian jessie and stretch support (shorewall 5.1+ only)
- Remove LOAD_HELPERS_ONLY=yes from configuration, since it is unsupported now

---

## 0.4.1

- smaller bugfixes

## 0.4.0

- removed old shorewall5 recipe since we only support 5.x anyways
- remove old shorewall 4.x leftovers, since it is unsupported anyway
- remove [shorewall][version] variable since it is never used at all
- test against debian buster
- ensure compatibility with buster and stretch at the same time ( shorewall 5.0 and 5.2 )
- fix support for chef client 14+

  0.3.1

---

- Support 5.0 and 5.1+ installations, yet detected by disto version

  0.3.0

---

- Upgraded configuration to 5.1 / 5.2 standards, removed all deprecations

  0.2.0

---

- removed shorewall4 support
- fixed bug with symbol vs string access using hash.fetch

  0.1.2

---

- important readme adjustments

  0.1.1

---

- source_url / issue_url

  0.1.0

---

- Intial release of shorewall_ng with shorewall5 support
