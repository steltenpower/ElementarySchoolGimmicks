# Elementary School Gimmicks

## Number slides
When I noticed a young kid able to do simple calculations with things, depictions and spoken numbers significantly better than with amounts written in digits, I wondered if learning could be helped by making the abstractions that digits are, explicit WITHIN doing calculations. This resulted in designs for 3 'machines', where every number is always also represented in an amount of depictions:

### Slide Spelling (Dutch):
<table><tr><td>
First reasonable paper prototype: shifting 'tens' and 'ones'.<br>
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/getallenuitspreker_samengesteld.jpg">
  </td><td>
But number naming is a little bit more complex than that. To figure that out:<br>
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/getallenuitspreker.jpg"></td></tr><tr><td colspan="3">
Which together with the notion of needing physical constraints for how layers can be moved relative to each other, resulted in the current digital design:<br><img src="https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/getal_in_letters_v0.svg"><br>
  The on/off of the trema, so "e" or "ë", is not taken into account yet.<br>
  optional TODO:<br>
  introduce empty colums/rows for sturdiness</td></tr>
  <tr><td colspan="3"> Of course we need a english version as well, where "for-teen" and "twenty-four" show there's irregularity in the order of things in that language too.
  </td></tr></table>

### Slide PlusMinus
Showing that adding and substracting are the same thing in a different direction.<br>
The first reasonable paper prototype: <img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/IMG_20230328_233125596.jpg">

The [in-progress digital design](https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/AddSubtract.svg) which sneaks in the concept of negative numbers.


### Slide Multiply <a name="multiplication"></a>
<table><tr><td>The first reasonable paper prototype:<br>
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/IMG_20200501_203637563.jpg">
  </td><td>
Built from a background:<br>
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/multiply_background.jpg">
  </td><td>with the following mask on top of it twice,<br> for both horizontal and vertical directions:<br>
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/horizontal_sliding_mask.jpg">
  </td></tr><tr><td colspan="3"> To also introduce the important concepts 0 and numbers above 10 the current full digital design is:<br>
<!-- <img src="https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/multiplier.svg"><br>-->
<img src="https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/multiplier2.svg"></td></tr></table>

I made a (still jerky, bugfix welcome) digital version of it that you can play on touch screens. Try by clicking this image: <a title="play !" href="https://steltenpower.github.io/ElementarySchoolGimmicks/sliding_calculators_multiplication.html">
<img src="https://repository-images.githubusercontent.com/217832815/2aec6500-1022-11eb-952a-1796fdb14235"></a>

## Some more ideas for learning numbers and calculations:

### A static multiplication matrix, with a layout to get a sense of prime numbers <a name="multiplication_static"></a>
![keersommen met aantallen](https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/keersommen_met_aantallen.jpg)
A variation on https://upload.wikimedia.org/wikipedia/commons/3/3f/Multiplication_table_to_scale.svg

### Numbered kid juwelry
- Rings/bracelets that show digits (similar to what's on combination lock). With a viewing window to read the number from and to keep 2 rings together. Highlight zeroes as those trigger 'carry over'. Of course those high-tech knitters thought of the same: [counting ring](https://www.youtube.com/watch?v=ZLnXdEWwikk)
- Necklace with beads that each have a number, starting with zero and from there add one every time (somebody must have made this, though the closest I got to finding it was this [alphabet necklace](https://rhythmsofplay.com/alphabet-bead-necklace-craft-for-kids/)

### Font of characters kids learn writing, so I can type a text that kid can practice to write

### Pattern Recognition that does ping or BUZZ based on handwritten or spoken numbers


notes:
- https://www.sitepoint.com/masking-in-the-browser-with-css-and-svg/
- https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/fill-rule#Example_2
- http://www.petercollingridge.co.uk/tutorials/svg/interactive/dragging/
