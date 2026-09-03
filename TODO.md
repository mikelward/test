# TODO

## Set up

- [ ] Replace the placeholder job in `.github/workflows/ci.yml` with this
      project's real jobs (tests, a build, lint -- whatever applies), each
      carrying `needs: classify` and
      `if: needs.classify.outputs.docs_only != 'true'`. Add each job's
      name to the `lanes` job's own `needs:` and `results:`, then delete
      the placeholder.
