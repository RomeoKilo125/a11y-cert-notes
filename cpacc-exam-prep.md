# CPACC Exam Prep

## Benefits of Accessible Design

1. Discuss ways in which designing for a11y benefits people with disabilities, society, and businesses.
    - accessibility isn't just for people with permanent disabilities, it is useful in a variety of ways for all people.
    - (e.g. curb cuts help wheelchair users, cyclists, delivery people with handtrucks etc., or voice controls, good for people with motor disabilities, or someone who is cooking and has dirty hands.)
    - accessiblity is good for society at large too, because when people can do things for themselves, they don't need others. that frees up those others to do for *them*selves
    - good for business, because people will take their patronage to places that make it easy to do business.

1. Provide reasoning that justifies accessible design.
    - the only reason you really need: it makes peoples' lives better.
    - improves SEO
    - improves compatibility
    - improves reputation
    - avoids lawsuits

## Web Accessiblity Principles

1. Name the four main principles of web accessibility
2. Describe how each principle is applied to web design and development.

- Perceivable: making the _output_ of the web work for multiple human senses
  - sight: screen with good contrast, text alternatives to speech etc.
  - sound: screen reader etc.
  - touch: braille displays (usually works in conjunction with screen reader)
- Operable: making the _input_ work for multiple modes
  - mouse and keyboard
  - keyboard only (this will make your site almost universally operable)
  - touch (effectively mouse only)
  - voice (good ids, alt text, semantic html)
  - In, Within, Through, and Out
  - when scripting pay attention to focus and timeouts
- Understandable: making _content_ and _interfaces_ that people can comprehend
  - the easiest win: specify the language
  - two keys, consistenct and predictability
  - simplified text (avoid jargon or slang)
  - line spacing
  - alternative forms of content presentation, (audio or visual) that provide content directly and clearly
  - w/r/t user input, provide instructions, hints (* for required fields)
  - provide clear feedback (success/error messages)
- Robust: ensuring _compatibility_ with many user agents (devices, browsers, AT's etc)
  - unfortunately you have to draw a line somewhere, it's impossible to support EVERYTHING.
  - use standad semantic markup
  - [W3C HTML Validator](http://validator.w3.org/)
  - [W3C CSS Validator](http://jigsaw.w3.org/css-validator/)
  - use ARIA, that's what it's there for. (aria-expanded, aria-label for announcers etc)

## Universal Design for the Web


