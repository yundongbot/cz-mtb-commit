# cz-mtb-commit

A commitizen adapter for mtb format, forked from cz-conventional-changelog.

## mtb commit message format

### Header

[{type}] {short description}

- `type`:
    - `feature`: A new feature;
    - `fix`: A bug fix;
    - `docs`: Documentation only changes;
    - `style`: Changes that do not affect the meaning of the code,like white-space, formatting, missing semi-colons, etc;
    - `refactor`: Code refactoring;
    - `upgrade`: Upgrade dependencies;
    - `test`: Adding missing tests;
    - `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation;
    - `feature`: A new feature;

- `{short description}`:

    Write a short, imperative tense description of the change.

### Body

Provide a longer description of the change.

### Footer

List any breaking changes or issues closed by this change.

## Usage

First, Install `commitizen` cli tools:

```
npm install -g commitizen
```

Next, initialize your project to use the cz-mtb-commit adapter by typing:

```
commitizen init cz-conventional-changelog --save-dev --save-exact
```

Now cdinto any git repository and use `git cz` instead of `git commit` and you will find the `commitizen` prompt.

[more information](https://github.com/commitizen/cz-cli)
