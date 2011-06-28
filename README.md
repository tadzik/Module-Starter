# Module::Starter - The easy way to start writing a Perl 6 Module

Module::Starter autocreates your metadata file, creates a git
repo and optionally asks you whether to create a new git repo
to push to on Github.

You must have github.token defined in your ~/.gitconfig for
the remote git repo to be created.

## Example usage

    module-starter --description="this is a short description of my module" Foo::Bar
