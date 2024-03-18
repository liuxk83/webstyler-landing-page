# FlavorForge
## by Kevin Liu

This repo contains a [landing page](https://liuxk83.github.io/hugo-mock-landing-page-autodeployed/) for FlavorForge, an (imaginary) product that 3D-prints delicious meals.
Made using the static site generator Hugo and [Felipe Carneiro's Bootstrap theme](https://github.com/filipecarneiro/hugo-bootstrap-theme).

This repo builds on [another repo](https://github.com/liuxk83/hugo-mock-landing-page) by adding a GitHub Action that automatically builds and deploys the landing page each time a commit is pushed. The GitHub Actions [`.yaml` file](https://github.com/liuxk83/hugo-mock-landing-page-autodeployed/blob/main/.github/workflows/gh-pages-deployment.yaml) was originally written by Jérémie Lumbroso and uses actions developed by Shohei Ueda (`peaceiris`) to set up a Hugo environment and deploy the website to the repo's GitHub Pages branch.
