<span class="heading">
Algorithm from flow to streams to contribution
</span>

Comparison $A:B$
The first step is to locate all streams by decomposing flow
1. Set initial graph $G\_{AB}$. Convert the row of $h\_{AB}$ to corresponding graph <!-- .element: class="fragment" data-fragment-index="1" -->
2. Locate a stream $s\_i$ by finding a path in $G\_{AB}$ from $A$ to $B$. Streams' flow is equal to the minimum flow of the path $\phi\_i = f\_{min}$ <!-- .element: class="fragment" data-fragment-index="2" -->
3. Remove stream from graph. Substract $\phi\_i$ from paths' flow. If an edge has $0$ flow remove it. <!-- .element: class="fragment" data-fragment-index="3" -->

Repeat until all flow is depleted and all streams are found: $S = \\{s\_1, s\_2, ...s\_k\\}$ <!-- .element: class="fragment" data-fragment-index="4" -->

<span><!-- .element: class="fragment" data-fragment-index="5" -->
Calculate contribution of comparison $XY$ to comparison $AB$: 
$c_{XY} = \sum\_i \frac{\phi\_i}{|\pi\_i|}$ 
where $|\pi\_i|$ is the lenght of path $i$ of stream $s\_i$
</span>


<footer>
Theodore Papakonstantinou - ISCB 2018 - 7
</footer>
