# Stackbit Ampersand Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.86.

Stackbit Ampersand Theme original README is located [here](./README.theme.md).

The content of this site is managed by DatoCMS.

# Running Your Site Locally

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch site contents from DatoCMS:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5e8caab2586b80001418a2d7

1. Build the site and start the Hugo server with drafts enabled

        hugo server -D

1. Browse to [http://localhost:1313/](http://localhost:1313/)
