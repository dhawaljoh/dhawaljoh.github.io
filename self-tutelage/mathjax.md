---
layout: page
title: MathJax
permalink: /self-tutelage/mathjax/
---

<script src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>


MathJax test site

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

The following is a math block:

$$ 5 + 5 $$

But next comes a paragraph with an inline math statement:

\$$ 5 + 5 $$
\$\$ 5 + 5 $$


<br><br>

ACCORDIAN STUFF

---
- - -
<br><br>

<link rel="stylesheet" href="//code.jquery.com/ui/1.10.4/themes/smoothness/jquery-ui.css">
<script src="//code.jquery.com/jquery-1.10.2.js"></script>
<script src="//code.jquery.com/ui/1.10.4/jquery-ui.js"></script>

<script>
$(function() {
 $( ".accordion" ).accordion();
 $(".accordion").accordion({ header: "h3", collapsible: true, active: false ,heightStyle: "content" });
});
</script>

 <div class="accordion">
 <h3>question goes here</h3>
     <div>
       <p>Answer goes here</p>
     </div>
 <h3>question goes here</h3>
     <div>
       <p>Answer goes here</p>
     </div>
 </div>
