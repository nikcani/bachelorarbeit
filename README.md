# Bachelorarbeit

## Titel

Vergleichende Analyse von
Laravel Admin-Panels mittels
Software Design Principles und Patterns
sowie prototypischer Implementierung

## Schriftliche Arbeit

https://github.com/nikcani/bachelorarbeit/releases

## Project Repo

https://gitlab.com/graw-radiosondes/sounding-console

# Research

## admin panels

> https://www.reddit.com/r/laravel/comments/wn8n8u/laravel_nova_vs_filament/

- I have worked with both and found Filament much easier to work with.
- Another problem I encountered with Nova is that customers without a technical background have a difficult time to work
  with Nova.
- Customising nova is really difficult.
- I've used both, and i still use both , but i prefer filament for it's community and easy customization, but i still
  use nova for vue projects.
- Nova is perfect if you don't need customization
- In my experience if you don’t need alot of custom work use Nova cause it’s easier and way faster to develop with.
- If you need something custom use filament.
- Filament is a lot easier to customize and extend. Mainly because you don’t have the compile Vue, etc.

> https://world.hey.com/akviby/filament-is-the-best-thing-that-happened-to-me-since-laravel-nova-2ab28a0f

> https://laracasts.com/discuss/channels/laravel/whats-the-best-free-laravel-admin-panel

### Livewire vs. Inertia.js

> https://laracasts.com/discuss/channels/inertia/inertiajs-vs-livewire-laravel

- Both aim to leverage the server as much as possible (routing, controllers, database access), while also avoiding full
  page refreshes. The difference is the views:
- Inertia: JavaScript templates (Vue/React/Svelte)
- Livewire: PHP (Blade) templates (minimal use of JS when needed)

> https://blog.logrocket.com/livewire-vs-inertia-js/

> https://www.byte5.de/blog/zeit-sparen-mit-laravel-livewire-und-inertia-im-vergleich/

> https://laravel-news.com/livewire-inertia

### The TALL Stack

> https://github.com/livewire/awesome-tall-stack#the-tall-stack

### Age: Laravel Nova

> https://nova.laravel.com/releases

- first release: 2018-08-22
- major versions: 4

### Age: filament

> https://github.com/filamentphp/filament/releases?page=34

- first stable release: 2021-03-02
- major versions: 2

### Packages

> https://filamentphp.com/plugins
> https://novapackages.com/

## foundation

### SOLID

> https://accesto.com/blog/solid-php-solid-principles-in-php/

- Single responsibility principle (SRP)
  - A class should have one, and only one, reason to change.
- Open/closed principle (OCP)
  - You should be able to extend a classes behavior, without modifying it.
- Liskov substitution principle (LSP)
  - Derived classes must be substitutable for their base classes.
- Interface segregation principle (ISP)
  - Make fine grained interfaces that are client specific.
- Dependency inversion principle (DIP)
  - Depend on abstractions, not on concretions.

### Boy Scout Rule

### PSR (PHP Standards Recommendations)

> https://www.php-fig.org/psr/

### KISS (Keep It Simple Stupid)

- Don't complicate the code.
- The code should be its documentation itself.
- Any new programmer on the team should be able to get into the project quickly.

### DRY (Don’t Repeat Yourself)

- Do not code using the Copy-Paste principle (there is no such rule).
- See that the same code repeats in several places? Extract code for a separate function.

### YAGNI (You Aren’t Gonna Need It)

- We should not write code “for the future”.
- Such code is not needed at the moment.

### GRASP (General Responsibility Assignment Software Patterns)

is a large set of rules about which I could write a separate article. These are the basic principles that we should
follow when creating object design and responsibility assignments. It consists of: Information Expert, Controller,
Creator, High Cohesion, Low Coupling, Pure Fabrication, Polymorphism, Protected Variations, Indirection.
