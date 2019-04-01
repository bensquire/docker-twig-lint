# docker-twig-lint

A docker image that allows us to run [asm89/twig-lint](https://github.com/asm89/twig-lint) which is a library designed to validate the compilability of twig templates.

Ideal for continuous integration pipelines.


## Running

    docker run -v $PWD:/app bensquire/twig-lint lint /app/src/App/templates
    
Where $PWD is the current working directory and ./src/App/templates contains the twig templates.
