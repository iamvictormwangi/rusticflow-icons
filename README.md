A lightweight icon library.

Example


```html

  <i class="icon feather activity"></i>

```

Change the color of the icon

```html

  <i class="icon feather activity white"></i>
  <i class="icon feather activity black"></i>

```

Change the size of the icon

```html

  <i class="icon feather activity extrasmall"></i>

  <i class="icon feather activity small"></i>

  <i class="icon feather activity medium"></i>

  <i class="icon feather activity large"></i>

  <i class="icon feather activity extralarge"></i>

```

Or you can easily change the sizes of the icons by
 using css property scale.

```html

  <i class="icon feather activity" style="scale: 1.35"></i>

  <i class="icon feather activity" style="scale: 5.35"></i>

```

Its better to include rusticflow-icons through cdn.

Usage with jsdelivr

```

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/rusticflow-icons@0.2.4/css/rusticflow-icons.min.css">

```

## Building from scratch

It relies on grass and rusticflow to build.

They are both rust tools that can be easily be installed
 through `cargo install`

Example

```

cargo install grass

```

```

cargo install rusticflow

```

Then build the project with `pnpm run dev`



