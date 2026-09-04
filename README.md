# AISTATS 2027

Year site for the 30th International Conference on Artificial Intelligence and Statistics (AISTATS 2027), planned for Montréal, Canada. Hosted on GitHub Pages at <https://aistats.org/aistats2027/>.

Content is driven by `_config.yml` and markdown pages; chrome comes from the remote theme [`aistats/jekyll-theme`](https://github.com/aistats/jekyll-theme). Organiser notes live under `_doc/` (unpublished).

## Status

- Location: Montréal, Canada (venue and meeting days TBA)
- Draft programme: `conference.draft: true`
- Early submission deadlines seeded from [virtual.aistats.org](https://virtual.aistats.org/Conferences/2027); confirm before relying on them

## Technical notes

- `baseurl` must remain `/aistats2027/` so CSS and assets resolve under that path.
- Deadline timezone: top-level `timezone: AOE`. Keep date values parseable; do not put “Anywhere on Earth” inside YAML date strings.
- For syncing with virtual, see `_doc/virtual-sync.md` if present, or [`aistats/site-management`](https://github.com/aistats/site-management) `scripts/sync_virtual/`.
