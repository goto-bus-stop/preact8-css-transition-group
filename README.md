# preact8-css-transition-group

> This is a fork of `preact-transition-group` that explicitly depends on
> Preact 8 for use in [Uppy](https://github.com/transloadit/uppy), to address
> [#2226](https://github.com/transloadit/uppy/issues/2226),
> [#2227](https://github.com/transloadit/uppy/pull/2227) and
> [#2377](https://github.com/transloadit/uppy/issues/2377).
>
> You may want to use this in your Preact 8 widgets to prevent interference with
> a Preact X app.

A preact fork of [css-transition-group](https://github.com/react-component/css-transition-group), which was originally extracted from the React codebase itself. The overwhelming majority of the code was written by the lovely folks of the React team, so kudos to them!

This module may be of use to you if:

- you want to apply CSS transitions when adding or removing elements; or
- you are getting a "not found" error for `react/lib/ReactCSSTransitionGroup`
