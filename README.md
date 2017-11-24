# vim-projectionist-elixir

Very simple vim file navigation for Elixir projects.

See [here](https://github.com/arcseldon/vim-projectionist-elixir) for the
source

This plugin supplies quick-nav links for Elixir projects.  It gives commands to
jump quickly between an Elixir source file and it's associated test.

This plugin is going to work with `mix` projects where source files are stored
under the `lib` directory and corresponding test files are stored under `test`.
Will work with Phoenix projects where the `web` directory is moved under `lib`.

Depends on Tim Pope's
[vim-projectionist](https://github.com/tpope/vim-projectionist) plugin.  

`:A` - open the 'alternate' file

`:AS` - open the 'alternate' file in a split window

`:AV` - open the 'alternate' file in a vertical split window

`:AT` - open the 'alternate' file in another tab
