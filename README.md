# STEAMDBnexus

A website about Steam games: what a game is, how many people are playing it, and
how that has moved over time. Think SteamDB with far less clutter.

Built from public Steam and steamcharts data into plain static pages that need
no JavaScript to read.

## This repository is output, not source

Everything here is **generated**. The pages are built by a separate toolchain
that is not published, and this repository holds only what a browser actually
fetches — the index, the per-game pages, and nothing else.

**Do not edit anything here by hand.** The next build overwrites it silently:
no error, no warning, the edit is simply gone.

## What is on the pages

Every figure is either something a source published or something a person
measured, and it carries the time it was fetched. Player counts and rankings are
Valve's own; player history is steamcharts' sampling, and the pages say so.

Nothing here is a recommendation, a rating, or a score invented by this site. A
value that is missing stays missing rather than being filled with a guess.
