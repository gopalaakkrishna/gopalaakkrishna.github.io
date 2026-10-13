# Portfolio maintenance

The GitHub repository is the authoritative source for this website. Work in a cloud environment or through the connected GitHub tools. The owner's PC and local checkout are not required for website edits or publishing. Do not synchronize, overwrite, or delete local copies unless explicitly requested.

## Requested updates

When the owner requests an update to the live portfolio, implement the requested change, check it, and save it to `main` using the connected GitHub tools or the cloud environment's authenticated Git access. Handle the commit and push as part of the task; do not hand routine Git steps back to the owner. Respect requests to pause, review only, or prepare a mockup without publishing.

Preserve the current section-based navigation and all existing work unless a change is requested. Keep role credits accurate. Ask for a missing credit rather than inventing one. Confirm uncertain claims against the owner's supporting material before publishing them.

## Automatic publishing

`.github/workflows/publish.yml` checks the homepage scripts, structured data, and referenced local media, then publishes the repository to GitHub Pages whenever `main` changes. It can also be run manually in GitHub Actions. The site URL is https://gopalaakkrishna.github.io/.

Verify the workflow outcome and the relevant public page after an update. A saved GitHub commit is not proof that the public deployment finished. If publication is delayed or fails, state that clearly and diagnose the workflow within the requested scope. Keep commits focused so earlier website versions can be recovered.

Website media must be available from the repository or an appropriate online host. Never link the public site to paths on the owner's local computer.
