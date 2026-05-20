# HelloServer

A minimalist, lightweight web server built in Elixir for learning purposes, using the `Plug` specification.

## How to Run

First, ensure you have Elixir installed. Then, download the project dependencies:

```bash
mix deps.get
```

To start the server and keep it running in your terminal, execute:

```bash
mix run --no-halt
```

The server will be up and running at: http://localhost:4000

To access a personalized message -> http://localhost:4000/users/your_name
