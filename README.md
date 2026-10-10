# interactor-aria-simple-travel

A travel planning domain in Elixir, where people walk or take a taxi between places under time and cash limits.

## What it is for

It is a worked example for the hybrid temporal planner. Walking and riding take time in proportion to distance, calling a taxi and paying are instant, and the planner picks the mode a traveller can afford. The domain, its actions and methods, and a set of example problems are in `lib/`.

## Build and test

```sh
mix deps.get
mix test
```

## Licence

MIT. See [LICENSE](LICENSE).
