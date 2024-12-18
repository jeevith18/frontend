types of css:
1. inline css
2. external css
3. internal

selector:
1. id (#welcome)
2. class (.text)
3. class + tag (a.h1)
4. tag (h1)
5. universal (*)
6. grouping (h5,p,.text,#welcome)

borders:
1. important thing is border-style
2. ridge, groove, inset, outset

Hirarchy:
Margin
 border
  padding

Height and Width:
we can inherit the property of the parent to the child via keyword inherit

To Use:
height
width
min-height
max-height
min-width
max-width


Recommended to use sans-serif (helvetica)
Text desing:
1. text-align: justify
2. text-align: centre
3. text-decoration: line through
4. text-decoration: underline
5. text-decoration: overline
6. text-decoration-line: overline
7. text-decoration-style: dashed
8. text-transform: capitalize, uppercase, lowercase
9. text-shadow: 5px, 5px, 5px red
10. line-height: 5px
11. word-spaing: 5px

Font:
1. font-family:
2. font-style: italic, oblique
3. font-weight: 100px, bold, bolder, lighter
4. font-variant: small-caps

Tables:


Priority in css styles:
!important
inline
css stylesheet

opacity: --> transparency
border-radius -->

Position:
1. static
2. relative
3. absolute
4. sticky
5. fixed

Overflow:
1. hidden
2. visible
3. auto
4. scroll
5. overflow-x
6. overflow-y

z-index:
1. z-index = -1 [ This will make the tag (Eg:p) to go behind the actual tag, for this to work we need to set position=relative not static]

Float:
CSS Float: Positioning Elements

The float property in CSS is used to position an element to the left or right of its container, allowing text and inline elements to wrap around it. This is a fundamental technique for creating layouts, especially those that involve images and text.

.float-left {
  float: left;
  width: 200px;
  margin-right: 20px;
}

Display:
1. inline
2. block
3. none