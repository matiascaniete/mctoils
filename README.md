## Dependencies

- stow

## Installing

```sh
cd ~ && git clone https://github.com/matiascaniete/myscripts.git && cd ~/myscripts
```

## Modules

- __generic__
    - __btc__: get btc price from Nomics API.
    - __empty-trash__: empties the trash bin.
- __rasp__
    - __blink__: GIO led blink.
    - __chsites__: Checks domains responses codes to be 200.
    - __gen__: number generator.
    - __led__: changes the pin status of GIO.
    - __seg__: prints text into seven segments display thru GIO.

## Activating modules

```sh
stow <module_name>
```

## Deactivating modules

```sh
stow -D <module_name>
```
