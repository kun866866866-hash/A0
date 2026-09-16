# A0: Set Up

Course instructions: https://github.com/UMN-CSCI5609/Assignments-Instructions/tree/main/A0-Setup

The SvelteKit project is directly inside this folder. The completed page is
`src/routes/+page.svelte`; the original course template is saved in
`reference/A0.svelte.txt`.

## Run locally

With Node.js 24 and npm installed:

```sh
npm ci
npm run dev -- --open
```

On this Mac, Node and pnpm are currently available through the Codex runtime.
If `npm` is not found, use:

```sh
export PATH="/Users/kunchen/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin:/Users/kunchen/.cache/codex-runtimes/codex-primary-runtime/dependencies/bin/fallback:$PATH"
pnpm dlx npm run dev -- --open
```

## Check

```sh
npm run check
npm run build
```

The initial limit is 2. Selecting 2, 4, or 6 resets the remaining count.
Each button click subtracts one; further clicks at zero do nothing.

The title currently uses Kun Chen and the image is a local mountain illustration.
You can change the name in `+page.svelte` and replace `static/mountains.svg`.

## Publish and submit

1. Publish this folder as a GitHub repository named `A0` on the `main` branch.
   If you use a different repository name, update `/A0` in `svelte.config.js`
   and `.github/workflows/build-and-deploy.yml`.
2. Apply for GitHub student benefits. The course permits a temporarily public
   repository while approval is pending; afterward use a private repository.
3. Select Settings > Pages > Source > GitHub Actions.
4. Push the project, wait for deployment, and verify the public page works.
5. Give the TA (`mkrstulovic`) and instructor access to the private repository
   as required by the Canvas rubric. Confirm the instructor's GitHub username.
6. Submit both the GitHub Pages URL and repository URL on Canvas.
7. Complete the separately announced AI research consent/opt-out form.

GitHub publication, collaborator invitations, the form, and Canvas submission
have not been completed by this local project setup.
