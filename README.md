**Steps to Reproduce**

<!-- If you can, provide a link to a public repository which contains the files necessary to reproduce this. -->

1. Run `yarn install --audit` at the root
2. Run `yarn audit` at the root
3. `cd packages/a`
4. Run `yarn install --audit` inside package
5. Run `yarn audit` inside package
