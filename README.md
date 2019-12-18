To use these zshrc files, just run the install.sh script.  

    ./install.sh

This will create a new ~/.zshrc file that will automatically load up the zshrc files in this directory.


Files in this repo:

- zshrc_base - the base zsh aliases and setup of things like antibody zsh plugins and fzf fuzzy searching that are generally useful
- zsh_options - sets up zsh values (such as globbing)
- zfunc - zshell functions for autocompleting different things
- purepower_prompt - the shell prompt with things tweaked as I like them
- zsh_plugins.txt - antibody zsh plugins that will get run for things like autocompletion

Files not in this repo, but that are created by `install.sh`:

- nonshared-zshrc/zshrc - not checked in
  - holds things that are secrets or not generally useful to other users
- nonshared-zshrc/<HOSTNAME> - not checked in
  - things that should be run just for this host, useful when sharing a zsh setting between multiple computers
  - you'll have one of these per machine you use your zsh settings on
