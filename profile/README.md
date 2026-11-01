<p align="center"><img src="ptyparty-logo.svg" alt="A purple terminal wearing a party hat, its screen making a green &gt;_&lt; face, with a pink streamer and a piece of gold confetti" width="160"></p>

<h1 align="center">ptyparty</h1>

Hi! Welcome to the `ptyparty`!

This is [@qxjit](https://github.com/qxjit) (a human) typing.

It can be a sad experience working with coding agents in the terminal these days, but
it doesn't have to be. We can make it a party instead!

Here are some (very experimental) tools that we are working on with copious agent
help to try to make it more enjoyable and productive. Each can be used successfully
on its own, but they work best together as a suite. Together, they let you run a Claude
session in the background that is aware of the other applications running alongside it. You
can do this for multiple tabs, with one Claude running per tab.

Like this:

![a qmux tab with quoll on the left, remax on the right, and native Claude docked below, asking a question through a popup](https://raw.githubusercontent.com/ptyparty/qmux/main/docs/qmux.gif)

This shows a layout in `qmux` that has `quoll` (a terminal markdown browser) on the left,
`remax` (a code review tool) on the right. Claude is running in the background and is prompted
directly via `qmux`, asks questions through `qmux` and interacts with `quoll` and `remax`.

So, here are the tools. These are considered *highly experimental*, and are changing very
quickly at the moment, so please keep that in mind. You don't have to use `qmux` to use
any of them either!

## The crew

| | | |
|---|---|---|
| <img src="https://raw.githubusercontent.com/ptyparty/qmux/main/docs/qmux.svg" alt="qmux logo" width="64"> | **[qmux](https://github.com/ptyparty/qmux)** | A terminal multiplexer that agents can interact with |
| <img src="https://raw.githubusercontent.com/ptyparty/quoll/main/docs/quoll.svg" alt="quoll logo" width="64"> | **[quoll](https://github.com/ptyparty/quoll)** | A markdown viewer that you can use to iterate on design with an agent |
| <img src="https://raw.githubusercontent.com/ptyparty/remax/main/docs/remax.svg" alt="remax logo" width="64"> | **[remax](https://github.com/ptyparty/remax)** | A code review focused editor that lets you review code diffs hunk by hunk |
| <img src="https://raw.githubusercontent.com/ptyparty/kowari/main/docs/kowari.svg" alt="kowari logo" width="64"> | **[kowari](https://github.com/ptyparty/kowari)** | A PostgreSQL client for the terminal designed to be used alongside an agent |

## Getting started

There's a README in each repo that you can follow for setup. Expect it to be rough right
now, as things are not polished.
