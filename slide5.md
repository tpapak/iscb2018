<span class="heading">
$h^{AB}$ row as a **comparison graph** $G\_{AB}$
</span>
<span class="content">

- Each $h$ matrix row can be transformed into a directed graph $G_{AB}= (V,E, F)$ 
 - $V$: Set of interventions
 - $E$: Comparisons with direct evidence (studies)
 - $F$: Flow, property of edges, equals the elements of $h$ row.

*Köning J. Krahn U. Binder H. Statistics in Medicine 2013*

Assumptions for contribution in a contribution graph <!-- .element: class="fragment" data-fragment-index="1" -->
<div> 
<table>
<tr><!-- .element: class="fragment" data-fragment-index="1" -->
<td>
Contribution of <em>parallel</em> paths (sequence of edges-comparisons) is **equal to the their flow**.
<br>
  $c\_{ACB}=c\_{AC}+c\_{CB} =f\_1$
<br>
  $c\_{ADEB}=c\_{AD}+c\_{DE}+c\_{EB} =f\_2$
<br>
  $c\_{AB}=f\_{direct}$
</td>
<td>
<img src="images/parallel.png" height="170px"/>
</td>
</tr>
<tr><!-- .element: class="fragment" data-fragment-index="2" -->
<td>
Contribution of individual edge inside a path 
<br>
Each comparison **contributes equally** in a path so the contribution
  of each comparison is its **flow** divided by its **length**:
<br>
  $c\_{AC}=c\_{CD}=c\_{DB}=\frac{f\_{ACDB}}{3}$
<br>
  $\mathbf{c\_{comparison}=\frac{f\_{path}}{length \~ of \~ path}}$
</td>
<td>
<img src="images/serial.png" size="85%" />
</td>
</tr>
</table>
</div>

</span>

<footer>
Theodore Papakonstantinou - ISCB 2018 - 5
</footer>
