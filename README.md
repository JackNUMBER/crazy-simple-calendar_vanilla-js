# Crazy Simple Calendar - Vanilla JS
A light and simple calendar in Vanilla JS. You can use .scss file to edit style.

_You don't need jQuery or other._

Demo: http://codepen.io/jacknumber/pen/RWLyQW

![Alt text](http://i.imgur.com/Dmm8HMm.png)

## 2 variations
One start by Sunday, as usual in Javascript. The other start by Monday, very useful. 

Why 2 versions? Because I want keep it very simple, no unused features.

## How to
Include .min.js (0.99 Ko) file into your page:

    <script src="crazy-simple-calendar.min.js"></script>

And use this to call the calendar:

    document.getElementById('Calendar').innerHTML = calendar();

That's it! Simple.

## Params
    Calendar(month, year)
- `month` Month number follows real chronology (1 = January, 12 = December).
- `year` Year uses index origin 1 too (1968 = 1968)

If you don't provide params, it will display current month. Easy!
