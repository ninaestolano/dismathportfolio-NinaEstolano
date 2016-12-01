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
<h1>Week 4</h1>
<ul type="disc">
<li>We learned that a counter-example is enough to prove something is wrong.</li>
<li>We learned how to prove a tautology using a truth table and proof by logical equivalences.</li>
<li>These are the logical equivalences:</li>
<li><table style="width:100%">
  <tr>
    <th>Equivalence</th>
    <th>Name</th>
  </tr>
  <tr>
    <td><i>p</i> ∧ T ≡ <i>p</i>
    <br><i>p</i> ∨ F ≡ <i>p</i><br/></td>
    <td>Identity Laws</td>  
  </tr>
  <tr>
    <td><i>p</i> ∨ T ≡ T
    <br><i>p</i> ∧ F ≡ F<br/></td>
    <td>Domination Laws</td>
  </tr>
   <tr>
    <td><i>p</i> ∨ <i>p</i> ≡ <i>p</i>
    <br><i>p</i> ∧ <i>p</i> ≡ <i>p</i><br/></td>
    <td>Idempotent Laws</td>
  </tr>
   <tr>
   <td>¬(¬<i>p</i>) ≡ <i>p</i></td>
    <td>Double Negation Law</td>
  </tr>
  <tr>
    <td><i>p</i> ∨ <i>q</i> ≡ <i>q</i> ∨ <i>p</i>
    <br><i>p</i> ∧ <i>q</i> ≡ <i>q</i> ∧ <i>p</i><br/></td>
    <td>Commutative Laws</td>
  </tr>
  <tr>
  <td>(<i>p</i> ∨ <i>q</i>) ∨ <i>r</i>  ≡ <i>p</i> ∨ (<i>q</i> ∨ <i>r</i>)
  <br>(<i>p</i> ∧ <i>q</i>) ∧ <i>r</i>  ≡ <i>p</i> ∧ (<i>q</i> ∧ <i>r</i>)</td>
    <td>Associative Laws</td>
  </tr>
   <tr>
    <td><i>p</i> ∨ (<i>q</i> ∧ <i>r</i>)  ≡ (<i>p</i> ∨ <i>q</i>) ∧ (<i>p</i> ∨ <i>r</i>)
    <br><i>p</i> ∧ (<i>q</i> ∨ <i>r</i>)  ≡ (<i>p</i> ∧ <i>q</i>) ∨ (<i>p</i> ∧ <i>r</i>)</td>
    <td>Distributive Laws</td>
  </tr>
   <tr>
    <td>¬(<i>p</i> ∧ <i>q</i>) ≡ ¬<i>p</i> ∨ ¬<i>q</i>
    <br>¬(<i>p</i> ∨ <i>q</i>) ≡ ¬<i>p</i> ∧ ¬<i>q</i><br/></td>
    <td>De Morgan's Laws</td>
  </tr>
  <tr>
    <td><i>p</i> ∨ (<i>p</i> ∧ <i>q</i>) ≡ <i>p</i>
    <br><i>p</i> ∧ (<i>p</i> ∨ <i>q</i>) ≡ <i>p</i><br/></td>
    <td>Absorption Laws</td>
  </tr>
  <tr>
    <td><i>p</i> ∨ ¬<i>p</i> ≡ T
    <br><i>p</i> ∧ ¬<i>p</i> ≡ F<br/></td>
    <td>Negation Laws</td>
  </tr>
