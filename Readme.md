# Blue Sky
## iOS Weather Application

### Blue Sky is a weather application built using best practices with Swift 5, UIKit and XCode 12.  In order to demonstrate scalable, reusable code that is easily reviewed by peers. 

## What's Inside?

- Vectorized assets
- No storyboards! 
- Stack Views
- Protocol-Delegate Pattern
- JSON Parsing with Codable
- Swift Unit Testing _TDD!!_
- Styling text with NSAttributedString _easy and efficent!_ 

## Benefits of the techniques used here

- Auto layout uses mathematical equations to place UI elements on screen, in the background it is 
simple linear algebra that brings views to life. This is how the application can be rendered on 
multipe screen sizes with programatically defined layouts. The anchoring system 
(top/leading/trailing/bottom) in autolayout is key here. 
- Since storyboards show up as an .xml file during the code review process, programatic layouts are much 
easier to collaborate on. 
- Stack views are Apple's way of streamlining a layout for a collection of views (for a column or row). 
This allows us to define fewer constraints, and get the same results. UIStackView works perfectly for 
certain elements of BlueSky. Not to mention, this leads to fewer lines of code and therefore a more
efficient development workflow.
