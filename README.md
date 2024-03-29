# Wozu 🤔

<img src="wozu.png" width="700">

## Basic idea

Everything in life can be decomposed into tasks that depend on each other.

Accordingly, in Wozu you can:

- Link tasks together
- Focus on specific tasks (Kanban)
- Embed URLs into tasks

These limited features encourage fast iteration and the exploration of ideas, not tooling.

## How to use

1. Supply the following:
   
|File|Example|
|---|---|
|`graph.txt`|`a --> b`<br>`b --> c`|
|`todo.txt`|`Want to do:` (green)<br>`c`<br>`Will do:` (blue)<br>`b`<br>`Doing:` (red)<br>`a`|
|`links.txt`|`a: somesite.com.com/someplace`|

2. Run `python server.py` to start the UI.
3. Iterate! Changes render immediately.

## Some tips

- Adjust until the graph looks pretty. This will force you to draw useful connections.
- Use separate files to track different things, or put everything in one big graph.
- You can use version control (Git) to back up your changes!
- You can embed graphs within each other. [TODO]

## On the name

Wozu is German for "for what", or "in order to." 

Plus it sounds nice: _woe-tsu_.