</table>
</li>
<li>Example:</li>
  <ul>
  <li>(<i>p</i> ∧ <i>q</i>) ∨ ¬<i>p</i></li>
  <li>Proof by Logical Equivalences:</li>
  <li>by commutative: ¬<i>p</i> ∨ (<i>p</i> ∧ <i>q</i>)</li>
  <li>by distributive: (¬<i>p</i> ∨ <i>p</i>) ∧ (¬<i>p</i> ∨ <i>q</i>)</li>
  <li>by negation: T  ∧ (¬<i>p</i> ∨ <i>q</i>)</li>
  <li>by identity: ¬<i>p</i> ∨ <i>q</i></li>
  <li>The formula is already simplified.</li>
  <li>Proof by Truth Table:</li>
  <li><table style="width:100%">
    <tr>
     <th><i>p</i></th>
     <th><i>q</i></th>
     <th><i>p</i> ∧ <i>q</i></th>
     <th>(<i>p</i> ∧ <i>q</i>) ∨ ¬<i>p</i></th>
    </tr>
    <tr>
     <td>T</td>
     <td>T</td> 
     <td>T</td>
     <td>T</td> 
    </tr>
    <tr>
     <td>T</td>
     <td>F</td> 
     <td>F</td>
     <td>F</td>
    </tr>
    <tr>
     <td>F</td>
     <td>T</td> 
     <td>F</td>
     <td>T</td>
    </tr>
    <tr>
     <td>F</td>
     <td>F</td> 
     <td>F</td>
     <td>T</td>
    </tr>
  </table>
  <p>∴ Not Tautology</p>
  </li>
  <li>The formula has the same interpretations as an implication therefore ¬<i>p</i> ∨ <i>q</i> ≡ <i>p</i> → <i>q</i>.</li>
  </ul>
<li>We learned how to formalize English in Logic.</li>
<li>Example:</li>
  <ul>
  <li>If Joe drives fast he gets a speeding ticket ≡ <i>r</i> → <i>s</i></li>
  <li>Joe did not get a ticket ≡ ¬<i>s</i></li>
  <li>Therefore, Joe did not drive fast ≡ ∴ ¬<i>r</i></li>
  <li>Prove ((<i>r</i> → <i>s</i>) ∧ ¬<i>s</i>) → ¬<i>r</i></li>
  <li>Proof by Truth Table:</li>
  <li><table style="width:100%">
    <tr>
     <th><i>r</i></th>
     <th><i>s</i></th>
     <th><i>r</i> → <i>s</i></th>
     <th>(<i>r</i> → <i>s</i>) ∧ ¬<i>s</i></th>
     <th>((<i>r</i> → <i>s</i>) ∧ ¬<i>s</i>) → ¬<i>r</i></th>
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
     <td>T</td> 
    </tr>
    <tr>
     <td>F</td>
     <td>T</td> 
     <td>T</td>
     <td>F</td>
     <td>T</td> 
    </tr>
    <tr>
     <td>F</td>
     <td>F</td> 
     <td>T</td>
     <td>T</td>
     <td>T</td> 
    </tr>
  </table>
  <p>∴ Valid</p>
  </li>
  <li>Proof by Logical Equivalences:</li>
  <li>by implication equivalence: ((¬<i>r</i> ∨ <i>s</i>) ∧ ¬<i>s</i>) → ¬<i>r</i></li>
  <li>by commutative: (¬<i>s</i> ∧ (¬<i>r</i> ∨ <i>s</i>)) → ¬<i>r</i></li>
  <li>by distributive: ((¬<i>s</i> ∧ ¬<i>r</i>) ∨ (¬<i>s</i> ∧ <i>s</i>)) → ¬<i>r</i></li>
  <li>by negation: ((¬<i>s</i> ∧ ¬<i>r</i>) ∨ F) → ¬<i>r</i></li>
  <li>by identity: (¬<i>s</i> ∧ ¬<i>r</i>) → ¬<i>r</i></li>
  <li>by implication equivalence: ¬(¬<i>s</i> ∧ ¬<i>r</i>) ∨ ¬<i>r</i></li>
  <li>by de Morgan's: (¬(¬<i>s</i>) ∨ ¬(¬<i>r</i>)) ∨ ¬<i>r</i></li>
  <li>by double negation: (<i>s</i> ∨ <i>r</i>) ∨ ¬<i>r</i></li>
  <li>by associative: <i>s</i> ∨ (<i>r</i> ∨ ¬<i>r</i>)</li>
  <li>by negation: <i>s</i> ∨ T</li>
  <li>by domination: T</li>
  <li>∴ Valid</li>
  </ul>
