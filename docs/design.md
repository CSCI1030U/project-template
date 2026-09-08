# Design Document - <your project name>

Written for **Milestone 3**. One page is enough - it should let a reader who has never
seen your code understand how the pieces fit and why your algorithm is fast enough.

## Architecture

<How the system is put together: what runs where. Name your modules and say what each is
responsible for - the server, the client, the game/app engine, the storage layer, the
interface. A small diagram (even ASCII) helps.>

```
<client> ──socket──▶ <server> ──▶ <engine>
                        │
                        ▼
                    <storage>
```

## The protocol

<What messages the client and server exchange, and what each one means. A short table is
usually the clearest form.>

| Message | Direction | Payload | Effect |
|---------|-----------|---------|--------|
|         |           |         |        |

## Concurrency

<How the server serves more than one client at once - async tasks, threads, or processes -
and what state is shared between them. Say what you did about anything two clients can
touch at the same time.>

## Data structure

<Which data structure (stack, queue, BST, ...), where it is used, and why it is the right
one for that job.>

## Algorithm and Big-O analysis

<Which strategy - backtracking, divide-and-conquer, greedy, dynamic programming - and
which feature uses it.>

- **What it does:** <the problem it solves>
- **Complexity:** <O(...) for time, O(...) for space, and what n is>
- **Why that is acceptable here:** <the size of n in practice; any budget or cutoff you
  added>

<If you measured it, say so and give the numbers - a real measurement beats an estimate.>

## What we would do differently

<A few honest sentences. This is worth marks, and it is easier to write than it looks.>
