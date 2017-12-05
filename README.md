# Pathfinder
Solves the [Traveling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem) on a user-supplied data-set.

## Features
##### Core
Is build using Haskell and implements at least one algorithm that gives an exact solution to the problem. Possible
algorithms would include '[Brute-Force](https://en.wikipedia.org/wiki/Brute-force_search)', '[Held-Karp](https://en.wikipedia.org/wiki/Held%E2%80%93Karp_algorithm)' (dynamic programming) or a '[Branch-and-Bound](https://en.wikipedia.org/wiki/Branch_and_bound)'-approach. If feasible multi-threading
should be used.

Pathfinder comes with pre-configured problem-sets to solve. However, users can add custom sets which consist of a list of 2-dimensional points
that represent points of interest (e.g. cities).

##### Frontend
User-interaction is done through a web-based front end that gives interactive visual feedback on the state of the calculation.
The front end is done using html/css/js. Communication with the backend is done through ajax-calls.

##### Backend
To connect the frontend with the core, pathfinder provides a rest-api that is done in haskell as well.

###### Team
J. Behrmann & J. Kluoné