<li>First-Order Logic (or Predicate Logic) was introduced.</li>
<li>First-Order Logic is more expressive.</li>
<li>Its building blocks are:</li>
 <ul>
  <li>constants: refer to specific objects</li>
  <li>variables: range over objects</li>
  <li>predicates: describe properties of objects or relationships between objects</li>
 </ul>
<li>Examples:</li>
 <ul>
  <li>even(2) ≡ T</li>
  <li>even(5) ≡ F</li>
  <li><i>Q</i>(<i>x</i>, <i>y</i>) denotes "x=y+3"</li>
  <li><i>Q</i>(3,0) ≡ T</li>
  <li><i>Q</i>(1,2) ≡ F</li>
 </ul>
</ul>
<h1>Week 5</h1>
<ul type="disc">
<li>We discussed quantifiers.</li>
<li>Universal Quantifier (∀): refers to all objects</li>
<li>Existential Quantifier (∃): refers to some objects</li>
<li>∀x.<i>P</i>(x) is true if predicate <i>P</i> is true for every object in the universe of discourse, and false otherwise.</li>
<li>∃x.<i>P</i>(x) is true if there is at least one element in the domain such that <i>P</i>(x) is true.</li>
<li>We learned about quantified formulas.</li>
<li>Example:</li>
 <ul>
  <li>∃x.(even(x) ∧ gt(x, 100))</li>
  <li>Assume even(x) means "x is even" and gt(x, y) means "x > y".</li>
  <li>What is the truth value of this formula if the domain is all true integers? True</li>
  <li>What about ∀x.(even(x) ∧ gt(x, 100))? False</li>
 </ul>
<li>We also learned how to translate English into quantified formulas.</li>
<li>Examples:</li>
 <ul>
  <li>Assume freshman(x) means “x is a freshman” and inCS311(x) means “x is taking CS311”.</li>
  <li>Someone in CS311 is a freshman ≡ ∃x.(freshman(x) ∧ inCS311(x))</li>
  <li>No one in CS311 is a freshman ≡ ∀x.(¬freshman(x) ∨ ¬inCS311(x))</li>
  <li>Everyone taking CS311 are freshmen ≡ ∀x.(inCS311(x) → freshman(x))</li> 
  <li>Every freshman is taking CS311 ≡ ∀x.(freshman(x) → inCS311(x))</li>
 </ul>
</ul>
<h1>Week 6</h1>
<ul type="disc">
<li>We discussed proof rules.</li>
<li>Proof rules are written as rules of inference:</li>
 <ul>
 <li><p>Hypothesis 1</p><p>Hypothesis 2</p>
 <hr noshade width="15%"><p>∴ Conclusion</p></li>
 </ul>
