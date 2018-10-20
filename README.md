# Protean Examples

New users are advised to see both Petstore projects for a codex and sim reference.

Other examples are optional.

## Petstore Default - reference codex

Contains a well documented fully featured codex.

```bash
protean doc --f petstore-default/petstore.cod.edn
protean sim --d petstore-default
```

## Petstore Sim - reference sim

Adds a sim extension to change Protean's default server behaviour.

```bash
protean doc --f petstore-sim/petstore.cod.edn
protean sim --d petstore-sim
```

## Text Adventure - stateful sim

A simple *multi* player text adventure game with a REST API interface.

Walk around in, look at and interact with a stateful world.

Game state is persisted to file via [enduro](https://github.com/alandipert/enduro) and loaded on server startup.

```bash
protean doc --f text-adventure/textad.cod.edn
protean sim --d text-adventure
```
