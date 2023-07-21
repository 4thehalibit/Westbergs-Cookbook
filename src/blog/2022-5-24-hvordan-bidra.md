# How to Contribute

If you want to add a recipe yourself and then create a pull request, you can do so by following these steps.

## Fork

Create a [fork](https://github.com/engeir/simple-recipes-cookbook/fork) of the repository.

## New Recipe

A new recipe can be added by creating a new file in an existing or new folder.

New files _must_ have the file extension `.md`, and the filename must be without spaces (use hyphens, `-`) and only in lowercase, also known as [kebab case](https://en.wikipedia.org/wiki/Letter_case#Kebab_case).

Let's say you want to add a recipe for buns. You would create a new file in the `baking` folder and name it something like `fresh-buns.md`. Copy the content from [TEMPLATE.md](https://github.com/engeir/simple-recipes-cookbook/blob/main/TEMPLATE.md?plain=1) into `fresh-buns.md` and edit it according to your preferences.

The file structure you want to add files to will look something like this, before and after:

|||Before
```text
.
├── IMAGE.md
├── LICENSE
├── README.md
├── TEMPLATE.md
├── retype.yml
└── src
    ├── _includes
    │   └── head.html
    ├── bakst
    │   ├── bananpannekaker.md
    │   └── index.yml
    ├── blog
    │   └── 2022-5-24-hvordan-bidra.md
    ├── hovedretter
    │   ├── index.yml
    │   └── tomat-paprika-suppe.md
    ├── index.md
    └── static
        └── pasta-a-la-vodka.webp
```
|||After
```text
.
├── IMAGE.md
├── LICENSE
├── README.md
├── TEMPLATE.md
├── retype.yml
└── src
    ├── _includes
    │   └── head.html
    ├── bakst
    │   ├── bananpannekaker.md
    │   ├── ferske-boller.md
    │   └── index.yml
    ├── blog
    │   └── 2022-5-24-hvordan-bidra.md
    ├── hovedretter
    │   ├── index.yml
    │   └── tomat-paprika-suppe.md
    ├── index.md
    └── static
        └── pasta-a-la-vodka.webp
```
|||
