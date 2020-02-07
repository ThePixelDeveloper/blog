---
title: "FOSDEM 2020 Review"
date: 2019-02-04
description: "My first time attending FOSDEM. Here's my thoughts on the two day conference."
---

I'd known about FOSDEM for a long time, but never managed to organise myself
into going. This year I'd got my eggs in order and got myself over there.

Before we move on, here's a description of what FOSDEM is:

> FOSDEM is a two-day event organised by volunteers to promote the
> widespread use of free and open source software.

Source: [fosdem.org](https://fosdem.org/2020/about/)

---

## Day 1

Because there's so many talks (871 to be precise) I needed to find a way
to organise myself before the paralysis of choice set in. There's one app called [FOSDEM-ORG](https://apps.apple.com/au/app/fosdem-org/id941904933)
which allows you to favourite talks and see what's coming up. Good enough
for two days.

---

### Talk 1: Introducing Tanka

**Presenters:** [Malcom Holmes](https://fosdem.org/2020/schedule/speaker/malcolm_holmes/) and [Tom Braack](https://fosdem.org/2020/schedule/speaker/tom_braack/)

Grafana's [Tanka](https://github.com/grafana/tanka) aims to solve the problem of
repetitive Kubernetes manifests, by combining [Jsonnet](https://jsonnet.org/) to create
re-usable Kubernetes components and a Terraform-esque command line tool to `diff` and `apply` deployment changes. Practically
speaking ... typing less to get the same result.

An interesting project, but looks to be competing with [Kustomize](https://kustomize.io/)
with some command line tooling.

---

### Talk 2: The Selfish Contributor Explained


**Presenter:** [James Bottomley](https://fosdem.org/2020/schedule/event/selfish_contributor/)

---

### Talk 3: Ephemeral Environments For Developers In Kubernetes

**Presenter:** [Jeff Knurek](https://fosdem.org/2020/schedule/speaker/jeff_knurek/)

This talk was an advertisement for a tool called [Armador](https://github.com/travelaudience/armador).
Positioning itself as the "Docker Compose" for Kubernetes, it finds a gap
between other utilities such as [garden.io](https://garden.io/), [Acyl](https://github.com/dollarshaveclub/acyl) and [Helmfile](https://github.com/roboll/helmfile). To go into a bit
more detail; it's got a dependency resolver that allows you to work on
services in isolation while pulling in dependencies of dependencies.

---

### Talk 4: Fixing the Kubernetes clusterfuck


**Presenter**: [Kris Nova](https://fosdem.org/2020/interviews/kris-nova/)

Gives a brief overview of [Falco](https://falco.org/), a Kubernetes threat
detection engine. Honestly, this one went over my head and I can't possibly
explain how it works better than what's on their own website. Good for
people operating Kubernetes clusters.

---

### Talk 5:



