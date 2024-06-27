<h1 align="center">Erlang Ecosystem for Elixir devs </h1>
<p align="center">
  <img src="https://github.com/the-elixir-developer/nautilcal_chart/assets/17634377/e0b8fd65-8e50-442b-aab2-cba94b504b49" width="35%">
</p>

## List of content

- [Design patterns in Elixir](#design-patterns-in-elixir)
- [Observability](./#observability)

## Design Patterns in Elixir

`Design patterns in Elixir - Graphic Recording`[^2]
<img src="https://github.com/the-elixir-developer/erlang_ecosystem/assets/17634377/a639d516-6f90-41ec-a367-c4602c84cb86" width="50%" align="right">

`Elixir`

- Elixir anti-patterns to guide the community
  - [Code-related](https://hexdocs.pm/elixir/main/code-anti-patterns.html)
  - [Design-related](https://hexdocs.pm/elixir/main/design-anti-patterns.html)
  - [Processes-related](https://hexdocs.pm/elixir/main/process-anti-patterns.html)
  - [Meta-programming](https://hexdocs.pm/elixir/main/macro-anti-patterns.html) 
- A `pattern` describes a problem.
- Book: Design paterns elements of reusable object-oriented software.
- Objects are about: `behaviour`, `mutability` and `state`.
- Design Patterns in OO are solved by functional programming: `mediator`, `facade`, `startegy`, `interpreter`, `adapter`, `decorator`, `proxy`, `observer`.

## Observability

`Observability at scale - Graphic Recording`[^1]
<img src="https://github.com/the-elixir-developer/nautilcal_chart/assets/17634377/1dff9842-6362-429f-a85b-f7da670042b0" width="50%" align="right">

`Erlang` `Elixir`

> Observability is the measure of how well a system's internal states can be inferred from its external outputs. It's also the ability to address failures before they happen. Observability needs to be designed.

- Observability needs to be designed.
- It's about past, present and future: `logs`, `metrics` and `alarms.`
- Design is the key.
- `Logging`
  - Detect failures and errors
  - What happened in your project?
  - Design your logs.
  - Avoid mess.
  - Record complimentary information about the errors.
- `Metrics`
  - Performance indicators in live systems.
  - Metrics are not free.
  - Types: business, product, and system.
  - Management and development should collaborate together.
  - Design your metrics.
  - Avoid vendor lock-in.
  - Understand your system.
  - Keep your metrics tidy.
- `Alarms`
  - Come from logs or metrics. 

### Notes and references

[^1]: Observability at scale, Code BEAM Europe Berlín 2023, Natalia Chechina. Drawings by @carlogilmar @visual_partner.
[^2]: Design Patterns in Elixir, ElixirConf EU 2024, Jose Valim. Drawings by @carlogilmar @visual_partner.

