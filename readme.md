# Starter
Starter for web development using native technologies.

![Starter](https://raw.githubusercontent.com/agragregra/starter/main/public/images/preview.jpg)
```
git clone https://github.com/wdmcourses/starter . && rm -rf trunk .gitignore .git readme.md
```

> Run with **Live Server**  
> "liveServer.settings.fullReload": true,

## Helpers

### font-weight:
```
100 - Thin (Hairline)
200 - Extra Light (Ultra Light)
300 - Light
400 - Regular (Normal)
500 - Medium
600 - Semi Bold (Demi Bold)
700 - Bold
800 - Extra Bold (Ultra Bold)
900 - Black (Heavy)
```

### grid-breakpoints (min-width):
```
xs  - 0
sm  - 576px
md  - 768px
lg  - 992px
xl  - 1200px
xxl - 1400px
```

### grid-breakpoints (max-width):
```
xs - 575.98px
sm - 767.98px
md - 991.98px
lg - 1199.98px
xl - 1399.98px
```

### responsive classes:
```
.container-fluid
.container
.row
.row-cols-{2, 3, 4}
.row-cols-{breakpoint}-{2, 3, 4}
.col-{1-12}
.col-{breakpoint}-{1-12}
.order-{breakpoint}-{first, 0–5, last}
.d-{breakpoint}-{inline, inline-block, block, grid, inline-grid, flex, inline-flex, none}
.flex-{fill, row, column, row-reverse, column-reverse, wrap, nowrap, flex-wrap-reverse}
.justify-content-{start, end, center, between, around, evenly}
.align-items-{start, end, center, baseline, stretch}
.align-content-{start, end, center, between, around, stretch}
.g-0, .gx-0, .gy-0, .g-10, .g-20, .g-30
.nowrap, d-none, [hidden]
.overflow-hidden
.h-100
```

### css mode classes (root):
```
.light
.dark
```

### theme switcher:
```
<span data-mode="light">Light</span>
<span data-mode="dark">Dark</span>
<span data-mode="auto">Auto</span>
```

### switcher active item:
```
[data-mode].active {}
```

### theme toggler:
```
<div class="toggler"><button></button></div>
```

### toggler active item:
```
(recommended):
.light .toggler {}
.dark .toggler {}

(optional):
.toggler.toggler-light {}
.toggler.toggler-dark {}
```

### default mode (optional):
```
<html data-mode-default="light">
...
```
