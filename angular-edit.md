# Angular CLI Command List

This document provides a complete list of commands used in Angular CLI.

## Table of Contents

- [Installation](#installation)
- [Check Versions](#check-versions)
- [Creating an Angular Application](#creating-an-angular-application)
- [Serving an Angular Application](#serving-an-angular-application)
- [Generating Components and Other Artifacts](#generating-components-and-other-artifacts)
- [Managing Dependencies](#managing-dependencies)
- [Updating Angular](#updating-angular)
- [Additional Commands](#additional-commands)
- [Cleanup](#cleanup)

## Installation

npm install -g @angular/cli               # Install Angular CLI globally

## Check Versions

npm -v                                      # Get npm version
node -v                                     # Get Node version
ng version                                  # Get Angular version
jasmine -v                                  # Get Jasmine version
karma --version                              # Get Karma version


## Creating an Angular Application

ng init                                     # Initialize a new application in current directory
ng new <app-name>                           # Create a new application in a new directory

## Serving an Angular Application
ng serve                                    # Serve the Angular application


### Generating Components and Other Artifacts
## Generate a Component

ng generate component <component-name>     # Generate a new component
ng g c <component-name>                     # Alias for generating a component


## Generate Other Artifacts

ng generate class <class-name>             # Generate a new class
ng g cl <class-name>                        # Alias for generating a class

ng generate directive <directive-name>      # Generate a new directive
ng g d <directive-name>                     # Alias for generating a directive

ng generate enum <enum-name>                # Generate a new enum
ng g e <enum-name>                          # Alias for generating an enum

ng generate module <module-name>            # Generate a new module
ng g m <module-name>                        # Alias for generating a module

ng generate pipe <pipe-name>                # Generate a new pipe
ng g p <pipe-name>                          # Alias for generating a pipe

ng generate service <service-name>          # Generate a new service
ng g s <service-name>                       # Alias for generating a service


## Managing Dependencies

npm run prepare                              # Prepare the project
npm run start                                # Start the project
npm install                                   # Install dependencies
ng update                                     # Update Angular
npm update                                    # Update npm packages


### Updating Angular
## Steps to Update Angular Version

ng update @angular/core@<version> @angular/cli@<version> --allow-dirty  # Update specific version
npm install                                                               # Install dependencies
git commit -a -m "Upgrade to the latest version of Angular <version>"     # Commit changes


## Update to the Latest Angular Version

npm uninstall -g @angular/cli                   # Uninstall global Angular CLI
npm cache clean --force                           # Clean npm cache
rm -rf node_modules                               # Remove node_modules
npm install -g @angular/cli@latest                # Install the latest Angular CLI
ng update @angular/cli @angular/core              # Update Angular
ng update --all --force                            # Force update all packages


## Additional Commands

ng help                                          # Get help in the terminal
ng new project-name                               # Create a new project
ng new project-name --skip-install                # Skip installing external dependencies
ng build                                         # Create a build
ng build --prod                                   # Create a production build
ng test                                          # Run test cases
ng e2e                                           # Run end-to-end tests
ng doc                                           # Open Angular documentation


## Cleanup

rm -rf node_modules                               # Remove node_modules
npm uninstall --save-dev @angular/cli            # Uninstall Angular CLI

