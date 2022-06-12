# nodeproj
Bash script that creates a node project below the current working directory. Supports GitHub uploads, and dynamic creation for whatever kind of project you are working on

## Installation
### Windows
Add wherever you are storing `nodeproj` to your global path.

### Linux/Mac
Add `nodeproj` to the `/usr/local/sbin` section OR
Add where `nodeproj` is stored to the path via `export PATH="yourpath:$PATH"`

Restart for changes to take effect.

## Usage
`nodeproj` will run baseline with defaults, by naming the project "Project", then proceeding to create the file structure and necessary npm packages for a quick simple server. Defaults can be overridden via arguments, use `nodeproj -h` to get the help screen.
