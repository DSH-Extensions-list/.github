# DSH Extensions — organization profile

I keep the public extension catalog in **[profile/README.md](profile/README.md)** and it appears on the [DSH Extensions organization page](https://github.com/DSH-Extensions-list).

It helps visitors choose an extension, understand what it adds to DeepSeek Harness, and find the right installation route. I use this repository for the catalog and its maintenance guidance; extension code belongs in each project's repository.

## Keeping the catalog current

1. Check the current DSH profile's declared dependencies and installed package manifests. A repository's existence alone does not establish that it belongs in the current collection.
2. Check public repository visibility, README features, and available release assets. Link only publicly accessible destinations from the organization profile.
3. Put each extension in a useful category and describe its actual behavior in one sentence. Use the distribution labels consistently: **Source**, **Source fork**, **Adapted source + release package**, **Package snapshot**, or **Upstream npm reference**.
4. Keep locally installed editions without an organization distribution in **Also in my setup**. Link upstream and state that upstream downloads do not contain my unpublished changes.
5. Remove retired entries from the current catalog. Preserve repository history unless repository removal is separately requested.
6. Update the reconciliation date after checking the installation. Keep version inventories out of the landing page; versions, compatibility ranges, and verification limits belong with each package.

## Distribution and attribution

- Link snapshots to their release archives and preserve their provenance documents and file inventories.
- Keep upstream authorship and licenses visible. An English edition or a package snapshot is not a claim of original authorship.
- A reference repository is not an installable package. In particular, Subscriptions uses its original npm distribution.
- Describe verification precisely. Source checks or Linux rendering do not establish successful use in Microsoft PowerPoint or on every supported platform.

## Reporting catalog issues

[Open an issue](https://github.com/DSH-Extensions-list/.github/issues/new) for a missing extension, broken link, inaccurate description, or outdated distribution instructions. Include the affected repository and a public source for the correction.

For runtime bugs and feature requests, use the individual extension's issue tracker or the upstream project's support route.
