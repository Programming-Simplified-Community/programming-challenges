# Info

Consolidated place to manage multiple repository releases. Each repo will generate a docker image on release. Ideally, 1 repo per language. 

To prevent people from just easily reading our tests, those repos are private.

-----

## As a `Programming Simplified Community` contributor if you clone this repository you will need to excute the following commands

```bash
git clone --recurse-submodules https://github.com/Programming-Simplified-Community/programming-challenges.git
cd programming-challenges
```

Because we use a submodule pointing to other repos, if you wish to update the repos to their latest run:
```bash
git submodule update --remote
git add nameofrepohere
git commit -m "updated repo reference"
git push origin
```

`nameofrepohere` represents the repository, or repositories whose references got updated.
