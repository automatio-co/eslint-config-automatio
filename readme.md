This is a config for eslint and prettier. We have multiple projects where we had to copy and paste same file over and over. This package will take care of the problem.

# Installation

Install eslint and the required config files,
```
npx install-peerdeps --dev eslint-config-automatio
```

Create a .eslintrc file in root of your project directory,
```
{
  "extends": [
    "automatio"
  ]
}
```