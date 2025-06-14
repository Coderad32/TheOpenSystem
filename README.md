
# The Open System

The open system is a import statement that Id like to get working.

```perl

import system

use system

#!/bin/bash

while true; do
    echo "Main Menu"
    echo "0. Menu (Main)"
    echo "1. option goto"
    echo "2. option todo"
    echo "3. option route"
    echo "4. back file"
    echo "  exit"
    echo -n "Enter your choice (0-4 or exit): "
    read choice

    case $choice in
        0)
            echo "You selected: Menu (Main)"
            ;;
        1)
            echo "You selected: option goto"
            ;;
        2)
            echo "You selected: option todo"
            ;;
        3)
            echo "You selected: option route"
            ;;
        4)
            echo "You selected: back file"
            ;;
        exit)
            echo "Exiting. Goodbye!"
            break
            ;;
        *)
            echo "Invalid option. Please choose 0-4 or 'exit'."
            ;;
    esac
    echo
done

```


## Logic of program

- Perl 
- Shell
- Python
- keywords


> Created for "The Open System" Repo  year 2025
