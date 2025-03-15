HTML

Key important notes: 
Website for texts: Hipster Ipsum
website for images: unsplash.com
website for images illustrations: unDraw
website for icons: ionicons
website for emojis: react-emojis
website for developer: mdn => eg: html form inputs mdn to check for a specific topic.
website for video editing: descript
website for web layout: Dan's UX Review: wireframe

CSS KEY WEBSITES:
website for text: font size(scale factor => 1.25) => typescale.com 
website for font: fonts.google.com
website for colors: htmlcolorcodes.com
google => color picker
google => open color (fav)
google => tailwind colors
google => coolors.co => with freedom, use tint and shades generator


hr is less common in modern website while br is.
another method iss used to achieve it(hr).
we always use br in a sentence to break word(s)or character(s), maybe paragraph, heading or whatever...

CSS-text

Text Styling:
fw => 100, 200, 300, 400, 500, 600, 700, 800, 900
400 => normal & default for most text, 500 => medium & 700 => bold & default for headings

FONT-WEIGHT GUIDANCE: HEADINGS SHOULD BE 500-900 AND OTHER TEXT 300-400

td => line-through, overline, underline & default for anchor element and none & default for most elements 
style values default => solid

TEXT-DECORATION GUIDANCE : ALWAYS REMOVE UNDERLINE FROM ANCHOR TAGS AND VERY RARELY USE TEXT-DECORATION

no text-decoration instead style with weight and color

fs => normal & default, italic, oblique, oblique 10deg

FONT-STYLE GUIDANCE: CAN SOMETIMES BE USED TO DRAW ATTENTION
NOTE: I PREFER USING WEIGHT AND COLOR BUT YOU CAN USE "ITALIC" AS WELL

tt => none & default, uppercase, lowercase, capitalize & first letter of each word is capitalized.

TEXT-TRANSFORM GUIDANCE: STICK WITH SENTENCE CASE => FIRST LETTER OF FIRST WORD IN A SENTENCE IS UPPERCASE 

ls => none, disc & default for unordered lists, circle, square decimal & default for ordered lists.

LIST-STYLE GUIDANCE: ALWAYS SET LIST-STYLE TO NONE WHEN HEY ARE USED FOR STRUCTURAL PURPOSES

Text Spacing : 
ta => left & default, considered easier to read for paragraphs of text, center & often used for headings, right & justify & every line in a paragraph takes up full width of containing box

Block Elements => text can move(space to move) while text-align applied but
Inline Elements => text can't move because no space

TEXT-ALIGN GUIDANCE: DON'T JUSTIFY, LONG BLOCKS OF TEXT SHOULD BE LEFT-ALIGNED AND DO NOT CENTER LARGE BLOCKS OF TEXT

lh => unitless & just a number that multiplies the font size & commonly used, percentage, pixels & ems

LINE-HEIGHT GUIDANCE: HEADINGS SHOULD BE LES THAN 1.5 AND REGULAR TEXT 1.5 TO 2 TO IMPROVE READABILITY

ls => pixels & commonly used, percentage, ems(no unitless value)

LETTER-SPACING GUIDANCE: WE OFTEN APPLY A SMALL NEGATIVE PX VALUE TO HEADINGS TO IMPROVE READABILITY


Text Size:
ABSOLUTE UNITS => SIZE IS FIXED AND DOES NOT CHANGE IN RELATION TO PARENT ELEMENTS (px & commonly used, pt, in cm & mm => uncommon)

RELATIVE UNITS => SIZE IS BASED ON THE SIZE OF A PARENT ELEMENT AND ADJUSTS PROPORTIONALLY TO CHANGES IN THE PARENT ELEMENT (%, em, rem, vh, & vw)

FONT-SIZE GUIDANCE: REGULAR TEXT SHOULD BE 16px-32px AND HEADINGS CAN BE GREATER THAN 60px
USE A TYPE-SCALE WHICH PROVIDES A STRUCTURED HIERARCHY OF FONT SIZES TO CREATE VISUAL CONSISTENCY AND LIMITS CHOICES
62px => h1
48px => h2
40px => h3
32px => h4
24px => h5
20px => p
16px => a
12px => small

Font Family: 

TYPEFACE => CHARACTERISTICS WITH CONSISTENT VISUAL CHARACTERISTICS
TYPEFACES ARE ORGANISED INTO GROUPS:

SERIF: Extra Details On The End Of Strokes => Times
SANS-SERIF: Straight Ends And Much Cleaner => Arial => web dev => favorite
MONOSPACE: Letters Are The Same Width => Courier New
CURSIVE: Joining Strokes Or mimic Handwriting => Comic sans ms
DISPLAY: Attention Grabbing And Artistic => Impact

FONT GUIDANCE: TO PLAY IT SAFE PICK A POPULAR SANS-SERIF(very popular choice) FONT & SELECT ONE OR TWO FONTS, NO MORE


  1. ROBOTO
  2. OPEN SANS
  3. MONTSERRAT
  4. POPPINS5(1 of fav)
  5. INTER

Color: 

COLOR VALUES CAN BE REPRESENTED IN EITHER RGB OR HEXADECIMAL(hex is most commonly used) NOTATION
THIS NOTATION IS USED ACROSS CSS FOR SPECIFYING COLORS FOR TEXT, BACKGROUNDS, BORDERS, SHADOWS AND MORE

