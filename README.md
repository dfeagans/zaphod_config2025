Zaphod and Zaphod Lite ZMK Config
=================================

This configuration may be used independently as a ZMK config as
described in https://zmk.dev/docs/development/build-flash#building-from-zmk-config-folder
or it can be included as a module.

Using This Config as a Module
-----------------------------

Add this repository to your `config/west.yml` in the `remotes` and
`projects` sections, adding the following snippets alongside the
entries that are already there.

```yaml
  remotes:
    - name: zaphod
      url-base: https://github.com/petejohanson
  projects:
    - name: zaphod-config
      remote: zaphod
      revision: main
```
