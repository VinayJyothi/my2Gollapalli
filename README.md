# my2Gollapalli
# Vinay jyothi
###### Aruku valley

 I like the location of Aruku valley and it was also know as ooty of Andhra Pradesh.<br>It has ***Pure coffee bean plants*** and also lot of greenary around that place.<br> Early morning snow was amazing.
 And the people in the ***Aruku Valley*** were very simple and hard workers. The locations was simply wonderful. A very good place to visit and explore the Nature.

 ---
 MY Fav Activities:
 #### Ordered List
 1. Having fresh coffee 
 2. Visiting Flower Garden
 3. Play on Tribal park
 #### Unorderd List
 * Bambo chicken
 * spicy Chees corn
 * Chicken Barbeque

[link_to_MyStats] (https://github.com/VinayJyothi/my2Gollapalli/blob/main/MyStats.md) 

---
Sports

Sports is a physical activity often competitive and organized, that aim to use, maintain, or improve physical ability and skills  while providing enjoymnet to participants and also entertainment to spectators.
| sport | Reason | Hrs spent |
| -- | -- | -- |
| valley ball| Playing a valleyball is help for physical and menatal health. It improves hand and eye coordination and increases body flexibilty. |  5Hrs|
| Cricket | Playing Cricket will definately help for the physical strength and also increases team cordination.   | 3Hrs |
| Hockey | playing hockey will increase theb concentration and also help for the leadership qualities.  | 2Hrs |
| Tennis | Playing tennis is good for maintaining health, fitness, strength and agility | 8Hrs |

---
Pithy Quotes
> "We live in a society exquisitely dependent on science and technology, in which hardly anyone knows anything about science and knows anything about science and technology." - *Carl Sagan*

> "Everything is theoretically impossible until it is done." - *Robert Heinlein*

---
Code Fencing

>Using function and if statement in SCSS

[Functional Programming Functions]<https://stackoverflow.com/questions/57025743/using-function-and-if-statement-in-scss>

```
/// Apply `$function` with `$args` to each item from `$list`.
/// @author Kitty Giraudel
/// @param {List} $list - List of items
/// @param {String} $function - Function to apply to every item from `$list`
/// @param {Arglist} $args - Extra arguments to pass to `$function`
/// @return {List}
/// @throw There is no `#{$function}` function.
@function walk($list, $function, $args...) {
  @if not function-exists($function) {
    @error "There is no `#{$function}` function.";
  }
  
  @for $i from 1 through length($list) {
    $list: set-nth($list, $i, call($function, nth($list, $i), $args...));
  }
  
  @return $list;
}

```
[Snippet Quick link]<https://css-tricks.com/snippets/sass/functional-programming-functions/>