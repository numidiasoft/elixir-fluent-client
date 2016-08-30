Fluent Client
=============

Minimalistic fluentd client

Add this to your mix.exs
========================

```ex
{:fluent_client, git: "https://github.com/numidiasoft/elixir-fluent-client.git"}
```

Send a message to your TCP server
=================================

```ex 
Fluent.start(FluentClient, [host: host, port: port])
Fluent.send(FluentClient, "tag", %{message: "Hello"})
```
