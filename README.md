# Focusing on the Flow with Dot.
by Evelyn J. Boettcher

## DDV_Talk_201702_DOT
Dayton Data Visualization Meetup Talk 
 
February 9th, 2017

## What is in the Repository
This repository contains some examples (some from the graphviz website) showcasing what dot can do.

## Dot
"dot" draws directed graphs as hierarchies. It runs as a command line program, web 
visualization service, or with a compatible graphical interface.
Its features include well-tuned layout algorithms for placing nodes and edge
splines, edge labels, “record” shapes with “ports” for drawing data structures;
and cluster layouts (cite: www.graphviz.org/pdf/dotguide.pdf). Because "dot" takes 
care  of the layout, you are free to focus on how objects are related to each other. 
Graphs are simply written as a human readable text file:
```bash
digraph mydotgraph {
main -> parse -> execute
} 
```
This talk will give you the tools to start making your own graphs either organizations
charts, software flow diagrams, or work flows using dot.

## Useful Cites
* www.graphviz.org
* https://stamm-wilbrandt.de/GraphvizFiddle
* http://mdaines.github.io/viz.js/


## References
* www.graphviz.org/pdf/dotguide.pdf
