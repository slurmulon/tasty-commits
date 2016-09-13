# tasty-commits

> :lollipop: Simple commit-message convention for easily digestible history streams

---

As a visual person, I find it difficult to read through large commit history logs in binary color schemes (i.e. black / white).
In order to improve readability and understandability of my commit history I started prefixing my messages with emojis 
in a consistent manner. Over the years I've made this convention a habit and find it hard to live without, so I figured 
I'd document the idea to see if others find it useful, too.

## Convention

Following the message rules described in the following section, simply prefix your commit messages like so:

`:EMOJI: my commit message`

That's it. Now when you read through your commit history it will be much easier to identify the general flow of your work, which
helps for trackability, recollection, debugging, and fun! :neckbeard:

## Messages

- :seedling: `:seedling:` initial/early commits
- :art: `:art:` working on or completing a general feature
- :construction: `:construction:` working on a critical or invasive feature
- :bug: `:bug:` working on fixing or completed fixing a bug
- :wrench: `:wrench:` updates to configuration, data population, build scripts, deploy, etc.
- :package: `:package:` updates to dependencies (Maven, NPM, Mix, etc.)
- :envelope: `:envelope:` updates to email templates / content
- :rocket: `:rocket:` optimization tweaks
- :sparkles: `:sparkles:` general cleanup
- :scroll: `:scroll:` documentation, wiki, docstring and general text updates
- :microscope: `:microscope:` test suite updates
- :truck: `:truck:` migrating code or renaming files
- :checkered_flag: `:checkered_flag:` functional but likely unclean checkpoint for a difficult or large feature
- :see_no_evil: `:see_no_evil:` adding technical debt to quickly resolve a problem
- :sweat_drops: `:sweat_drops:` code is in a state of instability due to an enigmatic problem (typically trying to address the problem)
- :boom: `:boom:` removing code, files, or data

## Contributing

This one is probably as subjective as it gets, but I'm always open to suggestions and objectively discussing which emojis make the most sense.
I'm also interested in what other ways commits can be categorized, so please don't be shy!

## Ideas

- Create more icons to help distinguish between front-end and back-end work
- Allow up to 2 emojis to be used in order to improve specificity

## License

MIT