<li><table style="width:100%">
  <tr>
    <th>Name</th>
    <th>Rule of Inference</th>
  </tr>
  <tr>
    <td>Modus Ponens</td>
    <td><p><i>Φ</i><sub>1</sub></p><p><i>Φ</i><sub>1</sub> → <i>Φ</i><sub>2</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>2</sub></p></td>
  </tr>
  <tr>
    <td>Modus Tollens</td>
    <td><p><i>Φ</i><sub>1</sub> → <i>Φ</i><sub>2</sub></p><p>¬<i>Φ</i><sub>2</sub></p>
    <hr noshade width="60%"><p>∴ ¬<i>Φ</i><sub>1</sub></p></td>
  </tr>
   <tr>
    <td>Hypothetical Syllogism</td>
    <td><p><i>Φ</i><sub>1</sub> → <i>Φ</i><sub>2</sub></p><p><i>Φ</i><sub>2</sub> → <i>Φ</i><sub>3</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>1</sub> → <i>Φ</i><sub>3</sub></p></td>
  </tr>
   <tr>
   <td>Or Introduction</td>
   <td><p><i>Φ</i><sub>1</sub></p>
   <hr noshade width="60%"><p>∴ <i>Φ</i><sub>1</sub> ∨ <i>Φ</i><sub>2</sub></p></td>
  </tr>
  <tr>
    <td>Or Elimination</td>
    <td><p><i>Φ</i><sub>1</sub> ∨ <i>Φ</i><sub>2</sub></p><p>¬<i>Φ</i><sub>2</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>1</sub></p></td>
  </tr>
  <tr>
    <td>And Introduction</td>
    <td><p><i>Φ</i><sub>1</sub></p><p><i>Φ</i><sub>2</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>1</sub> ∧ <i>Φ</i><sub>2</sub></p></td>
  </tr>
   <tr>
    <td>And Elimination</td>
    <td><p><i>Φ</i><sub>1</sub> ∧ <i>Φ</i><sub>2</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>1</sub></p></td>
  </tr>
   <tr>
    <td>Resolution</td>
    <td><p><i>Φ</i><sub>1</sub> ∨ <i>Φ</i><sub>2</sub></p><p>¬<i>Φ</i><sub>1</sub> ∨ <i>Φ</i><sub>3</sub></p>
    <hr noshade width="60%"><p>∴ <i>Φ</i><sub>2</sub> ∨ <i>Φ</i><sub>3</sub></p></td>
  </tr>
</table>
</li>
<li>Assume the following hypotheses:</li>
 <ul>
  <li>1. It is not raining or Kate has her umbrella ≡ ¬r ∨ u</li>
  <li>2. Kate does not have her umbrella or she does not get wet ≡ ¬u ∨ ¬w</li>
  <li>3. It is raining or Kate does not get wet ≡ r ∨ ¬w</li>
  <li>4. Kate is grumpy only if she is wet ≡ g → w</li>
  <li>Show these lead to the conclusion: "Kate is not grumpy" ≡ ¬g</li>
 </ul>
<li>Let:</li>
  <ul>
   <li>r = "It is raining"</li>
   <li>u= "Kate has her umbrella"</li>
   <li>w = "Kate is wet"</li>
   <li>g = "Kate is grumpy"</li>
  </ul>
<li>I answered:</li>
 <ul>
  <li>Resolution:</li>
    <ul>
      <li><p>¬r ∨ u</p><p>¬u ∨ ¬w</p>
      <hr noshade width="15%"><p>∴ ¬r ∨ ¬w</p></li>
    </ul>
  <li>Resolution:</li>
    <ul>
      <li><p>¬r ∨ ¬w</p><p>r ∨ ¬w</p>
      <hr noshade width="15%"><p>∴ ¬w ∨ ¬w</p></li>
    </ul>
  <li>by idempotent: ¬w</li>
  <li>Resolution:</li>
    <ul>
      <li><p>¬w</p><p>g → w</p>
      <hr noshade width="15%"><p>∴ ¬g</p></li>
    </ul>
  <li>∴ Valid</li>
 </ul>
<li>We studied mathematical proof techniques.</li>
<li>Direct Proof:</li>
  <ul>
   <li>"If n is an even integer, then n<sup>2</sup> is even."</li>
   <li>Assume <i>p</i> is true.</li>
    <ul>
    <li>n ϵ even, n=2k, k ϵ Z</li>
    </ul>
   <li>Show <i>q</i> must also be true.</li>
    <ul>
     <li>(n = 2k)<sup>2</sup></li>
     <li>n<sup>2</sup> = 4k<sup>2</sup></li>
     <li>n<sup>2</sup> = 2·2k<sup>2</sup></li>
     <li>let: a=2k<sup>2</sup>, a ϵ Z</li>
     <li>n<sup>2</sup> = 2a</li>
     <li>by definition: n<sup>2</sup> is even</li>
     <li>∴ PROVEN</li>
    </ul>
  </ul>
