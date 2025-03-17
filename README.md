# Stylelint shared config to use with Prettier
Open Region Stylelint shared config with turned off rules that are unnecessary or might conflict with Prettier.

## Usage
Install package

```shell
npm install --save-dev @openregion/stylelint-config-prettier
```

Create `.stylelintrc.json` file with this content

```json
{
  "extends": ["@openregion/stylelint-config-prettier"]
}
```

> [!IMPORTANT]
> This config already includes `@openregion/stylelint-config`.
