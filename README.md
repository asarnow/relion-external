# relion-external
Programs for Relion's "External" job interface.

`relion_tomo_ali_stack` will create *binned* aligned stacks

`relion_tomo_tomo3d` will use tomo3d to reconstruct aligned tilt series.
The 2015 version of tomo3d will be run directly. The 2023 has a restriction in place
that prevents it from being run by a Python script. In that case use `--script` to
output a bash script you can execute yourself.
