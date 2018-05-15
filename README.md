# dmk - Docker Make


## What

dmk is a helper tool for quick iteration of building and testing Dockerfiles.

Example workflow:

    # dmk
    ...build output...

    # dmk run
    ...your container starts up...

    # dmk push
    ...image is pushed to the registry...



## Usage

Copy the .dmk.EXAMPLE file into your project as .dmk alongside your Dockerfile and update the image name and ports.


    # dmk help
    dmk must be run in a directory with a .dmk file
    Available commands are:
      help - This text
      build - Build the image (default if no command specified)
      run - Run the image 
      run X - Run the image with X support
      push - Push the image to the registry
      pull - Pull the image from the registry
      clean - Remove the image locally
      squash - Flatten the container image layers into a single layer.
               Useful to show how terrible you write Dockerfiles ;)



## Get a copy

First-time installation:

    curl -SL https://github.com/Buhrietoe/dmk/raw/master/dmk -o dmk

Copy the binary to your $PATH and make it executable.



## Contributing

Pull requests welcome
