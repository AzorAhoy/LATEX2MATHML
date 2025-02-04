39

Write your Math formulas in LaTeX → Transform the LaTeX formulas in MathML Code → Copy/Paste the MathML Code in Word (after paste click CTRL and then T). Voila!

EXAMPLE:
Lets take for example this Formula: Formula written in LaTeX

This is the LaTeX source Code from the above Formula:

0 \leq \lim_{n\to \infty}\frac{n!}{(2n)!} \leq \lim_{n\to \infty} \frac{n!}{(n!)^2} = \lim_{k \to \infty, k = n!}\frac{k}{k^2} = \lim_{k \to \infty}\frac{1}{k} = 0.
Now open a Editor and put the above source code between the signs $$ $$ like this:

<!DOCTYPE html>
<html>
<head>
    <script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
    <title>tex texample</title>
</head>
<body>
    $$ 0 \leq \lim_{n\to \infty}\frac{n!}{(2n)!} \leq \lim_{n\to \infty} \frac{n!}{(n!)^2} = \lim_{k \to \infty, k = n!}\frac{k}{k^2} = \lim_{k \to \infty}\frac{1}{k} = 0.$$
</body>
</html>
Save the file as .html file and open it with a browser like Chrome.



Right Click on the Formula and Choose Show MathML As → MathML Code.

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mn>0</mn>
  <mo>&#x2264;<!-- ≤ --></mo>
  <munder>
    <mo form="prefix" movablelimits="true">lim</mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>n</mi>
      <mo stretchy="false">&#x2192;<!-- → --></mo>
      <mi mathvariant="normal">&#x221E;<!-- ∞ --></mi>
    </mrow>
  </munder>
  <mfrac>
    <mrow>
      <mi>n</mi>
      <mo>!</mo>
    </mrow>
    <mrow>
      <mo stretchy="false">(</mo>
      <mn>2</mn>
      <mi>n</mi>
      <mo stretchy="false">)</mo>
      <mo>!</mo>
    </mrow>
  </mfrac>
  <mo>&#x2264;<!-- ≤ --></mo>
  <munder>
    <mo form="prefix" movablelimits="true">lim</mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>n</mi>
      <mo stretchy="false">&#x2192;<!-- → --></mo>
      <mi mathvariant="normal">&#x221E;<!-- ∞ --></mi>
    </mrow>
  </munder>
  <mfrac>
    <mrow>
      <mi>n</mi>
      <mo>!</mo>
    </mrow>
    <mrow>
      <mo stretchy="false">(</mo>
      <mi>n</mi>
      <mo>!</mo>
      <msup>
        <mo stretchy="false">)</mo>
        <mn>2</mn>
      </msup>
    </mrow>
  </mfrac>
  <mo>=</mo>
  <munder>
    <mo form="prefix" movablelimits="true">lim</mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>k</mi>
      <mo stretchy="false">&#x2192;<!-- → --></mo>
      <mi mathvariant="normal">&#x221E;<!-- ∞ --></mi>
      <mo>,</mo>
      <mi>k</mi>
      <mo>=</mo>
      <mi>n</mi>
      <mo>!</mo>
    </mrow>
  </munder>
  <mfrac>
    <mi>k</mi>
    <msup>
      <mi>k</mi>
      <mn>2</mn>
    </msup>
  </mfrac>
  <mo>=</mo>
  <munder>
    <mo form="prefix" movablelimits="true">lim</mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>k</mi>
      <mo stretchy="false">&#x2192;<!-- → --></mo>
      <mi mathvariant="normal">&#x221E;<!-- ∞ --></mi>
    </mrow>
  </munder>
  <mfrac>
    <mn>1</mn>
    <mi>k</mi>
  </mfrac>
  <mo>=</mo>
  <mn>0.</mn>
</math>
Now Copy/Paste the MathML Code in Word 2013 (or 2007) and click sequentially CTRL and then T (Paste Options: keep the text only) or go to the small Ctrl image at the end of the MathML Code you pasted and select the option manually.

This is how the formula looks at the end in Word 2013: 