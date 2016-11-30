# dismathportfolio-NinaEstolano
Niña Francesca Estolano
<h1>Week 1</h1>
<ul type="disc">
<li>We were not able to meet due to holidays and discrepancies in the schedule.</li></ul>
<h1>Week 2</h1>
<ul type="disc">
<li>In our first meeting, the professor discussed the syllabus.</li>
<li>We also had our first lesson on logic.</li>
<li>We learned that propositional logic is the simplest logic and it is made of propositions, which can be true or false.</li>
<li>We studied the following logical connectives (or boolean connectives):</li>
<table style="width:100%">
  <tr>
    <th>Symbol</th>
    <th>Name</th> 
    <th>Description</th>
  </tr>
  <tr>
    <td>˄</td>
    <td>Conjunction</td> 
    <td>It is only true if both propositions are true, false if otherwise.</td>
  </tr>
  <tr>
    <td>˅</td>
    <td>Disjunction</td> 
    <td>It is false if both propositions are false, true if otherwise.</td>
  </tr>
  <tr>
    <td>¬</td>
    <td>Negation</td> 
    <td>It has the opposite truth value of the propositional variable.</td>
  </tr>
  <tr>
    <td>⊕</td>
    <td>Exclusive OR (XOR)</td> 
    <td>It is false if both propositions have the same truth value, true if otherwise.</td>
  </tr>
  <tr>
    <td>→</td>
    <td>Implication</td> 
    <td>It is false if the first proposition is true and the second proposition is false, true if otherwise.</td>
  </tr>
</table>
<li>We learned how to fill a truth table.</li>
<li>Truth table for Negation:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th>¬<i>p</i></th> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td> 
  </tr>
  <tr>
    <td>F</td>
    <td>T</td> 
  </tr>
</table>
<li>Truth table for Conjunction:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>˄<i>q</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
  </tr>
</table>
<li>Truth table for Disjunction:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>˅<i>q</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
  </tr>
</table>
<li>Truth table for Exclusive OR:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>⊕<i>q</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>F</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
  </tr>
</table>
<li>Truth table for Implication:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>→<i>q</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>T</td> 
  </tr>
</table>
<li>In an implication, the first part of the proposition is the antecedent and the second part is called the consequent.
<li>The implication <i>p</i>→<i>q</i> has a converse of <i>q</i>→<i>p</i>, an inverse of <i>¬p</i>→<i>¬q</i>, and a contrapositive of<i>¬q</i>→<i>¬p</i>.</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>→<i>q</i></th>
    <th>(Converse)<i>q</i>→<i>p</i></th>
    <th>(Inverse)<i>¬p</i>→<i>¬q</i></th>
    <th>(Contrapositive)<i>¬q</i>→<i>¬p</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td> 
    <td>T</td> 
    <td>T</td> 
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>T</td> 
    <td>F</td>
    <td>F</td>
    <td>T</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
  </tr>
</table>
<li>We had to construct a truth table for this formula: (<i>p</i>∧<i>q</i>)∨(¬<i>p</i>∧¬<i>q</i>)</li>
<li>My answer was:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>∧<i>q</i></th>
    <th>¬<i>p</i>∧¬<i>q</i></th>
    <th>(<i>p</i>∧<i>q</i>)∨(¬<i>p</i>∧¬<i>q</i>)</th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
    <td>F</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>F</td>
    <td>F</td> 
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>F</td>
    <td>T</td> 
    <td>T</td> 
  </tr>
</table>
</ul>
<h1>Week 3</h1>
<ul type="disc">
<li>We discussed the last logical connective which is biconditional(↔)("if and only if").</li>
<li>It is true if both propositions have the same truth value, false if otherwise.</li>
<li>Truth table for Biconditional:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>p</i>↔<i>q</i></th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
  </tr>
  <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>T</td>
    <td>F</td> 
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>T</td> 
  </tr>
</table>
<li>We also learned about the operator precedence.</li>
<li>Negation has the highest precedence while biconditional is the lowest (¬, ˄, ˅, →, ↔).</li>
<li>We had to choose the correct order for this formula: <i>p</i> ˅ <i>q</i> ˄ <i>r</i> ↔ <i>q</i> → ¬<i>r</i>, then construct its truth table.</li>
<li>This was my answer:</li>
<table style="width:100%">
  <tr>
    <th><i>p</i></th>
    <th><i>q</i></th>
    <th><i>r</i></th>
    <th><i>q</i>∧<i>r</i></th>
    <th><i>p</i>∨(<i>q</i>∧<i>r</i>)</th>
    <th><i>q</i>→<i>¬r</i></th>
    <th>(<i>p</i>∨(<i>q</i>∧<i>r</i>))↔(<i>q</i>→<i>¬r</i>)</th>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td> 
    <td>T</td> 
    <td>T</td> 
    <td>T</td>
    <td>F</td>
    <td>F</td>
  </tr>
  <tr>
    <td>T</td>
    <td>T</td>
    <td>F</td>
    <td>F</td>
    <td>T</td>
    <td>T</td>
    <td>T</td>
  </tr>
   <tr>
    <td>T</td>
    <td>F</td>
    <td>T</td>
    <td>F</td> 
    <td>T</td>
    <td>T</td>
    <td>T</td>
  </tr>
   <tr>
    <td>T</td>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
    <td>T</td>
    <td>T</td>
    <td>T</td>
  </tr>
  <tr>
    <td>F</td>
    <td>T</td>
    <td>T</td>
    <td>T</td> 
    <td>T</td>
    <td>F</td>
    <td>F</td>
  </tr>
  <tr>
    <td>F</td>
    <td>T</td>
    <td>F</td>
    <td>F</td>
    <td>F</td>
    <td>T</td>
    <td>F</td>
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>T</td>
    <td>F</td> 
    <td>F</td>
    <td>T</td>
    <td>F</td>
  </tr>
   <tr>
    <td>F</td>
    <td>F</td>
    <td>F</td>
    <td>F</td> 
    <td>F</td>
    <td>T</td>
    <td>F</td>
  </tr>
</table>
<li>We also learned about validity and unsatisfiability of a formula.</li>
<li>A formula is a tautology if it is "always true".</li>
<li>A formula is a contradiction/unsatisfiable if it is "always false".</li>
<li>A formula is contingent if it is "sometimes true, sometimes false".</li>
<li>A formula is satisfiable if there is at least one interpretation that is true.</li>
<li>A valid formula is a tautology.</li>
<li>An interpretation (I) is a mapping of from each propositional variables of a formula to exactly one truth value.</li>
<li>Example:</li>
  <ul>
    <li>(<i>p</i>∨(<i>q</i>∧<i>r</i>))↔(<i>q</i>→<i>¬r</i>)</li>
    <li><i>I</i><sub>1</sub>:{<i>p</i>↦ T; <i>q</i>↦ T; <i>r</i>↦ T}</li>
  </ul>
<li><i>I</i> ⊨ <i>Formula</i> evaluates to true under <i>I</i></li>
<li><i>I</i> ⊭ <i>Formula</i> evaluates to false under <i>I</i></li>
</ul>
