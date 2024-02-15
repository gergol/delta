# Delta git pager config

The config / themes for the [delta](https://github.com/dandavison/delta) git pager.

To use these themes, first include this file in your own gitconfig file:

```
[include]
     path = PATH/TO/delta/themes.gitconfig

Then, in your own gitconfig file, activate the chosen theme, e.g.

[delta]
    features = kingfisher
```

## Themes

Run `delta --show-syntax-themes --dark` or `delta --show-syntax-themes --light` to see the available themes.
