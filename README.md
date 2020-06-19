![](preview/preview.gif)

# ~~Transparent full-screen & monocle work-flow for BSPWM~~

# Screw this! Use [Crystal](https://github.com/salman-abedin/crystal)

No more ugly windows behind your beautiful transparent one

# Features

-  No background windows on fullscreen mode
-  No background windows on monocle mode
-  Navigation between hidden windows
-  Auto navigation to previews hidden window after closing
-  fully functional with regular work flow

# Dependencies

-  A compositor(duh!)

# Usage

```sh
mono-trans --toggle [monocle,fullscreen]  # toggle transparent monocle
mono-trans --navigate [next,prev]         # navigate to next/prev hidden nodes
mono-trans --close                        # closes current node and unhides the previous one
```

