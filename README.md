# tasty-commits

> :lollipop: Simple commit message convention for easily digestible history streams

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

- :seedling: `:seedling:` initial or early project commits
- :anchor:`:anchor:` early scaffolding work for a specific feature
- :art: `:art:` working on or completing a general feature anywhere in the stack
- :tv: `:tv:` working on the user interface or front-end (stylesheets, aesthetic changes, layouts, etc.)
- :satellite: `:satellite:` working on the API or back-end, or integration with another API
- :cd: `:cd:` working with video, images, music, fonts, etc.
- :lock: `:lock:` permissions, authorization, authentication, user sessions
- :moneybag: `:moneybag:` anything related to payments, subscriptions, trials, pricing models, or financing
- :cloud: `:cloud:` deploy scripts, continuous integration, networking configurations, proxies, DNS, etc.
- :wrench: `:wrench:` updates to configuration, data population, build scripts, environment setup scripts, etc.
- :construction: `:construction:` working on a critical or invasive feature
- :bug: `:bug:` working on fixing or completed fixing a bug
- :rocket: `:rocket:` optimization tweaks
- :sparkles: `:sparkles:` general cleanup (linter appeasement, stale comments, repairing broken windows, etc.)
- :scroll: `:scroll:` documentation, wiki, comments, docstring and general text updates
- :bulb: `:bulb:` adding useful content or links to assist others 
- :microscope: `:microscope:` test suite additions or updates
- :package: `:package:` updates to dependencies (Maven, NPM, Mix, etc.)
- :truck: `:truck:` migrating code or renaming files
- :checkered_flag: `:checkered_flag:` functional but likely unclean checkpoint for a difficult or large feature
- :see_no_evil: `:see_no_evil:` adding technical debt to quickly resolve a problem
- :sweat_drops: `:sweat_drops:` code is in a state of instability due to an enigmatic problem
- :boom: `:boom:` removing code, files, or data
- :ok: `:ok:` merge conflict resolution(s)
- :envelope: `:envelope:` updates to email templates or content
- :snowflake: `:snowflake:` i18n/l10n, partnerification or white labeling changes

## Combinations

Combining emojis can be a great way to either increase message specificity or to support a new type of message that's unique to your own application / workflow.

Here are some common scenarios where combining can be very useful:

 - `:microscope: :bug: fixed a broken test`
 - `:anchor: :construction: scaffolding work for a critical feature`
 - `:wrench: :rocket: configuration change that optimizes the application`
 - `:scroll: :bug: fixed a typo in the documentation`
 - `:satellite: :package: added a new third-party dependency to the API"`
 
There are of course an endless number of scenarios where this can be useful, so please feel free to contribute to this list when you find yourself using novel combinations.

### Conflicts

One could argue that certain combinations inherently conflict, such as `:art:` and `:bug:`, but I believe that context is everything, and so I want to ensure that no assumptions are made about what contexts users will find themselves in. 

So there are no hard and fast rules regarding how you can/should combine emojis. My only suggestion is to be as consistent as possible so that everybody on your engineering team can benefit and pick up the process efficiently.

## Contributing

This one is probably as subjective as it gets, but I'm always open to suggestions and objectively discussing which emojis make the most sense.
I'm also interested in what other ways commits can be categorized, so please don't be shy!

## License

MIT
