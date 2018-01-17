## These build files can be built with the following command:
 ``` singularity build (container image name) (container build file)``` 
example: ```singularity build matlab singularitybuild_matlab```

This will provide an container image ready to be run and used

## A similar command is to build from a dockerhub container 
```singularity build (container image name) docker://(dockerhub location)```
For example to build a jupyter minimal-notebook container run the following ```singularity build jupyter_minimal.img docker://jupyter/minimal-notebook```

This can be used to build a local singularity image for a docker container.
