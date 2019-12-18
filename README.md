PHP Accessibility Conformance Report
=======================================

VPAT® Version 2.0 - October 2017

Name of Product:
----------------

PHP

Product Description:
--------------------

PHP is a popular general-purpose scripting language that is especially suited to web development.
This assessment is limited to the supporting documentation at https://php.net/manual since there is no user interface nor any sort of hardware in the product.

Date:
-----

17-Dec-2019

Contact Information:
--------------------

[Rasmus Lerdorf](mailto:rasmus@php.net)

### Evaluation Methods Used:

Testing based on general product knowledge

### Accessibility Standards/Guidelines

This report covers the degree of conformance for the following accessibility standard/guidelines:

*   WCAG 2.0 (ISO/IEC 40500)
*   Section 508 as published in 2017, at https://www.Section508.gov

WCAG 2.0 Report
---------------

Table 1 also documents conformance with:

Section 508: Chapter 6 - 602.3 Electronic Support Documentation

Note: When reporting on conformance with the WCAG 2.0 Success Criteria, they are scoped for full pages, complete processes, and accessibility-supported ways of using technology as documented in the WCAG 2.0 Conformance Requirements.

### Table 1: WCAG Conformance Criteria

| Criteria | Conformance Level | Remarks and Explanations |
| -------- | ----------------- | ------------------------ |
| 1.1.1 Non-text Content (Level A) | Not Applicable | The product has no non-text content |
| 1.2.1 Audio-only and Video-only (Prerecorded) (Level A) | Not Applicable | The product has no audio/video content |
| 1.2.2 Captions (Prerecorded) (Level A) | Not Applicable | The product has no audio/video content |
| 1.2.3 Audio Description or Media Alternative (Prerecorded) (Level A) | Not Applicable | The product has no audio/video content |
| 1.3.1 Info and Relationships (Level A) | Supports | * Document uses headings and group relationships<br> * Document components have appropriate labels<br> * Groups of components are marked and their relationships described<br> * Stylesheets are used for device-specific layout<br> * Lists are contained within a List component<br> * Tables are contained within a Table component and include row and column headers where appropriate |
| 1.3.2 Meaningful Sequence(Level A)     | Supports | The accessibility hierarchy is logical |
| 1.3.3 Sensory Characteristics(Level A) | Supports | Documentation does not refer to things solely based on their sensory characteristics such as shape, size, visual location, orientation, color, or sound |
| 1.4.1 Use of Color(Level A)            | Supports | No critical information is conveyed by color |
| 1.4.2 Audio Control(Level A)           | Not Applicable | The product has no audio/video content |
| 1.4.3 Contrast (Minimum) (Level AA)    | Supports | Text and images of text have a contrast ratio of at least 4.5:1 |
| 1.4.4 Resize text(Level AA)            | Supports | Text resizes to any size due to the stylesheets used |
| 1.4.5 Images of Text(Level AA)         | Supports | Images have meaningful alternative text and repeated images and icons have a consistent alternate text |
| 2.1.1 Keyboard(Level A)                | Supports | In additiona to normal web browser keyboard controls, the documentation includes a simple custom set of controls |
| 2.1.2 No Keyboard Trap (Level A)       | Supports | No mechanisms to prevent normal focus navigation are present |
| 2.2.1 Timing Adjustable(Level A)       | Supports | There are no time limits |
| 2.2.2 Pause, Stop, Hide (Level A)      | Supports | There is no moving, blinking, scrolling, or auto-updating information |
| 2.3.1 Three Flashes or Below Threshold(Level A) | Supports | There is no screen flickering or flashing of any kind |
| 2.4.1 Bypass Blocks(Level A)           | Supports | Navigation components are in separate blocks and are easily bypassed with screen readers |
| 2.4.2 Page Titled(Level A)             | Supports | Every page has an appropriate and relevant title |
| 2.4.3 Focus Order(Level A)             | Supports | Keyboard controls provide a logical way to navigate between focusable components |
| 2.4.4 Link Purpose (In Context)(Level A) | Supports | The text around links sufficiently describe their purpose |
| 2.4.5 Multiple Ways(Level AA)          | Supports | * Pages can be found via a search on each page<br> * Simple keyboard controls let you move between pages |
| 2.4.6 Headings and Labels(Level AA)    | Supports | * Headers describe the topic or purpose of the content below them<br> * Labels describe the purpose of the associated field |
| 2.4.7 Focus Visible(Level AA)          | Supports | |
| 3.1.1 Language of Page(Level A)        | Supports | Page locale/language is properly set through various mechanisms |
| 3.1.2 Language of Parts(Level AA)      | Supports | Parts locale/language is properly set |
| 3.2.1 On Focus(Level A) | Supports | Changing focus does not result in any change to content displayed on the page |
| 3.2.2 On Input(Level A) | Supports | Input does not result in any change to content displayed on the page |
| 3.2.3 Consistent Navigation(Level AA) | Supports | Pages are grouped logically and with simple navigation with repeated navigation mechanisms |
| 3.2.4 Consistent Identification(Level AA) | Supports | Images and controls are used and identified consistently throughout the product |
| 3.3.1 Error Identification(Level A) | Supports | Input errors are described logically |
| 3.3.2 Labels or Instructions (Level A) | Supports | Labels are provided with user input elements |
| 3.3.3 Error Suggestion (Level AA) | Supports | Input errors result in suggested alternatives |
| 3.3.4 Error Prevention (Legal, Financial, Data)(Level AA) | Supports | No legal/financial data is collected and all actions are easily reversible |
| 4.1.1 Parsing(Level A) | Supports | Markup includes begin/end tags, are properly nested, validates and are not used for visualization |
| 4.1.2 Name, Role, Value (Level A) | Supports | Name, role and value state information is provided by the standard web browser mechanisms |


