# Saluca roadmap

This is where Saluca's product direction is decided in the open.

Feature requests reach us **anonymously** through the products themselves... an
agent asks its Saluca tool to file one, and nothing about who asked is stored.
We group the requests we receive, and the ones we take forward appear here as
**change records**: one issue per direction, with our position and reasoning in
the thread.

**Endorse what you want.** A 👍 on a change record is a vote. You do not need an
account relationship with us to be counted, and you never have to read a
document to weigh in... the record says what it is in a sentence.

We do not publish raw submissions, and we never attach a name to one. What you
see here is what we chose to say out loud.

- **under-review**, we've seen the ask, no decision yet
- **planned**, we intend to do it
- **in-progress**, being built
- **shipped**, done
- **declined**, with the reason in the thread; disagreement is fine, we say why

Bugs go through support privately and do not appear here.

## Status

Maintained. As of 2026-10-22 there is one change record:
[#1, subject-facing context audit](https://github.com/saluca-labs/roadmap/issues/1), labelled `planned`.

## Install

Nothing to install: this repo is a README and its issues. You need a GitHub account to add a 👍 or comment.

## Quickstart

1. Open the [list of change records](https://github.com/saluca-labs/roadmap/issues).
2. Open one and add a 👍 reaction to the first post to endorse it, or comment with your reasoning.

## Usage

- **Find a product's records:** filter by its label, for example
  [`product:tiresias-zt`](https://github.com/saluca-labs/roadmap/issues?q=label%3Aproduct%3Atiresias-zt).
  The product labels are `product:asphodel-memory`, `product:mindsets`, `product:tiresias-zt`,
  `product:tiresias-watch` and `product:tiresias-report`.
- **Find records by stage:** filter by `under-review`, `planned`, `in-progress`, `shipped` or `declined`,
  for example [`planned`](https://github.com/saluca-labs/roadmap/issues?q=label%3Aplanned).
- **See what is most wanted:** [sort by 👍](https://github.com/saluca-labs/roadmap/issues?q=is%3Aissue+sort%3Areactions-%2B1-desc).

## Architecture

There is no code. Each change record is a GitHub issue opened by Saluca, with one stage label and one or
more product labels. The position and reasoning live in the issue body and thread; a 👍 reaction on the
first post is the vote.

## Citation

No archived record yet.

## License

No licence has been chosen for this repo yet, so no licence is granted beyond what GitHub's terms of service
allow.

## Links

- [Change records](https://github.com/saluca-labs/roadmap/issues)
- [saluca-labs/open-review](https://github.com/saluca-labs/open-review): public review of Saluca Labs research

_Last updated: 2026-10-22_
