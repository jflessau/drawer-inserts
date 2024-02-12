<div style="display: flex; justify-content: center; align-items: center; width: 100%; margin-bottom: 3rem;">
<img style="max-width: 512px; border-radius: 12px;" alt="3D rendering of drawer inserts" src="media/drawer-inserts-rendering.png" />
</div>

# drawer inserts

This is a [blender](https://www.blender.org/) project for procedurally generating 3D printable drawer inserts.
Blender v4.0.2 was used to create it.

It is inspired by [this project](https://github.com/node-dojo/dojo-recursive-bins) from @node-dojo.

## Demo

![Blender setup for easy creation of custom drawer inserts for 3D printing.](media/procedurally-generated-drawer-inserts.mp4)

## Usage

Download and install Blender if you haven't already. Then open the file and you will see 3D view showing the drawer inserts on the left and the configuration options on the right. Configuration options are:

| option               | type      | description                                              |
| -------------------- | --------- | -------------------------------------------------------- |
| `rows`               | `integer` | Number of rows in the drawers                            |
| `columns`            | `integer` | Number of columns in the drawers                         |
| `container depth`    | `float`   | Depth of the drawer                                      |
| `container width`    | `float`   | Width of the drawer                                      |
| `container height`   | `float`   | Height of the drawer                                     |
| `box height`         | `float`   | Height of the inserts                                    |
| `gap`                | `float`   | Gap between the insert                                   |
| `wall width`         | `float`   | Thickness of the inserts' walls                          |
| `slope`              | `float`   | Slope of the inserts                                     |
| `bottomless box`     | `bool`    | Whether the inserts have a bottom or not                 |
| `show export`        | `bool`    | Toggle showing just one insert for export to e.g. `.stl` |
|  `export row number` | `integer` | The row number of the insert to export                   |

### Hints:

- Bottomless inserts are much quicker to print, at least with FDM printers.
- Adding a slope is useful for drawers closer to eye level or ones that do not pull out all the way. Helps to see and grab the content.
- Units are omitted on purpose. As long as your ratio is correct, you can use any unit you like and later scale the model in a slicing software of your choice.