SHADES OF GREY => WHEN ALL THREE CHANNELS OF RGB HAVE THE SAME VALUE WE GET A SHADE OF GRAY.
FOR EG: RGB(64, 64, 64) & (#404040)

COLOR GUIDANCE: HAVE AT LEAST 2 COLORS IN YOUR COLOR PALETTE? A PRIMARY AND GREY COLOR
PRIMARY => TINTS, BASE COLOR & SHADES
GREY => CAN BE A DARK VERSION OF A COLOR (TINTS, BASE COLOR & SHADES)

PRIMARY COLORS ARE USED TO HIGHLIGHT IMPORTANT PARTS OF A PAGE AND TINTS AND SHADES CAN BE USED TO CREATE CONTRAST
BACKGROUND => PRIMARY TINT

GREY COLOR WITH TINTS AND SHADES OFTEN USED FOR FONTS
COLOR IS USED THROUGHOUT DESIGN FOR COMPONENTS & SECTIONS

BLUE(base color => blue=>4 or 5 tint=> 1  or 2 & shade => 7, 8 9)

In color theory, base color, shade, and tint refer to specific concepts related to modifying or working with colors. Here's a breakdown:

1. Base Color
Definition: The main or original color you start with. This could be any pure hue from the color wheel (like red, blue, green, etc.).
Use: It serves as the foundation for creating variations like tints, shades, and tones.
2. Tint
Definition: A tint is created by adding white to a base color, making it lighter.
Effect: It reduces the intensity of the color and makes it appear softer or pastel-like.
Example: Red + White = Pink.
3. Shade
Definition: A shade is created by adding black to a base color, making it darker.
Effect: It increases the depth and intensity of the color, giving it a richer, more dramatic appearance.
Example: Red + Black = Burgundy.
4. Tone (Bonus Term)
Definition: A tone is created by adding gray (a mix of black and white) to a base color.
Effect: It softens the color without making it distinctly lighter or darker.
Example: Red + Gray = Muted Red.
Quick Summary
Base Color: The starting color (e.g., pure red).
Tint: Base color + White (lighter version).
Shade: Base color + Black (darker version).
Tone: Base color + Gray (softer or muted version).
Let me know if you’d like examples or a color visualization!

In color theory, primary, secondary, and tertiary colors describe the relationships between colors on the color wheel. Here’s a breakdown:

1. Primary Colors
Definition: These are the fundamental colors that cannot be created by mixing other colors.
Colors:
Red, Blue, and Yellow (Traditional color wheel used in art and design).
In additive color (light-based, e.g., for screens), the primary colors are Red, Green, and Blue (RGB).
Use: Primary colors are the starting point for creating all other colors.
2. Secondary Colors
Definition: These are created by mixing two primary colors in equal proportions.
Colors:
Orange = Red + Yellow
Green = Blue + Yellow
Purple (Violet) = Red + Blue
Use: Secondary colors are used to expand the color palette by combining the basics.
3. Tertiary Colors
Definition: These are created by mixing a primary color with a secondary color that is next to it on the color wheel.
Colors: There are six tertiary colors:
Red-Orange
Yellow-Orange
Yellow-Green
Blue-Green
Blue-Purple
Red-Purple
Use: Tertiary colors add variety and subtlety to color palettes, bridging gaps between primary and secondary colors.
Visual Representation
Imagine a color wheel:

Primary colors are spaced evenly apart.
Secondary colors are between the primary colors.
Tertiary colors fill in the spaces between a primary and its neighboring secondary.
Would you like help visualizing this or applying it to design projects?


CSS-SELECTORS:

ts(type selector) => selects elements based on their tag name.

TYPE SELECTOR GUIDANCE: IT IS USEFUL FOR SETTING GLOBAL(APPLY EVERYWHERE) STYLES TO ENSURE CONSISTENCY.

cascade => flows from one stage to the next
style declared later will take priority
style sheets declared later will take priority


gs & c(grouping selectors & cascading) => selectors can be comma separated to apply shared styles
gs & c => we can use the css cascade to add new rules to previous rules


Limitations with type selectors: sometimes we want to apply specific styles to a single element
ids(the id selector) => selects an element based on a unique id attribute and can only be used once

Limitations with type selectors: sometimes we want to apply specific styles to multiples elements
cs(the class selector) => selects one or more elements based on a class attribute that can be used multiple times

SELECTOR GUIDANCE: CLASSES ARE OFTEN PREFERRED OVER IDS BECAUSE THEY OFFER GREATER FLEXIBILITY AND REUSABILITY
                   IT IS COMMON TO USE TYPE SELECTORS FOR GLOBAL STYLES AND CLASS SELECTORS FOR MORE SPECIFIC VISUAL STYLES 
                   CLASSES FOR COMPONENTS(reusable ui) ARE DESIGNED TO BE COMBINED ON A SINGLE HTML ELEMENT FOR A MODULAR APPROACH TO STYLING

pc(pseudo-classes) => defines styles for a specific state or condition of an html element
pc(pseudo-classes) => a key word with a colon added to the end of a selector
spc(state pseudo-classes(very important)) => dynamic styling based on user interaction & commonly used for hyperlinks 

STATE PSEUDO-CLASSES GUIDANCE: IT IS BEST PRACTICE TO STYLE THE PSEUDO-CLASSES OF ANCHOR TAGS INSTEAD OF STYLING THE ANCHOR ELEMENT DIRECTLY

BAD PRACTICE => a {color: blue;} : GOOD PRACTICE => .btn, a:link, a:visited {color: blue;}, .btn, a:hover, a:active {color: darkblue;} GROUPED AND COVERS ALL STATES

cpc(conditional pseudo-classes(less important)) => styling based on an elements position in relation to other elements
eg: li:first-child, li:last-child & li:nth-child(n)

cs(combinator selectors) => combines two or more selectors to target elements based on their positions relative to each other
eg: div p, div > p, h1 + p & h1 ~ p

ds(descendant selector) => targets all children elements of a parent => eg: div p
dds(direct descendant selector) => targets only direct children elements of a parent => div > p
ass(adjacent sibling selector(next to)) => targets an element directly after another element both nested within the same parent => h1(preceding sibling) + p(adjacent sibling)
gss(general sibling selector) => targets multiple elements directly after another element both nested within the same parent => h1(preceding sibling) ~ p(subsequent siblings)

cs(conflicting selectors) => when styles are applied to the same element using a different type of selector the outcome is determined by specificity.
specificity => determines the priority of a css rule when multiple rules apply to the same element

SPECIFICITY GUIDANCE => IT IS COMMON TO USE THE TYPE SELECTOR FOR GLOBAL STYLES AND THE CLASS SELECTOR TO OVERRIDE THIS FOR SPECIFIC STYLING 

cssi(css inheritance) => properties set on parent elements are passed to their children by default
i & s(inheritance & specificity) => specific selectors will override inherited styles as inherited styles have a very low specificity => .hero-section { color: blue;} will be overrode by p { color: red;}

WHAT GETS INHERITED? => IT IS MAINLY TEXT PROPERTIES THAT ARE INHERITED FROM PARENT TO CHILD: COLOR, FONT-SIZE, FONT-FAMILY, FONT-WEIGHT, FONT-STYLE, LETTER-SPACING, LINE-HEIGHT, TEXT-ALIGN, TEXT-TRANSFORM

INHERITANCE GUIDANCE: => GLOBAL FONT STYLES ARE SET ON THE BODY ELEMENTS SO THAT ALL CHILD TEXT ELEMENTS INHERIT STYLES BY DEFAULT
NEXT, SET GLOBAL FONT STYLES ON TYPE SELECTORS WHICH WILL OVERRIDE INHERITED PROPERTIES
INHERITANCE IS ALSO OFTEN UTILIZED FOR A CONTAINER THAT REQUIRES SPECIFIC TEXT STYLING

INHERITANCE & TEXT-ALIGN => WE'VE ALREADY SEEN TEXT-ALIGN AFFECTS BLOCK-LEVEL ELEMENTS BUT HAS NO IMPACT ON INLINE-LEVEL ELEMENTS

WHEN APPLYING THE TEXT-ALIGN PROPERTY TO A BLOCK-LEVEL PARENT CONTAINING INLINE ELEMENTS, ALL CHILDREN WILL BE IMPACTED

us(the universal selector) => applies styles to all elements

THE UNIVERSAL SELECTOR GUIDANCE: PRIMARILY USED FOR RESETTING DEFAULT PROPERTIES AND IS NOT TYPICALLY USED FOR APPLYING SPECIFIC STYLING

pe(pseudo-elements) => used to style a specific part of an element

cbm(the css box ) => all html elements are treated as a rectangular boxes
                  => each box has it own set of properties

bcp(background color property) => sets the back ground color of an element and applies to the content and any padding

BACKGROUND COLOR GUIDANCE: SOMETIMES USED TO SET THE BACKGROUND COLOR OF ENTIRE PAGE
                           COMMONLY USED TO SET THE BACKGROUND COLOR OF PAGE SECTION
                           COMMONLY USED IN COMPONENTS(REUSABLE UI)

cbm(css box model) => each rectangular box has height and width
dbled(default block-level element dimensions) => by default block-level elements are just big enough to fit its contents vertically and stretches full-width horizontally

diled(default inline-level element dimensions) => by default inline-level elements are just big enough to fit its contents vertically horizontally

w&hp(width & height properties) => the default box dimensions can be overwritten by the width and height properties

BLOCK-LEVEL SIZING GUIDANCE: individual elements => h1, p, ul, li => height => usually do not set height but let it be automatically determined(margins, paddings, & font-size determines) width => usually do not set width which will stretch to fill the parent container

                            : container elements => div, section => height => usually do not set height but let it be automatically determined(margins, paddings, & font-size determines) width => depending on the layout it can be common to set a width
This approach ensures flexibility where content better adapts to different screen sizes 

INLINE-LEVEL SIZING GUIDANCE: width and height can be set on some inline-elements but not others
                              can apply width and height(img(setting height or width will adjust the other dimension automatically to preserve aspect ratio), input, select, textarea, button)

                              can't apply width and height(a(common to use padding to create space around anchor text), span, sub, sub)

p(padding) => padding is the space between the content of an element and its border to improve readability and visual design

PADDING GUIDANCE: COMMONLY USED IN BUTTONS AND TEXT CALLOUTS TO IMPROVE READABILITY
                  COMMONLY USED ON CARDS
                  COMMONLY USED ON INPUTS

b(border) => creates a visible boundary around an html element and can enhance visual appearance and separation from other elements

BORDER GUIDANCE: BORDERS HELP WITH GROUPING RELATED CONTENT
                 INDIVIDUAL BORDERS HELP SEPARATE SECTIONS
                 BORDERS CAN CREATE OUTLINE BUTTONS WHICH ARE COMMONLY USED ALONGSIDE SOLID FILLED BUTTONS
                 IT IS COMMON TO ADD A BORDER ON A FILLED BUTTON WHICH MATCHES ITS BACKGROUND COLOR WHEN USED ALONGSIDE AN OUTLINE BUTTON


br(border radius) => rounds the corners of elements border
hbrw(how border radius works) => a quarter-circle is placed in the corner of an element and the cut out rounds the elements corner
p(pills) => fully rounded corners are created from rectangles by setting border radius equal to half the elements height 
c(circles) => circular elements are created from squares by setting border radius equal to half the elements height 

BORDER RADIUS GUIDANCE: SQUARE CORNERS ARE MORE FORMAL
                        ROUNDING CORNERS CAN BE PERCEIVED AS MORE FRIENDLY
                        FULLY ROUNDING CORNERS CAN BE PERCEIVED AS PLAYFUL
                        IT IS IMPORTANT TO HAVE CONSISTENT ROUNDING ACROSS ALL ELEMENTS

tbd(total box dimensions) => by default the total width and height of a box will be the sum of the content width and height, padding and border
bz(box sizing) => the box-sizing property modifies how the total width and height of an element are calculated                        

BOX-SIZING GUIDANCE: SET THE BORDER-BOX ON THE UNIVERSAL SELECTOR(universal selector => sets border-box on all boxes)

m(margin) => margin is the space outside of an elements border creating distance between it and neighboring elements

MARGIN GUIDANCE: USE MARGIN TO APPLY WHITESPACE BETWEEN GROUPS OF ELEMENTS
                 USE MARGIN TO APPLY WHITESPACE BETWEEN SECTIONS
                 IT IS COMMON TO CONTROL SPACING BETWEEN ELEMENTS WITH MARGIN AND OTHER MORE MODERN TECHNIQUES

SPACING SYSTEM: A PREDEFINED SPACING SYSTEM SIMPLIFIES THE DESIGN PROCESS AND ENSURES CONSISTENCY(5px/10px/20px/25px/30px/40px/50px/60px/70px/80px/90px/100px/100px/125px/150px/200px/250px/300px/400px/500px)  

DISPLAY PROPERTY  => sets how the element is formatted and positioned 
beatbm(block elements and the box model) => block elements follow the box model rules so applying any properties work as expected
ieatbm(inline elements and the box model) => inline elements do not follow the box model rules so applying some properties do not work as expected

ib(inline-block) => combines features of block and inline elements

INLINE-BLOCK GUIDANCE: IT IS COMMON TO APPLY INLINE-BLOCK TO INLINE ELEMENTS SO THEY FLOW INLINE(next to each other)  BUT ALL BOX PROPERTIES(padding, border & margin) CAN BE APPLIED

rie(replaced inline elements) => inline elements where the content is soured externally and is not part of the html markup(img, input, select, textarea)

bdp(browser default properties) => browsers have built-in css default rules that style html elements
cr(css reset => global resets => removes all default margin and padding) => it is very common to strip away the main default browser styles to give us a blank canvas to work from

nc(normalize css) => creates uniform default styles for html elements without removing all styles like a reset does

c (container) => to create a container, a suitable width is chosen to prevent content from excessively stretching on larger screen sizes
ctc(centering the container) => to center the container, calculate the remaining width and distribute the space to margin left and right equally

a(auto) => a value that enables the browser to automatically determine a property's size
        => using the shorthand margin property is concise and more common(width: 1200px; margin: 0 auto;)
mamw(maximum and minimum width ) => ensures elements are responsive for different screen sizes
baie(block and inline elements) => max-width & min-width behave differently depending on the display property of the html element
mwobl(max-width on block elements) => sets the maximum width an element can be while it can still go narrower

MAX-WIDTH BLOCK ELEMENT GUIDANCE: USING MAX-WIDTH ON A MAIN CONTAINER ENSURES CONTENT DOES NOT GO TOO WIDE ON LARGER SCREENS

mwoie(max-width on inline elements) => sets the maximum width an element can be while it won't go narrower

MAX-WIDTH INLINE ELEMENT GUIDANCE: USING MAX-WIDTH ON IMAGES CREATES A RESPONSIVE LAYOUT

mwobe(min-width on block elements & inline elements) => sets the minimum width an element can be while it can still go wider

MIN-WIDTH BLOCK ELEMENT GUIDANCE: USEFUL FOR MAINTAINING A SECTION WIDTH IN A GRID LAYOUT SO IT DOES NOT BECOME TOO NARROW

MIN-WIDTH INLINE ELEMENT GUIDANCE: SOMETIMES USEFUL FOR SPANS AS IT ENSURES TEXT DOES NOT BECOME TOO NARROW & IMPROVES VISUAL CONSISTENCY

mamp(maximum and minimum properties) => max & min width are more commonly used compared to max & min height due to their role in creating responsive layouts

mwvsmh(max width vs. max height) => max width and max height behave in fundamentally different ways(max width => based on its container, so it applies even without content) while(max height => only applies when content exceed the limit)

of(overflow) => controls what happens to content that overflows an element's box 

MAX-HEIGHT GUIDANCE: USED WHEN YOU WANT TO ENSURE ELEMENTS DO NOT EXCEED A CERTAIN HEIGHT
MIN-HEIGHT GUIDANCE: USED WHEN YOU WANT TO ENSURE ELEMENTS MAINTAIN A MINIMUM HEIGHT REGARDLESS OF THE AMOUNT OF CONTENT

css units:
ru(relative units) => are essential for responsive webpages so elements can dynamically adjust for different screen sizes
                   => size is based on he size of a parent elements and adjusts proportionally to changes in the parent element(%, em, rem, vh vw)

p(pixels) => are still used with (border radius, border, letter spacing, logo, max-width & shadows)

p(percentages) => a unit that is always relative to some other value (very common=> relative to a parent width, height, margin, padding)
              => (very few elements => line height)relative to the element itself

PERCENTAGES GUIDANCE => PERCENTAGES ARE USED IN CONJUNCTION WITH MAX-WIDTH ON MAIN CONTAINERS SO THAT THE WEBSITE IS FULLY RESPONSIVE
                     => PERCENTAGES ARE USED IN CONJUNCTION WITH MAX-WIDTH ON STANDALONE IMAGES SO THAT THE WEBPAGE IS FULLY RESPONSIVE
                     => IT IS COMMON TO SET IMAGES INSIDE A GRID OR FLEX CONTAINER TO 100% SO IT FILLS THE CELL AND ADAPTS RESPONSIVELY
                     => THERE ARE CASES WHEN YOU WANT TO SET A BUTTON WIDTH TO 100% SO IT FILLS ITS CONTAINER AND ADAPTS RESPONSIVELY
                     => PERCENTAGE VALUES ARE USED FOR FULLY ROUNDED CORNERS AS PIXELS REQUIRE MANUAL CALCULATION

r(rems) => relative to the root elements font size and are the key ingredient for creating responsive webpages
        => working with a base 10px for rem units makes it simpler when thinking about sizing elements 
REMS GUIDANCE: REMS ARE COMMONLY USED ON FONT-SIZE, MARGINS, AND PADDINGS TO CREATE FULLY RESPONSIVE WEBPAGES

e(ems => not as frequently used as rems) => a relative unit that is more context specific(closer) compared to rems(typography => relative to the font-size of the parent(font-size, line-height, letter-spacing other properties => relative to the font-size of the element itself => width, height, margin, padding))

EMS GUIDANCE: EMS PROVIDE A HIGHER LEVEL OF PRECISION FOR STYLING SMALLER COMPONENTS AS SIZING IS BASED ON FONT-SIZE OF THE ELEMENT ITSELF

vh and vw(view height & view width) => are units that are a percentage of the browsers visible window 

VH AND VW GUIDANCE: VH CAN BE USED ON THE HERO SECTIONS IN CONJUNCTION WITH MIN-HEIGHT SO CONTENT IS ALWAYS ABOVE THE FOLD
                    VW CAN BE USEFUL FOR CREATING RESPONSIVE TEXT WHEN IT IS A MAIN STANDALONE ELEMENT AND DO NOT CONFINED WITHIN A CONTAINER


cv(css variables => also known as custom properties) => allows us to store values to make it easier to maintain consistency and more easily make global style changes

root pseudo-class? => a special pseudo-class selector that matches the root element in a document's hierarchy

css calculations? => perform dynamic calculations when setting values 
variables and calculations? => it is common to use variable and calculations in combination

flexbox? => flexbox is a one-dimensional layout model making it simple to arrange items in rows or columns and distribute space

flexbox has two main components => flex container and flex items
df(display flex) => the display property on a container element will activate flexbox's layout features on children elements

maca(main and cross axis) => The main axis is the primary direction in which flex items are laid out & cross axis determines distribution on secondary axis

fd(flex direction) => controls orientation of the main axis

FLEX DIRECTION GUIDANCE: IN MOST CASES FLEX-DIRECTION IS SET TO ROW OR COLUMN

nf vs fb (normal flow vs flexbox) => when flexbox is applied to a container it takes control of the alignment of children

normal flow => spacing and alignment are determined by inherit properties of block and inline elements
flexbox flow => flexbox overrides default behavior of block and inline elements with spacing & alignment controlled by flexbox properties

normal flow => block and inline elements behave differently in normal flow

nfaa(normal flow and alignment) => applying text-align to a block-level parent will impact both block & inline children through different mechanisms

fb(flex box) => flexbox overrides display behavior of block & inline elements
aas(aligning and spacing) => flexbox offers a powerful way to space and align content

fcs(flex container size) => understanding a flex-container's dimensions is essential for visualising how flex items will be positioned 

jc(justify content) => sets how flex items are positioned along the main axis

JUSTIFY CONTENT GUIDANCE: => OFTEN USED TO ALIGN AND SPACE NAVIGATION BARS
                          => CAN BE USED TO ALIGN ENTIRE SECTIONS
                          => OFTEN USED FOR SPACING AND ALIGNING OF SIMPLE ONE-DIMENSIONAL COMPONENTS

ai(align items) => sets how flex items are positioned along the cross axis     

aiastma(align items & shifting the main axis) => when no height is set on the container, its height is sum of flex item's height & justify content will have no impact
                                              => when height is set on the container, there can be additional space so justify content will have impact 

ALIGN ITEMS GUIDANCE: COMMONLY USED ON NAVIGATION MENUS AND FOOTERS   
                      POSITIONING ITEMS INSIDE A COMPONENT IN A FLEX ROW 

fbatbm(flexbox and the box model) => box model properties can still be used in a flexbox layout to control spacing
gp(gap property => set on flex container) => sets uniform spacing between flex items on the main axis

MARGIN AND GAP GUIDANCE: MARGIN IS USED WHEN YOU WANT DIFFERENT SPACING VALUES BETWEEN FLEX ITEMS
                         GAP IS USED WHEN YOU WANT UNIFORM SPACING VALUES BETWEEN FLEX ITEMS

nfb(nested flexbox) => it is common to have a flexbox layout inside another flexbox layout 
                    => a flex item within a flex container can also function as a flex container itself, allowing for multi-level flex layouts

NESTED FLEXBOX GUIDANCE: COMMONLY USED ON NAVIGATION MENUS AND FOOTERS
                         COMMONLY USED IN SECTIONS AND COMPONENTS                   

flexbox:
CENTRING 
- Centering with flexbox
flexbox offers a modern & flexible approach to centering items vertically and horizontally
- Horizontal centering methods  
Horizontal centering a container
box model=> margin cen be applied left and right to horizontally center child containers => margin: 0 auto;  note: margin is applied on the child container.

flexbox => flex properties make it simple to horizontally center flex items
main axis(in row) => justify-content: center;
main axis(in column) => align-items: center;
note: the flex properties are applied on the flex container.

Horizontal centering content inside a container: 
 Box Model => using padding to crete internal space left and right gives the illusion that content inside a container is center
 padding: 0 200px, note padding is applied on the child container

 Flexbox => box model properties still apply on flex items, so padding can still be used to create internal horizontal space 
 padding: 0 200px, note padding is applied on the flex item 
- Vertical Centering Methods
  
  Vertically centering a container(Parent container has a set height)

box model => there is no easy way to vertically center a child container inside a parent container with a set height

flexbox => flexbox properties make it simple to vertically center flex items when the parent container has a set height
main axis(in row) => justify-content: center;
main axis(in column) => align-items: center;
for this to work, our parent container height set should bigger than child container
note: the flex properties are applied on the flex container.

vertically centering content inside a container(parent container has no set height)
box model => padding can be applied to the top and bottom of the child container, padding: 200px 0; note: the padding are applied on the child container.

flexbox => box model properties still apply on flex items so padding can be used to create internal vertical space, padding: 200px 0; note: flex properties are applied on the flex item.

HORIZONTAL CENTERING GUIDANCE:
1. Horizontally centering a container:
margin is often used to establish a webpage's main container as it is a simple method for horizontal centering
flexbox properties make it simple to horizontally center regular content containers

2. Horizontally centering content inside a container:
Padding is used to create equal internal space left and right around containers like cards and elements like anchor tags
padding can be used to create equal internal space left and right on flex containers

3. Vertical centering guidance:
flexbox properties are often used to vertically center UI elements inside a flex container that has a set height

4. Vertically centering content inside a container:
padding is used to create equal internal space top and bottom around containers like cards & elements like anchor tags

padding can also used to create internal space top and bottom on flex containers

- Traditional centering methods vs. flexbox


FLEX CHILDREN
- Flex items properties
- flex grow
- flex shrink
- align self
- order

Flexbox also has properties that control the behavior and positioning of flex-item

Flex container
display: flex;
flex-direction: column;
justify-content: space-between;
align-items: center;
gap: 2rem;

Flex items
flex-basis:flex;
flex-grow: 0;
flex-shrink: 1;
align-self: center;
order: 2;


flex-grow: determines how flex-items expand to fill extra space in a container based on a set of proportions.

flex-grow: 0; 0 => default value
default behavior is flex-items do not expand

calculates how flex-items can fill the extra space
box 1 fg => 1
box 2 fg => 2
box 3 fg => 0
box 4 fg => 0

total flex-grow = 1 + 2 + 0 + 0 = 3

Flex-shrink: determines how flex-items shrink relative to others in a container where there isn't enough space.

flex-shrink: 1; 1 => default value

flex-shrink => items shrink based on flex-shrink value relative to the total

Align-self:
Sets individual flex items alignment by overriding the flex containers default align-items value
align-self: auto
align-self: stretch
align-self: flex-start
align-self: flex-end
align-self: center
align-self: baseline

Order:
Changes the visual order of flex items independent of heir order in the html markup

FLEX WRAP & ALIGN CONTENT:
flex wrap property
align wrap property
align content values

SHRINKING BEHAVIOR:
If flex items are larger than their container, by default they will shrink to fit inside

FLEX-WRAP:
pushes flex-items onto multiple lines instead of being forced to fit on a silence line when they exceed the container

general block container:
no set height => container expands

container with a set height => rows divide equally

flex wrap will only work if the flex items exceed its container

flex-wrap: wrap;
           no wrap(default); wrap; wrap-reverse

ALIGN-CONTENT(do not confused with align-items)
controls the alignment of flex-items along he cross-axis when there are multiple rows of flex-items.
align-content will only work if only the flex-wrap is enable 
The align-content can only work if the flex-wrap is enable
With the flex-wrap, align-items works if only the align-content is not applied or else it will override the align-items.

general rule of tom: only use the align-content when the flex-wrap is enable.

FLEX-WRAP GUIDANCE(not often required):
wrapping is useful for simple linear layouts when elements need to wrap onto multiple lines.

CSS GRID:
Introduction to css grid
- what is css grid: CSS GRID is a two-dimensional layout model making it simple to arrange items in rows and columns
- css grid terminology: CSS GRID has two main components(grid container(parent) grid items(children))
css grid has two axis(can't change direction of the axis(column axis(vertical)) and row axis(horizontal))
grid line, grid cells(can have no grid items)
Grid rows(horizontal gap) and columns(vertical gap) can have spacing between them
Display Grid: the display property on a container element will activate grid layout features on children elements => display: grid; => declared on the grid container(parent)
By declaring display: grid; by default, it will only have one column
- css grid design guidance 
CSS GRID GUIDANCE: css grid can be used for complex two-dimensional layouts
                   grid is also commonly used for major sections
                   grid is also commonly used for UI elements with consistent spacing in a one-dimensional row or column(could also use flexbox)
- css grid vs. flexbox
FlexBox(smaller ui) => display:flex; one-dimensional(row or column)
- navigation
- footers
- components(buttons, callouts, inside cards)
- hero sections
- forms
Grid(larger ui) => display:grid; two-dimensional(row and column)
- complex 2d layouts
- features
- cards

GRID COLUMNS and ROWS: grid items will appear in a single column by default(the height of grid container is sum of grid items and block elements expand full width) 
- grid template columns & rows
grid template columns => sets the number of columns and width of each
grid template rows => sets the number of rows and width of each
- fractional unit(very commonly used in css grid)
The fraction of available space in the Grid container
- Fractional unit and rows: if the height is set on a grid container, fr units(expected) proportionally distribute space to the grid items
                            if no height is set on a grid container, fr units use the height(unexpected) of the grid items to set height and space on the grid container

- repeat function:used to repeat rows or columns dimensions when they are recurring
- grid column & row design guidance

COLUMN AND ROW GUIDANCE:
columns are often set with fr units and the width of grid container is usually not set but extends width of the page(grid container width extends full width of page)
the number of rows are not usually set but are automatically defined by the number of grid items
the height of the grid container is not usually set but defined by the sum of the height of the grid items
- 3 columns with 6 grid items automatically creates 2 by 3 grid
- grid container width extends full width of page
- height of grid container is sum of height of the content in the grid items

GRIP GAP:
- default spacing between grid items: by default, grid items are placed next to each other with no spacing between them
- gap property: the gap property creates space between grid rows and columns
- gap design guidance
commonly used to space grid items in major sections
commonly used for spacing in card layouts such as testimonials and features

GRID CELL ALIGNMENT: grid items can be aligned inside cells if there is space available
- justify items: aligns grid items inside a grid cell along the row axis
- align items(same as flexbox): aligns grid items inside a grid cell along the column axis
- grid cell alignment design guidance: it is common to use grid alignment properties when one grid item is larger than another
                              : it is common to use grid and flexbox in parallel to achieve more precise control of layout(grid controls overall structure and flexbox controls alignment inside grid item)

GRID ALIGNMENT: entire grid tracks can be aligned and distributed when there is extra space in the grid container
- justify content(same as flexbox): aligns entire grid columns along the row axis
- align content(same as flexbox): aligns entire grid rows long the columns axis
- items vs. content

GRID ITEMS 
           
- placing grid items: grid items are automatically placed in a grid based on the order they 
appear in the html
placing grid items Guidance:
  grid items an be moved to different cells  
   placing grid items is used to achieve specific layout(text should follow image for a semantic aspect)
- spanning grid cells: grid-row and grid-column can be used to have grid items span multiple rows or columns 

spanning grid cells GUIDANCE:
grid cells can be spanned to create visually interesting designs
- aligning grid items: grid cell alignment can be overridden for individual items(not too common)


Responsive Design:
INTRO TO RESPONSIVE DESIGN

- Responsive design : webpages were originally designed only for desktop computers, as they were he only devices available to access the internet
  Today there are a variety of devices with different screen sizes so webpages need to adapt for a more functional user experience
  webpage appears different between different devices(desktop, laptop, tablet, mobile)
- media queries: applies styles o a webpage based on specific conditions
at-rule(@media) condition(max-width: 500px) {
  h2 {
    font-size: 14px; (when page is less than 500px apply these rules)
  }
}

note: cascade style: smaller screen always last(descending order)
- relative units: elements scale proportionally based on parent container(percentages) size or scalable reference points(rems)
REMS INSIDE MEDIA QUERY CONDITIONS: the rem value inside a media query condition is(inside brackets) always based on the default browser font sizes(16px) 
css: 62.5% * 16px = 10px (4rem = 40px and 2rem = 20px) => use 10px instead 16px because it is easier to work with 10px.
media query condition: (max-width: 31.25rem ) = 1rem = 16px(default browser font size=> 31.25rem * 16px = 500px)
(max-width: 1000px = 1000 / 16px = 62.5rem)

REMS INSIDE MEDIA QUERIES: rem values scale proportionally, adjust both existing and new values based on the updated root font size

css: html {           media query: html {font-size: 50% } => 50% * 16px = 8px (1rem = 8px)  font-size: 62.5% } => 62.5% * 16px = 10px (1rem = 10px)
Existing properties using rems: all properties using rems will automatically shrink to 80% of their original size

when adding new rem values inside a media query select values you would use for the base case and it will scale automatically (a {padding: 2rem 4rem} => think as if: 1rem = 10px not 1rem = 8px even though the root html is set to 50% in the media query)

New properties inside media query: new properties added with rem will be based on new pixel value, not 10px
- fluid layouts: using flexbox & css grid allow layouts to dynamically adjust in size and position easily

BREAKPOINTS:
- what are breakpoints: a specific screen width where a website's layout changes
- selecting breakpoints: selecting breakpoints for specific devices is impractical as there are too many to cater for 
knowing the ranges of common device screen sizes is helpful in thinking about breakpoints(576px = phone portrait(xs) > 768px = phone landscape(sm) > 1024px = tablets(md) > 1280px = small laptops(lg) > 1536px = large laptops(xl) above = large screens(2xl) )
note: ultimately, selecting breakpoints should be design-led & determined by observing where the layout naturally 'breaks'
note: it is recommended to have more than 2 breakpoints
when using max-width in media queries, there's no need to set a maximum range because styles will be applied automatically(styles not inside any media query applied automatically)

CSS & Physical PIXELS:
- what is a pixel: a single point of light on a digital display
- physical pixels: a pixel does not have a fixed length and varies between screens
- css pixels: a css pixel has a length of 1/96 inch (0.0104)
- pixels in dev tools vs. devices: pixel values in dev tools are not the same as device pixel values
css pixels are scaled depending on screen resolutions
scaling across different devices happens automatically

POSITIONING
NORMAL FLOW: elements occupy their own designated 'slot' on the page which allows them to be surrounded by other elements
- Static positioning: the element follows the normal document flow(position: static; default)
- Relative positioning: the element follows the normal document flow but can be offset relative to itself(slot remains/ element can move around relative to its original position)
other elements remain in position as the slot f the relatively positioned element remains present
in its own 'layer' & can move around(offset properties => offset properties are used to shift the element from its reference point. note: position has a value other than static)
Offset properties: top: 20px; left: 10px; bottom: 40px; right: 30px;
shift ___ away from the ___ of the reference point
- Absolute positioning: the element is removed from the normal documentation(slot removed/green box does dot exist for these elements as 'slot' has been removed in its own 'layer' & can move around)
when positioning an absolute positioned element the reference point is the root html element
more commonly, the reference point is et by the nearest ancestor with a non-static position
- Fixed positioning: 
  absolute positioning:
  the element is removed from the normal document flow => fixed positioning: absolute positioning, but the element remains fixed relative to the viewport and is unaffected by scrolling(fixed to viewport)
- Sticky positioning: the element is normal flow until a certain scroll point when it then becomes fixed(needs action)

POSITIONING GUIDANCE: absolute positioning is more commonly used than(slot is removed. so no unexpected gaps in layout) relative because it removes elements from the document flow.
absolute positioning should be used as a last resort for very specific cases as it makes responsive design more challenging

fixed positioning is used for elements that need to be absolute positioned but also need to remain visible when the user scrolls(inter con => chat window)

sticky positioning is ideal for nav bars, as they stay at the top in normal flow and then becomes fixed when user scrolls

Z- INDEX & STACKING CONTEXT:
NORMAL FLOW: most web layouts have elements in the same 2d plane and do not overlap
elements can overlap in the same plane with the stacking order being determined by the order they appear in html

Z-INDEX: the z-index property controls the vertical stacking order of positioned elements
STACKING CONTENT: a positioned element with z-index creates a new stacking context, where its children are stacked independently of other elements

TRANSFORM:
- transform property: applies visual transformations to an element like scaling, rotating, translating and skewing
scale: resizes element horizontally & vertically(x-axis scale factor, y-axis scale factor)
skew: distorts element by slanting it horizontally & vertically(x-axis slant angle, y-axis slant angle)
rotate: rotates element around its center(angle)
translate: moves element horizontally & vertically from its position(x-axis translation, y-axis translation)
- transformation functions
- positioned elements & translate: using positioning and translate together provides precise control over element placement

TRANSFORM GUIDANCE: scale is often used when hovering(triggered by state change) over image to create a dynamic visual effect
                    translate is used on positioned modals to achieve precise centering within their containers
                    translate is used on positioned alerts to achieve precise alignment in the top right corner

SHADOWS & TRANSITIONS:
- shadows: 
* how shadows work: moving light in the same plane as the table moves the shadow horizontally and vertically on the floor
                  moving light up and down creates a blur resulting in edges that appear soft or sharp (blur radius)
                  the size of the table impacts the size of the shadow(spread radius)
* shadow property
* shadow design guidance:shadows can be used to add depth and dimension to a design to create separation between ui elements
shadows should be light, as darker shadows can crete a harsh and unnatural appearance in the design (shadows should be light and not too dark)

smaller shadows are idea for enhancing smaller components like buttons and cards which add subtle depth
medium-sized shadows can be used for larger components, helping them standout
large shadows are used when an element should appear to be floating above the rest of the design
* flat design vs. shadows: flat design uses border and background colors to achieve separation instead of shadows
shadows should not be used too often, as overuse can ake a design look cluttered and overwhelming

TRANSITIONS:
- transitions: when an element moves between states the changes occur immediately
               are used to create a smooth, gradual change to an elements properties when it undergoes a state change
- timing functions: controls the speed of the animation

ease: starts slowly, speeds up and then slows down
linear: consistent speed start to end
ease-in: starts slowly and accelerates to the end
ease-out: starts quickly and slows down towards the end
ease-in-out: starts slowly, speeds up in the middle and slows down at the end

  


- transitions design guidance
transitions on buttons add subtle visual feedback
            can make card components 'pop'

stop: 6:14:40/8:32:46