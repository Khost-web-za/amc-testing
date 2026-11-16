# amc-publish-test

Throwaway repo for testing allminecraft's GitHub Actions publishing. Publishing a GitHub release runs `.github/workflows/release.yml`, which zips `pack/` and publishes it to the linked post using the vendored Action in `.github/actions/publish/`.

Repository variables used by the workflow:

- `AMC_POST_ID`: the post's numeric id
- `AMC_API_URL`: the site origin (staging or tunnel), `https://`, no trailing slash

## allminecraft

<!-- Paste the badge snippets from the post editor's Options tab here. -->
