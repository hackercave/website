# we moved!

The name was cool until we started working with it. We quickly realized that many applications don't work well with these types of domains.We have now worked four months with various workarounds and Co. But we don't want to push this further, as workarounds are simply not suitable for a production environment.

The new domain is [retarded.systems] where the project and services will continue to run. Code and other things will remain accessible, but we will move to our own gitlab to have more control and to be more independent.

# website

![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/hackercave/website/Publish/master?style=flat-square)  ![Website](https://img.shields.io/website?style=flat-square&url=https%3A%2F%2Fwww.xn--hckerhhle-v2a7r.org%2F)

This project is based on [Hugo Highlights](https://github.com/schmanat/hugo-highlights-theme) which in turn is based on the HTML5Up template.

The template was fundamentally revised, the dynamics were extended and new colors were introduced. Also an extension for cookie information has been added to be in line with EU legislation. On the other hand, the contact form and Google Analytics were removed to be more data efficient.

## automated deployment

We won't be using Github forever, so the deployment exists once as Github and once as Gitlab CI/CD.

### Github

see the [./github/workflows/main.yml](https://github.com/hackercave/website/blob/master/.github/workflows/main.yml)

### Gitlab

see the [.gitlab-ci.yml](https://github.com/hackercave/website/blob/master/.gitlab-ci.yml)

## see in action

just clone the project and run `$ hugo server --disableFastRender` or go on our website.
