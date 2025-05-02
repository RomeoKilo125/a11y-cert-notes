# CPACC Exam Prep

## Benefits of Accessible Design

1. Discuss ways in which designing for a11y benefits people with disabilities, society, and businesses.
    - accessibility isn't just for people with permanent disabilities, it is useful in a variety of ways for all people.
    - (e.g. curb cuts help wheelchair users, cyclists, delivery people with handtrucks etc., or voice controls, good for people with motor disabilities, or someone who is cooking and has dirty hands.)
    - accessiblity is good for society at large too, because when people can do things for themselves, they don't need others. that frees up those others to do for *them*selves
    - good for business, because people will take their patronage to places that make it easy to do business.

2. Provide reasoning that justifies accessible design.
    - the only reason you really need: it makes peoples' lives better.
    - improves SEO
    - improves compatibility
    - improves reputation
    - avoids lawsuits

## Web Accessiblity Principles

### Name the four main principles of web accessibility
	
- Perceivable
- Operable
- Understandable
- Robust

### Describe how each principle is applied to web design and development.

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

### Identify challenges people with diabilities face while using the web.

- images
- low contrast
- color communicating meaning
- video without captions
- interactive elements that are inaccessible via keyboard
- inconsistent and overly complicated layouts

### Discuss ways in which universal design can be utilized to make web content accessible based on different types of disabilities.

#### Basic Layout

- heading layout and hierarchy
- logical tab order
- focus indicator (don't remove the default unless you replace it with something better
- add good alt text
- tables are data tools. not layout tools

#### Content

- ensure contrast is adequate
- have captions and/or transcript for all video
- links should clearly state where they go
- label form controls
- Use ARIA effectively:
	- name
	- role
	- state
	- value
	- often this is built into html tags but for dynamic elements, they need to be updated.

#### Navigation and dynamic content

- pay attention to dynamic focus when using JavaScript
- everything should be accessible via keyboard
- be consistent with help and navigation

#### PDF Documents

- add markup to PDFs (tagged PDF)
- only available through certain authoring tools (Acrobat Pro?)

## Universal Design for the Physical World

### Explain the concept of universal design for the physical world

	Universal design is the idea that a single design should be usable by everyone. There needn't be different toilets for different species. Let's build one that everyone can use.

### Name the seven principles of universal design.

1. Equitable Use
	- design should be useful for everyone. If possible it should be usable in the same manner.
2. Flexibility in Use
	- design should provide a variety of options for the use of its features.
3. Simple and Intuitive Use
	- the purpose of the design should be easy to understand. Background, language, experience should not hinder understanding and/or use.
4. Perceptible Information
	- Information about the design should be perceivable to everyone; providing a variety of sensory modalities for receiving the the information.
5. Tolerance for Error
	- The design should reduce chances of accident or unintentional side effects
6. Low Physical Effort
	- The design should require little to no physical effort to use. (implicitly redundant with Equitable?)
7. Size and Space for Approach and Use
	- Design should be of sufficient size to allow anyone to use its features.

### Provide examples of universal design princples in the physical world

- curb cuts
- tactile pedestrian paths
- auditory crossing signals
- automated doors
- RAMPS
- handrails on stairs


