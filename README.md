# Elementary School Gimmicks

## Number sliders
When I noticed a young kid able to do simple calculations with things, depictions and spoken numbers significantly better than with amounts written in digits, I wondered if learning could be helped by making the abstractions that digits are, explicit WITHIN doing calculations. This resulated in designs for 3 'machines', where every number is always also represented in an amount of depictions:

### Numbers expressed in the alfabet (in Dutch):

First reasonable paper prototype: shifting 'tens' and 'ones'.
<img src="https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/getallenuitspreker_samengesteld.jpg">

But number naming is a little bit more complex than that. To figure that out:
![naming tens and ones v2](https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/getallenuitspreker.jpg)

Which together with the notion of needing physical constraints for how layers can be moved relative to each other, resulted in the [full digital design] (https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/getal_in_letters_v0.svg) (though the on/off of the trema, so "e" or "ë" is not taken into account yet). Of course we need a english version as well, where "for-teen" and "twenty-four" show there's complexity in the order of things.

### Add and substract, shown as 2 directions along the same scale:
The first reasonable paper prototype: ![add and substract](https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/IMG_20230328_233125596.jpg)

The [in-progress digital design](https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/AddSubtract.svg) which sneaks in the concept of negative numbers.

### Multiplication<a name="multiplication"></a>
The first reasonable paper prototype: ![paper](https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/IMG_20200501_203637563.jpg)
Built from a background:
![background](https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/multiply_background.jpg)
with the following mask on top of it, for both horizontal and vertical directions:
![x-mask](https://raw.githubusercontent.com/steltenpower/ElementarySchoolGimmicks/master/horizontal_sliding_mask.jpg).

In the [full digital design](https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/muliplier.svg) the important concepts 0 and numbers above 10 were introduced as inputs.

I made a (still jerky, improvements welcome) digital version of it that you can play on touch screens. Try by clicking this image: <a title="play !" href="https://steltenpower.github.io/ElementarySchoolGimmicks/sliding_calculators_multiplication.html">
<img src="https://repository-images.githubusercontent.com/217832815/2aec6500-1022-11eb-952a-1796fdb14235"></a>

## Some more ideas for learning numbers and calculations:

### A static multiplication matrix, with a layout to get a sense of prime numbers <a name="multiplication_static"></a>
![keersommen met aantallen](https://github.com/steltenpower/ElementarySchoolGimmicks/blob/master/keersommen_met_aantallen.jpg)
A variation on https://upload.wikimedia.org/wikipedia/commons/3/3f/Multiplication_table_to_scale.svg

### Numbered kid juwelry
- Rings/bracelets that show digits (similar to what's on combination lock). With a viewing window to read the number from and to keep 2 rings together. Highlight zeroes as those trigger 'carry over'.
- Necklace with beads that each have a number, starting with zero and from there add one every time

### Font of characters kids learn writing, so I can type a text that kid can practice to write

### Pattern Recognition that does ping or BUZZ based on handwritten or spoken numbers
notes:
- https://www.sitepoint.com/masking-in-the-browser-with-css-and-svg/
- https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/fill-rule#Example_2
- http://www.petercollingridge.co.uk/tutorials/svg/interactive/dragging/