<li>Proof by Contraposition:</li>
 <ul>
   <li>"If n<sup>2</sup> is even, then n is even."</li>
   <li>Assume ¬<i>q</i> is true.</li>
    <ul>
    <li>n ϵ odd, n=2k+1, k ϵ Z</li>
    </ul>
   <li>Show ¬<i>p</i> must also be true.</li>
    <ul>
     <li>(n = 2k+1)<sup>2</sup></li>
     <li>n<sup>2</sup> = 4k<sup>2</sup>+4k+1</li>
     <li>n<sup>2</sup> = 2·(2k<sup>2</sup>+2k)+1</li>
     <li>let: a=2k<sup>2</sup>+2k, a ϵ Z</li>
     <li>n<sup>2</sup> = 2a+1</li>
     <li>by definition: n<sup>2</sup> is odd</li>
     <li>∴ PROVEN</li>
     <li>∴ The original theorem is also true.</li>
  </ul>
<li>Proof by Contradiction:</li>
 <ul>
   <li>"If 3n+2 is odd, then n is odd."</li>
   <li>Negate the whole statement.</li>
    <ul>
    <li>¬(<i>p</i> → <i>q</i>) ≡ ¬(¬<i>p</i> ∨ <i>q</i>) ≡ <i>p</i> ∧ ¬<i>q</i></li>
    <li>Assume <i>p</i> ≡ T and ¬<i>q</i> ≡ T</li>
    <li>"3n+2 is odd" and "n is even"</li>
    </ul>
   <li>Show that a contradiction exists.</li>
    <ul>
     <li>n=2d, d ϵ Z</li>
     <li>3n+2 = 3(2d)+2</li>
     <li>3n+2 = 6d+2</li>
     <li>3n+2 = 2(3d+1)</li>
     <li>let: b=3d+1, b ϵ Z</li>
     <li>3n+2 = 2b</li>
     <li>∴ EVEN≠ODD</li>
     <li>There is a contradiction.</li>
    </ul>
  </ul>
<li>Proof by Cases:</li>
 <ul>
   <li>Prove |xy| = |x| |y|</li>
   <li>Case 1:</li>
    <ul>
     <li>x=+, y=+</li>
     <li>|(+x·+y)| = |+x| |+y|</li>
     <li>|xy| = xy</li>
     <li>xy = xy</li>
    </ul>
   <li>Case 2:</li>
    <ul>
     <li>x=+, y=-</li>
     <li>|(+x·-y)| = |+x| |-y|</li>
     <li>|-xy| = xy</li>
     <li>xy = xy</li>
    </ul>
   <li>Case 3:</li>
    <ul>
     <li>x=-, y=+</li>
     <li>|(-x·+y)| = |-x| |+y|</li>
     <li>|-xy| = xy</li>
     <li>xy = xy</li>
    </ul>
   <li>Case 4:</li>
    <ul>
     <li>x=-, y=-</li>
     <li>|(-x·-y)| = |-x| |-y|</li>
     <li>|xy| = xy</li>
     <li>xy = xy</li>
    </ul>
   <li>∴ PROVEN</li>
  </ul>
</ul>
<h1>Week 7</h1>
<ul type="disc">
<li>We discussed functions.</li>
</ul>
<h1>Week 8</h1>
<ul type="disc">
<li>We did not meet due to holidays.</li>
</ul>
<h1>Week 9</h1>
<ul type="disc">
<li>We discussed classes of functions.</li>
<li>We were introduced to algorithms.</li>
<li>We studied linear search algorithm.</li>
</ul>
<h1>Week 10</h1>
<ul type="disc">
<li>We continued discussing binary search pseudocode.</li>
<li>We learned about bubble sort pseudocode.</li>
<li>We discussed another sorting algorithm called insertion sort.</li>
<li>We also studied greedy algorithm.</li>
</ul>
<h1>Week 11</h1>
<ul type="disc">
<li>We discussed the growth of functions.</li>
</ul>
<h1>Week 12</h1>
<ul type="disc">
<li>We discussed graph theory.</li>
</ul>