Section 508 Report
------------------

### Chapter 3: Functional Performance Criteria (FPC)

| Criteria | Conformance Level | Remarks and Explanations |
| -------- | ----------------- | ------------------------ |
| 302.1 Without Vision | Not Applicable | The product does not rely on equivalent functionality |
| 302.2 With Limited Vision | Not Applicable | The product does not rely on equivalent functionality |
| 302.3 Without Perception of Color | Not Applicable | The product does not rely on equivalent functionality |
| 302.4 Without Hearing | Not Applicable | The product does not rely on equivalent functionality |
| 302.5 With Limited Hearing | Not Applicable | The product does not rely on equivalent functionality |
| 302.6 Without Speech | Not Applicable | The product does not rely on equivalent functionality |
| 302.7 With Limited Manipulation | Not Applicable | The product does not rely on equivalent functionality |
| 302.8 With Limited Reach and Strength | Not Applicable | The product does not rely on equivalent functionality |
| 302.9 With Limited Language, Cognitive, and Learning Abilities | Not Applicable | The product does not rely on equivalent functionality |

### Chapter 4: Hardware

These criteria are all Not Applicable because the product is not Hardware.

### Chapter 5: Software

These criteria are all Not Applicable because the product is not an application.

### Chapter 6: Support Documentation and Services

| Criteria | Conformance Level | Remarks and Explanations |
| -------- | ----------------- | ------------------------ |
| *601.1 Scope* | Heading cell – no response required | Heading cell – no response required |
| *602 Support Documentation* | Heading cell – no response required | Heading cell – no response required |
| 602.2 Accessibility and Compatibility Features | Supports |  |
| 602.3 Electronic Support Documentation | See WCAG 2.0 section | See information in WCAG section |
| 602.4 Alternate Formats for Non-Electronic Support Documentation | Not Applicable | No non-electronic documentation |
| *603 Support Services* | Heading cell – no response required | Heading cell – no response required |
| 603.2 Information on Accessibility and Compatibility Features | Not Applicable | No support services |
| 603.3 Accommodation of Communication Needs | Not Applicable | No support services |

