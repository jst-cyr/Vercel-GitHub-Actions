# Vercel GitHub Actions
 In this repository you'll find a default Next.js TypeScript application which can be deployed to Vercel. Nothing fancy... EXCEPT IT HAS GITHUB ACTIONS!

 I've been looking at ways to get things like notifications on deployment failures, and possibly other things in the future. These are the GitHub Actions workflows you can find in the repo:

 1. [Deployment Failure Notification](https://github.com/jst-cyr/Vercel-GitHub-Actions/blob/main/.github/workflows/deploy-failed.yml)
    - When Vercel fails to deploy the app, the GitHub action [comments on the commit](https://github.com/jst-cyr/Vercel-GitHub-Actions/commit/f5bc3b869bb98db51588287ad70eba3dee861ae7#commitcomment-55960321) so that you can be notified via GitHub notifications.


Hopefully these can be useful for your GitHub deployments to Vercel!
