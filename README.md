# tasty-commits

> :lollipop: Simple commit message convention for easily digestible history streams

---

As a visual person, I find it difficult to read through large commit history logs in binary color schemes (i.e. black / white).

In order to improve readability and understandability of my commit history I started prefixing my messages with emojis 
in a consistent manner.

Over the years I've made this convention a habit and find it hard to live without, so I figured I'd document the idea to see if others find it useful, too.

## Convention

Following the message rules described in the following section, simply prefix your commit messages like so:

`:EMOJI: my commit message`

That's it. Now when you read through your commit history it will be much easier to identify the general flow of your work, which
helps for trackability, recollection, debugging, and fun! :neckbeard:

## Messages

- :seedling: `:seedling:` initial commits
- :anchor: `:anchor:` feature scaffolding
- :art: `:art:` general feature development
- :tv: `:tv:` user interface or front-end development
- :satellite: `:satellite:` API, back-end, or integration development
- :lipstick: `:lipstick:` styles, colors, sizes, positions, alignment
- :wrench: `:wrench:` configuration, settings, environment variables
- :construction: `:construction:` work-in-progress, unstable, unusable
- :bug: `:bug:` bugs, broken windows
- :fire: `:fire:` error and exception handling
- :vhs: `:vhs:` general scripts, task automation, code generation
- :microscope: `:microscope:` test suite additions or updates
- :performing_arts: `:performing_arts:` stubs, mocks and fixtures
- :zap: `:zap:` caching
- :rocket: `:rocket:` optimizations
- :sparkles: `:sparkles:` cleanup, lint, touch-ups
- :package: `:package:` packages, dependencies
- :factory: `:factory:` build scripts
- :truck: `:truck:` migrating code, data, files or database tables
- :checkered_flag: `:checkered_flag:` large/complex feature checkpoint
- :see_no_evil: `:see_no_evil:` adding technical debt
- :sweat_drops: `:sweat_drops:` enigmatic problems
- :boom: `:boom:` removing code, files, or data
- :ghost: `:ghost:` temporary or ephemeral changes
- :pill: `:pill:` experimental changes or implementations
- :ok: `:ok:` conflict resolutions
- :cd: `:cd:` media and static assets
- :electric_plug: `:electric_plug:` offline mode
- :lock: `:lock:` permissions, authorization, authentication, user sessions
- :cop: `:cop:` security features, improvements or fixes
- :moneybag: `:moneybag:` payments, subscriptions, trials, pricing models, financing
- :iphone: `:iphone:` media queries, device-specific changes
- :cloud: `:cloud:` networking, deploy, continuous integration
- :eye: `:eye:` monitoring, analytics
- :scroll: `:scroll:` documentation, wiki, comments, docstrings, general text
- :bulb: `:bulb:` assistive content, learning resources
- :envelope: `:envelope:` email templates or content
- :snowflake: `:snowflake:` i18n/l10n, partnerification, white labeling
- :hammer: `:hammer:` administration, moderation

## Combinations

Combining emojis can be a great way to either increase message specificity or to support a new type of message that's unique to your own application / workflow.

Here are some common scenarios where combining can be very useful:

 - `:microscope: :bug: fixed a broken test`
 - `:anchor: :construction: scaffolding work for a critical feature`
 - `:wrench: :rocket: configuration change that optimizes the application`
 - `:scroll: :bug: fixed a typo in the documentation`
 - `:satellite: :package: added a new third-party dependency to the API`
 - `:tv: :lock: :checkered_flag: finished integrating auth in the client`
 
There are of course an endless number of scenarios where this can be useful, so please feel free to contribute to this list when you find yourself using novel combinations.

### Conflicts

One could argue that certain combinations inherently conflict, such as `:art:` and `:bug:`, but I believe that context is everything and I want to ensure that no assumptions are made about what contexts users will find themselves in. 

So there are no hard and fast rules regarding how you can/should combine emojis. My only suggestion is to be as consistent as possible so that everybody on your engineering team can benefit and pick up the process quickly.

## Contributing

This one is probably as subjective as it gets, but I'm always open to suggestions and objectively discussing which emojis make the most sense.
I'm also interested in what other ways commits can be categorized, so please don't be shy!

## Roadmap

- [ ] Node API

## License

MIT
