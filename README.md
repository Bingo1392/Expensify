# Expensify

Store and filter your expenses. Small app without styles (yeah, it's ugly). It was created only for learning purposes.

Still exploring... (in progress)

## What i learned?

- React router
- Redux basics

## Requirements

- Node 8
- x86_64 architecture. If you are using Mac with M1 chip you have to run the terminal with x86_64 instructions. You can add these two lines into your `.zshrc` file to be able to change architecture in your terminal:
    ```
    alias arm="env /usr/bin/arch -arm64 /bin/zsh --login"`
    alias intel="env /usr/bin/arch -x86_64 /bin/zsh --login"
    ```
  now when you run `intel` command in the terminal it'll switch to x86_64 architecture. With `arm` command you can go back to arm64 architecture.
