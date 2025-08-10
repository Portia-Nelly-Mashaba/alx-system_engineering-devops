# ALX System Engineering & DevOps

This repository contains shell scripting projects and exercises for the ALX System Engineering & DevOps program.

## 0x03-shell_variables_expansions

This directory contains shell scripts that demonstrate the use of shell variables and expansions.

### Scripts

- **0-alias**: Creates an alias where `ls` is aliased to `rm *`
- **1-hello_you**: Prints "hello" followed by the current Linux user's name
- **2-path**: Adds `/action` to the PATH environment variable

### Usage

Each script can be executed or sourced depending on the task requirements:

```bash
# For scripts that need to be sourced
source ./script_name

# For scripts that can be executed directly
./script_name
```

### Requirements

- All scripts must be exactly 2 lines long
- First line must contain `#!/bin/bash`
- No use of `&&`, `||`, `;`, `sed`, or `bc` is allowed
- Scripts must produce the correct output when executed or sourced 