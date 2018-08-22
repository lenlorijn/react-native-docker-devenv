#React Native Docker Compose Devenv


To work with this development environment please install and configure 
[Docker](https://docs.docker.com/install/) and 
[Docker Compose](https://docs.docker.com/compose/install/).

##Getting Started
To get started with a new React Native project run `./bin/rnd init`.
This will set up a new 
[create react native app](https://github.com/react-community/create-react-native-app)
with [typescript](https://www.typescriptlang.org/) enabled.

The app will be created in the `src` directory.
After the initial install I recommend you remove the .gitignore file and .git
directory. Currently this development environment is set up for just a single
project.
Comitting the development environment ensures you can customise it to the
projects needs.

##Running the development environment
After setting up your project, use `./bin/rnd up` to start the environment.
Make sure your phone and PC are on the same network, and scan the barcode.
