# regulad/nssm: build branch

This branch holds only the build pipeline. The source is upstream NSSM, kept
untouched on `master` and in the `v*` tags:

- `master` is upstream's last commit, `dee49fc` (2.24-103-gdee49fc), the same
  code as the 2.24-103 build nssm.cc published.
- `v1.0` through `v2.24` are Iain Patterson's own annotated tags. Upstream's
  server no longer carries any tags, so these come from the mirrors that cloned
  it before they were lost, where those mirrors agree.

Upstream: https://nssm.cc/ (source formerly at https://git.nssm.cc/nssm/nssm).
