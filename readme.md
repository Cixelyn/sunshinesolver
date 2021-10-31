quick 'n dirty solver for sunshine heavy industries.

the game is good, [buy it now on steam](https://store.steampowered.com/app/1542810/Sunshine_Heavy_Industries/)

coming in second place in the leaderboard is no fun. thus, this git repository

## notes

costs last extracted from halloween patch (10/30-ish)
packed asar needs to be decompiled and then the obfuscated module needs to be run in order to generate the full `costs.json` via `yarn generate`.

## to use:

run [./solver.ipynb](solver.ipynb) w/ relevant constraints

requires everything in `requirements.txt`
Also needs GLPK binary as mixed-integer lintear programming solver via pyomo
