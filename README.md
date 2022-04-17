## Dependencies

- stow

## Installing

### Clone the repo

```sh
cd ~ && git clone git@github.com:matiascaniete/mctoils.git && cd ~/mctoils
```

### Run the installer

```sh
cd ~/mctoils && bash ./install.sh
```

### Add this line at the end of .bashrc or .zshrc file

```sh
source ~/mctoils/mct.sh
```

## Modules

- **rasp**
  - **blink**: GIO led blink.
  - **chsites**: Checks domains responses codes to be 200.
  - **gen**: number generator.
  - **seg**: prints text into seven segments display thru GIO.

## Activating individual modules

```sh
cd ~/mctoils
stow <module_name>
```

## Deactivating modules

```sh
cd ~/mctoils
stow -D <module_name>
```
