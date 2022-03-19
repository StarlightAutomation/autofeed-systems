# Contributing System Designs

Thank you for your interest in contributing to DIYAutoFeed! Your contribution may help home gardeners automate
their garden irrigation, which makes their lives easier and their plants happier!

Since every system is different, the guidelines for contributions are somewhat loose. The general idea is to
provide a structure for contributed systems that will be consistent and easy to follow across the entire
repository.

## Adding your System
Every system design is stored within a subdirectory of this repository. To add your system, you should create
a new subdirectory alongside all the others.

Your directory structure should look something like this:
```
autofeed-systems/ # root
- system-1/ # existing system
- my-new-system/ # your new system docs
  - images/ # folder where images are stored
  - README.md # your documentation
```

Each system directory **must** contain a `README.md`. If your documentation makes use of images, you should
include an `images/` folder within your subdirectory.

## Required Documentation Structure
Documentation should be structured consistently. The following format should be followed by all system docs:
```
# Autofeed System: <the name of your system>

* **Budget:** <the cost/range of the system build>
* **Capacity:** <the capacity of the reservoir>
* **Base Controller:** <what computer or other device may be needed>

### About

<description of this system, any limitations, intended audience, etc>

---

## Item List
* List
* Of
* Items
* With
* Links

---

<the rest of your documentation>
<this may include wiring diagrams, pictures, etc>
```

* Budget: this is the total cost of your system. This value may be a range if there are optional components.
* Capacity: this is the total volume of the completed reservoir.
* Base Controller: optional, for example if your system uses a Raspberry Pi to automate the reservoir, enter
`Raspberry Pi` here.

#### About Section
The `About` section should include some information about who may be able to use this design and any other
details you'd like to provide. This section should also include whether or not your system is compatible with
the DIYAutoFeed Control software.

#### Item List Section
The `Item List` should be a bullet list of every item used in your system build. There should be links to purchase
each item if applicable. You do not need to include prices with this list, as prices fluctuate.

#### Documentation
The rest of the `README.md` will be your documentation. This should be detailed and be written like a tutorial,
as users will be following the instructions to build their own system.

## Pull Requests
Once your documentation is complete, you should open a Pull Request against this repository. Your PR will be
reviewed to ensure it follows these guidelines and is also appropriate for addition to this repository.
