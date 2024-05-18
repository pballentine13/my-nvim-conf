# My nvim dev enviroment for working with python/flask
Based on the tutorial series from [typecraft](https://www.youtube.com/watch?v=zHTeCSVAFNY&list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn)

The leader is set to spacebar

Clone this to repo to *~/.config/nvim/* to try it out. *Don't forget to back up your config first.*

##### For best results, install a font from nerdfonts for your terminal. 

\<C-x\>o to code complete

Invoke :Mason and install black and isort for python formatting/linting

### Current LSPs
- Python
- HTML
- CSS
- SQL
- YAML
- LUA

### Custom Commands for Telescope 
- \<leader\>ff for fuzzy find
- \<leader\>fg for live grep
- \<leader\>fb for buffers
- \<leader\>fh for help tags

### Custom Commands for None-Ls
- \<leader\>gf for formatting, currently using black and isort for python as well as stylua for lua.

### Custom Commands for Neo-Tree
- \<C-n\> to open file tree on left

### Custom Commands for Code Completing
- \<C-b\> to scroll docs up
- \<C-f\> to scroll docs down
- \<C-Space\> to complete
- \<C-e\> to abort
- \<CR\> to confirm
