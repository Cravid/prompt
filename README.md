# prompt
CLI tool to show a y/n prompt

Test case to show how to use

```bash
#!/bin/bash

prompt "Do you like dogs?"

if [ $? -eq 0 ]; then
    echo "Cool"
else
    echo "How dare you"
fi

exit 0
```