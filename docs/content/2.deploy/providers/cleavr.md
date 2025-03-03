# Cleavr

**Preset:** `cleavr` ([switch to this preset](/deploy/#changing-the-deployment-preset))

Nitro provides a built-in preset to generate output format compatible with [Cleavr.io](https://www.cleavr.io/).

## Set up your web app

In your project, set Nitro preset to `cleavr`.

```
export default {
  nitro: {
    preset: 'cleavr'
  }
}
```
Push changes to your code repository.

**In your Cleavr panel:**

1. Provision a new server
2. Add a website, selecting **Nuxt 3** as the app type
3. In web app > settings > Code Repo, point to your project's code repository

You're now all set to deploy your project!
