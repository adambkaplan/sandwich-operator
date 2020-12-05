# Step 0: Initialize the project

To get started with operator-sdk:

- Download [operator-sdk](https://sdk.operatorframework.io/docs/installation/install-operator-sdk/).
  This example is generated with version 1.2.0
- Initialize the project via the `operator-sdk init` command. For this operator the following
  arguments were used:
  - `--domain`: adambkaplan.com
  - `--repo:`: github.com/adambkaplan/sandwich-operator

### Step 0a: Update the boilerplate

Operator-sdk generates a boilerplate file to generate license information on all code. Update the
boilerplate to add the appropriate copyright and notice. If you don't know which license to choose, 
[choosealicense.com](https://choosealicense.com/) can help you determine what is best for you.

This project uses the MIT License, therefore I updated the `hack/boilerplate.go.txt` with my
copyright and [SPDX License Identifier](https://spdx.org/licenses/):

```
/*
Copyright Adam B Kaplan

SPDX-License-Identifier: MIT
*/
```

For your project, enter the appropriate copyright and SPDX license identifier. Next, copy the
boilerplate into the `main.go` file, replacing the original generated boilerplate.
