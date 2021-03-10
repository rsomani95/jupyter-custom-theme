background_color = "#11141F" # "#0F111B"
text_color = "#8D9C9F"
grid_color = "#1B1D30"
linestyle = '--'
font_family = 'monospace'
font_size = 12
dpi = 100

import matplotlib as mpl
text_keys = ['axes.labelcolor', 'text.color', 'xtick.color', 'ytick.color']
background_keys = [
    'figure.edgecolor',
    'figure.facecolor',
    'axes.edgecolor',
    'axes.facecolor',
    'savefig.facecolor',
    'savefig.edgecolor',
]
grid_keys = [
    'grid.color',
    'patch.facecolor'
]
mpl.rcParams['font.size'] = font_size
mpl.rcParams['font.family'] = font_family
mpl.rcParams['grid.linestyle'] = linestyle
mpl.rcParams['figure.dpi'] = dpi
for param in grid_keys:
    mpl.rcParams[param] = grid_color
for param in text_keys:
    mpl.rcParams[param] = text_color
for param in background_keys:
    mpl.rcParams[param] = background_color
