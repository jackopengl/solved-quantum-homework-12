Download Link: https://assignmentchef.com/product/solved-quantum-homework-12
<br>



<ol>

 <li>Let <em>t </em>∈ N.

  <ul>

   <li>Prove that</li>

  </ul></li>

</ol>

<em>t</em>−1 <em>x<sup>t </sup></em>− 1 = (<em>x </em>− 1)<sup>X</sup><em>x<sup>k</sup>.</em>

<em>k</em>=0

<ul>

 <li>Prove that <em>x </em>= <em>e</em><sup>2<em>πi</em>(<em>m/t</em>) </sup>is a solution to <em>x<sup>t </sup></em>− 1 for <em>m </em>∈ Z.</li>

 <li>Let <em>m </em>∈ Z with 0 ≤ <em>m &lt; t</em>. Use the previous parts to prove that</li>

</ul>

if <em>m </em>= 0<em>, </em>0 otherwise<em>.</em>

<em>k</em>=0

Recall that the <em>n</em>-qubit Quantum Fourier Transform (QFT <em><sub>n</sub></em>) is characterized by its action on basis vector |<em>x</em>i,

where [0<em>.</em>···] represents the number with binary decimal representation 0<em>.</em>··· and likewise [<em>x</em>] represents the number with binary representation <em>x </em>∈ {0<em>,</em>1}<em><sup>n</sup></em>.

<ol start="2">

 <li><strong>(i) </strong>Explicitly calculate QFT <em><sub>n </sub></em>|0<em><sup>n</sup></em></li>

</ol>

<strong>(ii) </strong>Explicitly calculate QFT <em><sub>n </sub></em>|1<em><sup>n</sup></em>i.

<ol start="3">

 <li>Show that</li>

</ol>

QFT <em><sub>n </sub></em>|<em>x</em>i = 2−<em>n/</em>2 X <em>e</em>2<em>πi</em>[<em>x</em>][<em>y</em>]<em>/</em>2<em><sup>n </sup></em>|<em>y</em>i<em>,</em>

<em>y</em>∈{0<em>,</em>1}<em><sup>n</sup></em>

where [<em>x</em>] represents the number with binary representation <em>x </em>∈ {0<em>,</em>1}<em><sup>n </sup></em>(and so [<em>x</em>][<em>y</em>] is the product of <em>x </em>and <em>y</em>, regarded as binary numbers).

<strong>Problems continue on the next page.</strong>

1

<h2>                                                 QUANTUM ALGORITHMS, HW 11 ADDITIONAL PROBLEMS                                                                       2</h2>

<ol start="4">

 <li>Use the previous problem to prove that</li>

</ol>

QFT †<em><sub>n </sub></em>|<em>x</em>i = 2−<em>n/</em>2 X <em>e</em>−2<em>πi</em>[<em>x</em>][<em>y</em>]<em>/</em>2<em><sup>n </sup></em>|<em>y</em>i

<em>y</em>∈{0<em>,</em>1}<em><sup>n</sup></em>

for basis vector |<em>x</em>i ∈ {0<em>,</em>1} defines the inverse of QFT <em><sub>n</sub></em>.

<em>Hint 1: </em>Show that QFT <em><sub>n </sub></em>◦ QFT <sup>†</sup><em><sub>n </sub></em>|<em>x</em>i = QFT <sup>†</sup><em><sub>n </sub></em>◦ QFT <em><sub>n </sub></em>|<em>x</em>i = |<em>x</em>i.

<em>Hint 2: </em>You may find this identity useful

2<em><sup>n</sup></em>−1

<em><sup>n</sup></em>

<table width="223">

 <tbody>

  <tr>

   <td width="155">X 2<em>πi k`/</em>2<em>e                  </em>= 0<em>k</em>=0</td>

   <td width="34">if</td>

   <td width="34"><em>` </em>6= 0<em>.</em></td>

  </tr>

 </tbody>

</table>

<ol start="5">

 <li><strong>(i) </strong>Write the matrix for QFT <sub>3 </sub>in the standard computational basis (i.e. |<em>x</em>i for <em>x </em>∈ {0<em>,</em>1}<em><sup>n</sup></em>). Use the notation <em>ω<sub>n </sub></em>= <em>e</em><sup>2<em>πi/n</em></sup>. [<em>Hint: this is an </em>8 × 8 ]</li>

</ol>

<strong>(ii) </strong>Write the matrix for in the standard computational basis (i.e. |<em>x</em>i for <em>x </em>∈

{0<em>,</em>1}<em><sup>n</sup></em>).