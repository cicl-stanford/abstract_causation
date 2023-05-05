# Experiments readme

Information about each of the experiment that is run as part of this project. 

## Experiment 1: Blicket 'feedback condition'
- Blicket Task with 16 trials. Feedback is shown on all trials. Blickets are defined by either color or shape.
- No url paramaters

## Experiment 2: Blicket 'no feedback condition'
- Blicket Task with 16 trials. Feedback is shown, except for on the final trial (the one asked about in the surprise quiz). Blickets are defined by either color or shape.
- Pass one of URL Paramaters (shape_on, shape_off, color_on, color_off) dictating the causally relevant feature and whether the last trial is on or off
- Pass url paramaters with syntax URL?condition=shape_on

## Experiment 3: Blicket 'short condition'
- Blicket Task with 2 trials. Feedback is shown, except for on the final trial. Blickets are defined by either color or shape.
- Pass one of URL Paramaters (shape_on, shape_off, color_on, color_off) dictating the causally relevant feature and whether the last trial is on or off
- Pass url paramaters with syntax URL?condition=shape_on

## Experiment 4: Blicket 'conjunctive condition'
- Blicket Task with 16 trials. Feedback is shown, except for on the final trial. Blickets are defined by a conjunction of color and shape (ex. only 'light cubes' may be Blickets).
- Pass one of URL Paramaters of form condition = "blicketrule_lasttrial", (ex. condition=ls_dc, where ls is light cube and dc is dark cylinder)
- Pass url paramaters with syntax URL?condition=lc_dc

## Experiment 5: Physics 'long condition'
- Ramp sliding task with 16 trials. Either 1) the ramp or 2) the cube determine whether the cube crosses the finish line
- Pass URL Paramater for condition as one of (1, 2, 3, 4). Four conditions dictate whether 1) the ramp or cube is causally determinant and 2) whether red cubes and blue ramps are high friction while black cubes and yellow ramps are low friction or whether the inverse is true (2x2). For the four conditions, the cube will cross the line when there is a; 1:black_cube, 2:red_cube, 3:blue_ramp, 4:yellow_ramp
- Pass url paramaters with syntax URL?condition=4

## Experiment 6: Physics 'short condition'
- Ramp sliding task with 4 trials (one of each scenario). Either 1) the ramp or 2) the cube determine whether the cube crosses the finish line
- Pass URL Paramater for condition as one of (1, 2, 3, 4). Four conditions dictate whether 1) the ramp or cube is causally determinant and 2) whether red cubes and blue ramps are high friction while black cubes and yellow ramps are low friction or whether the inverse is true (2x2). For the four conditions, the cube will cross the line when there is a; 1:black_cube, 2:red_cube, 3:blue_ramp, 4:yellow_ramp
- Pass url paramaters with syntax URL?condition=4

## Experiment 7: Physics 'conjunctive condition'
- Ramp sliding task with 16 trials. Both ramp and cube determine whether the cube crosses the finish line
- Pass URL Paramater for condition as one of (1, 2, 3, 4). 
- Pass url paramaters with syntax URL?condition=1
