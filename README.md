# 37061

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Config migration PR title is "Migrate renovate config {{#if (equals packageFileDir '')}}{{else}}in /{{{ packageFileDir }}}/{{/if}}"

## Expected behavior

Config migration PR title should just be "Migrate renovate config" after parsing the template.

## Link to the Renovate issue or Discussion

<https://github.com/renovatebot/renovate/discussions/37061>
