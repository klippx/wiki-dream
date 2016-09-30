# WikiDream

mix deps.get

mix escript.build

```shell
╭─mathias.klippinge in ~/src/wiki_dream on master✔ 16-09-30 - 9:43:55
╰─○ ./wiki_dream lion

The lion (Panthera leo) is one of the big cats in the genus Panthera and a member of the family Felidae.
The commonly used term African lion collectively denotes the several subspecies in Africa.
With some males exceeding 250 kg (550 lb) in weight, it is the second-largest living cat after the tiger.
Wild lions currently exist in sub-Saharan Africa and in India (where an endangered remnant population resides in Gir Forest National Park).
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `wiki_dream` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:wiki_dream, "~> 0.1.0"}]
    end
    ```

  2. Ensure `wiki_dream` is started before your application:

    ```elixir
    def application do
      [applications: [:wiki_dream]]
    end
    ```
