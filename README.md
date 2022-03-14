# redmoon

Goals for Redmoon:

- Everything is Modularized, Packages should be seperation of concerns, bloat should be extra packages.
- Everything has native Injection Support (Things should be injectable, you should be able to safely edit behavior by adding a singular line of code in a particular place.)
- Should be Usable and Tested.
- Should have Examples for Usage that shows working intended behavior.
- Should have documentation to avoid known development design traps.
- Should be coded in such a way to avoid development design traps.
- Should allow for CI/CD using Unity's Built-In Package Manager System (with potential add-ons).
- Document for used Packages

Macro Package for Red Moon Tooling

Red Moon is a developer tool set for integrated modular packages within Unity that allow for quick installing of common code for common development tasks.

Included So Far:
- Dependency Injector: A Lightweight Dependency Injection System for asynchronously connecting Providers to Clients. It includes additional features such as Singleton conversion and UniRx integration. (https://github.com/crazyjackel/redmoon-depInjector/)
