# Typical Interview Questions Answered In Elixir

## Introduction



This repo explores common software <ruby>interview questions<rt>hazing rituals<rb></ruby> and
provides one or more approaches to solving them in Elixir.

I don't endorse actually conducting interviews that rely on live coding assessments. But
being able to pattern match the problems themselves to a reasonably defensible solution is
an useful skill; if nothing else, it means that when you're confronted with a problem, you'll
be able to remind yourself of what available algorithms and patterns to look up.

For problems you actually face on a regular basis, the solutions will either eventually become 
things you do more or less based on muscle memory, or you'll write some higher-order abstractions
so that you don't have to solve that exact problem again.

Every developer faces a different subset of problems on a day-to-day basis, with a minority of
us focused on nuanced algorithms, the vast majority of us trying to translate complex business
logic into a reasonably readable, maintainable implementations.

## Using this repository

You can clone this repository using:

```bash
git clone git@github.com:JasonTrue/ex_interview_questions.git
```

I'm leveraging a feature of Elixir inspired by Jupyter Notebooks
and Swift playgrounds called Livebook.

The files in this repository are in a slightly modified
version of Markdown that Livebook renders.

I'm making the assumption that you have a place you can
run Elixir and Livebook.

To install Elixir, follow this guide:

[Installing Elixir](https://elixir-lang.org/install.html)

To install Livebook, once you've installed elixir:

```bash
mix escript.install hex livebook
```

Alternatively, if you don't want to install Elixir locally,
you can run a docker container or launch an instance on [Fly.io](https://fly.io/launch/livebook)

You can find more guidance on [the Livebook web page](https://livebook.dev/)

## Notebooks

I'm planning to structure this as a group of mostly-self-contained notebooks. Eventually,
I'll hope to organize this into several notebooks covering different categories of problems.

Here's a list of the ones I've written so far:
[Notebook](notebook.livemd)
