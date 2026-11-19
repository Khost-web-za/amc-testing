
<a href="https://allminecraft.net/post/221"><picture><source media="(prefers-color-scheme: dark)" srcset="https://allminecraft.net/badge/221/banner.svg?theme=dark&count=site"><source media="(prefers-color-scheme: light)" srcset="https://allminecraft.net/badge/221/banner.svg?theme=light&count=site"><img alt="Download on AllMinecraft" src="https://allminecraft.net/badge/221/banner.svg?theme=dark&count=site" width="420" height="84"></picture></a>

# amc-publish-test

Throwaway repo for testing allminecraft's GitHub Actions publishing. Publishing a GitHub release runs `.github/workflows/release.yml`, which zips `pack/` and publishes it to the linked post using the vendored Action in `.github/actions/publish/`.

Repository variables used by the workflow:

- `AMC_POST_ID`: the post's numeric id
- `AMC_API_URL`: the site origin (staging or tunnel), `https://`, no trailing slash

## allminecraft

<!-- Paste the badge snippets from the post editor's Options tab here. -->
