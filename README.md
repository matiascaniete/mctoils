## Dependencies

- stow

## Installing

### Clone repo

```sh
cd ~ && git clone git@github.com:matiascaniete/mctoils.git && cd ~/mctoils
```

### Add this line at the end of .bashrc or .zshrc file

```sh
source ~/mctoils/mct.sh
```

## Modules

- **generic**
  - **btc**: get btc price from Nomics API.
  - **check-cert**: checks domain ssl certificate expiration date.
- **rasp**
  - **blink**: GIO led blink.
  - **chsites**: Checks domains responses codes to be 200.
  - **gen**: number generator.
  - **led**: changes the pin status of GIO.
  - **seg**: prints text into seven segments display thru GIO.

## Activating modules

```sh
stow <module_name>
```

## Deactivating modules

```sh
stow -D <module_name>
```
