# Fantastic CSS and Where to Find it

CSS is a strange beast: resilient, declarative, contextual, and very unlike JavaScript. If you fight against its nature, CSS can be frustrating. If you can tame it, however, it can be a powerful ally. Come embrace the nature of CSS so you can work with it instead of fearing it.

# Description
When you approach CSS with a JavaScript-centric mindset, you may find yourself frustrated. But if you re-center your thinking, it will do a lot of the hard work for you, like magic.

In this talk, we’ll look at several common tasks in CSS. I’ll show you not just how to build them, but also how to think about the problem in the first place. We’ll look at issues like vertical centering, controlling element heights, and working with animations. Instead of focusing only on specific end-results, I’ll show you how to approach CSS as a system of constraints.

Come learn to get comfortable with CSS. Learn to work with the grain of the web instead of against it. Learn to understand this fantastic beast.

## Misc thoughts

* Resilience. Rule of least power. Pull out chunks and it still works.
* abstract rules; unknown content; unknown medium. CSS does work for you - document flow, etc
* Declarative. CSS does just what you say. CSS doesn’t just do what you say.
* CSS in a system of constraints. In JS, you tell the computer what to do. In CSS, you sometimes need to tell it what *not* to do.
* It’s easy. It’s hard as @$&+
* It defies componentization. You must style elements together, in conjunction. You must think about the relationship between elements on the page. CSS is contextual.
  * container controlling spacing
  * document flow
  * why is it like this? -> Because that’s how design works

## Misc examples:

* "what not to do": overriding list UA styles, applying max-width
* animated nav menu (from book) - deeply-nested relationship
* vertical centering: focus less on the result you want and instead on the constraints needed to achieve it
  * navbar & nav
* using ems for vertical alignment, sizing
* Grid repeat/minmax
* sneak peak at color-mod()?
* feature queries/media queries
