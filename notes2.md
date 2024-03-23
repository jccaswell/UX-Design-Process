# UX/UI Website Design Process

## Welcome / Introduction

UX/UI Website Design Process

Joseph C. Caswell, Technical Solutions Consultant, TPM, Inc.

<div style="page-break-after: always"></div>

## Overview of what will be covered

High level overview of the UX/UI design process geared towards anyone with a new or existing DriveWorks implementation.

- [What is UX/UI Design and why should you care?](#what-is-ux-design)
- [The importance of Accessibility](#accessibility)
- [The Design Process Roadmap](#the-design-process-roadmap)
- [Tools of the trade](#flow-diagram-software)

<div style="page-break-after: always"></div>

## What is UX Design?  

UX Design is the process of creating products that provide meaningful and relevant experiences to users. This involves the design of the entire process of acquiring and integrating the product, including aspects of branding, design, usability, and function.  

UX Design is focused on the user’s journey to solve a problem, not just the interface.

Holistic design of the experience from cradle to grave

Analogous to an engineer designing an entire car

- What size, what region, what price, what features, etc  
- How does it make the driver/passenger feel

<div style="page-break-after: always"></div>

## What is UI Design?

UI Design is the process of making interfaces in software or computerized devices with a focus on looks or style. Designers aim to create designs that users will find easy to use and pleasurable.

Specific design of controls and layout

Analogous to a designer/drafter creating the drawings for door handle, steering wheel, etc

<div style="page-break-after: always"></div>

## Why should you care about UX?

Ease of use is the best way to retain users

User acceptance is the #1 reason for DW implementations to encounter serious roll-out difficult, if not outright fail.

Any planning work - no matter how crude - will make future execution efforts smoother. (underlying message - it's actually easier and quicker to do it this way.  It may not feel as productive up front, but the dividends pay off later...)

DriveWorks automation is a great way to decrease design errors, but it relies on the user to input the correct information, UX focuses on making that as easy as possible

Having modern, accessible, and easy to use configurator can be a great selling point, and helps build trust with your customers / users

A good UX can mean that you don't have to train on how to use it: it should be intuitive

A good UX can mean that you don't have to provide as much support

<div style="page-break-after: always"></div>

## Accessibility

Accessibility is the term for making sure that everyone can use your product, regardless of their abilities.

UX design is all about making your product easy to use, and so that includes making sure you are not excluding your users.

Everyone benefits from accessibility.

- Elevators: not just wheelchairs, but also strollers, luggage, etc
- Curb cuts: not just wheelchairs, but also bikes, skateboards, etc
- Closed captioning: not just deaf, but also noisy environments, non-native speakers, etc
- Large print: not just visually impaired, but easier to read for everyone
- Color contrast: not just color blind, but also in bright sunlight, monitor differences, printing, etc

<div style="page-break-after: always"></div>

## The Design Process Roadmap

1. [Identify](#1-identify)
2. [Research](#2-research)
3. [Plan](#3-plan)
4. [Conceptual Design](#4-conceptual-design)
5. [Wireframe](#5-wireframe)
6. [Prototype](#6-prototype)
7. [Implement](#7-implement)
8. [Feedback loop](#8-feedback-loop)

## 1. Identify

### Goals

Define what you want to accomplish with your configurator (if you haven't already)

Define what you want to accomplish with your (re)design

- Reduce user input errors
- Retain users
- Reduce training time
- Reduce manual work
- Increase sales

### Priorities

- Of your goals, which are the most important?
- Are there known issues that need to be addressed first?
- Is this more important then what you are currently working on?

### Audience

Define who your audience is, and what you plan on improving for them

- Sales, Administrators, Public Customers, Internal Engineers, Anonymous users, etc  

### Resources

- Who is going to be working on this project? Do they have the skills and time to do so?
- Other departments
  - Do you already have branding guidelines?
    - Colors, fonts, logos, icons, images, email templates, etc
  - Do you have a marketing department that can help with the design?
  - Do you have a web development department that can help with the implementation?

<div style="page-break-after: always"></div>

## 2. Research

- Who are your prospective users?
  - What is their motivation, goals in their role?
  - What is their existing solution?
    - Excel, manual process, existing configurator, competitor's configurator, etc
    - What do they like about it?
    - What do they dislike about it?
    - What errors have they encountered?
    - What do they wish it could do?
    - What are their pain points?
  - Do they have any accessibility needs?
  - What devices / browsers are they using?
  - Region, language, timezone, currency, etc
- What are your competitors doing? / What are the alternatives?
  - What are they doing well?
  - What are they doing poorly?
  - What are they (not) doing that you could do?
  - Take screenshots, make notes
- What applications/websites are familiar to your users?
  - Can you use similar patterns?

<div style="page-break-after: always"></div>

## 3. Plan

- Are you going to make incremental changes, or a complete redesign?
  - Should you have a separate project for the UI and keep the existing project for the logic?
- Identify who will be working on what
  - Do you need assistance from other departments such as marketing or IT?
- Timeline, budget, resource allocation

<div style="page-break-after: always"></div>

## 4. Conceptual Design

This is also known as "The Big Picture."

### 4.1. Start by writing down notes and thoughts

What are some common complaints you have heard from users?

What are some things you have seen in other sites that you are inspired by?

### 4.2. Define the problem(s) you wish to solve and a way to measure success

- Reduce user input errors by implementing input validation
- Retain users by making the configurator more modern and easy to use
- Reduce training time by making the configurator more intuitive
- Reduce number of rejected quotes by implementing logic to prevent invalid configurations
- Decrease time between quote request and quote delivery by making the configurator require less manual input

### 4.3. Create User Personas: Typically 1 per user type (Team)

- What is their role / relationship to the company?
- Which groups, projects, or forms should they have access to?
- Why should they use your configurator?
  - "It is an improvement over their existing solution because..."
  - "This will save them time/effort/money because..."
- Review this with stakeholders to ensure it matches their understanding

### 4.4. Define user workflows

- what are the different things that a user can accomplish?
- These should match the goals you defined earlier
- Request a quote, check status of a quote, create a new project, update password, etc
- Are there different paths that a user could take to accomplish the same thing?
- Which Teams use each workflow?

### 4.5. Define Design Principles and Guidelines

Use everything you have gathered so far and work with other stakeholders on defining high-level design principles and guidelines that will guide the design process now and in the future.

- "We want to make the configurator as easy to use as possible"
- "We want to match the design of our website"
- "We want to ensure that the configurator is accessible to users in North America"

### 4.6. Draw a flow diagram

Using technology you are comfortable with, make a high level structure of the configurator. How do different pages/forms interact with each other? What sources do they send or receive information from?
Make sure to include, not just pages, but also states the user may be in, such as "waiting for approval" or "received email confirmation." Sometimes these can map to specification states.

- Pen and paper, LucidChart, PowerPoint, whatever you are comfortable with
- Map the flow of the user through the configurator
  - Remember, map their experience, not just the pages
- Include holistic view, including spec transitions, approvals, etc.
- What sources do they send or receive information from? 3D Preview, SQL, API, etc
- Include and flag nodes that still require manual effort
- Collect feedback from stakeholders
- ITERATE ITERATE ITERATE

<div style="page-break-after: always"></div>

### Flow Diagram Software

If you have something already, use that. If you know something already, use that. Talk with your company with what others are using or what you have licenses for. Consider these:

- Figma has an option called FigJam
  - Easier to learn Figma + FigJam then Figma + other software
  - Integrates well with Figma
  - Consolidated licensing
- LucidChart is industry leader
- integrates with Professional services such as SalesForce, Microsoft Office
  - Use LucidSpark to quickly capture ideas, then LucidChart to make flow diagram
  - Most features, most templates
  - AI assist
- PowerPoint
  - Likely already have license(s)
  - Likely already know the software

<div style="page-break-after: always"></div>

## 5. Wireframe

A wireframe is a low fidelity mockup of the various pages and controls. It is meant to be quick and easy to iterate on. It is not meant to be a final product, rather a way to quickly and easily visualize the layout and functionality of the configurator.

Don't worry about colors, fonts, etc, rather focus on layout and functionality.
  
Use technology you are comfortable with. Pen and paper, whiteboard, cut out pieces of paper, Figma, PowerPoint, etc.

1. Start drawing the overall layout (header, sidebar, main content, etc.)
2. Which controls should be grouped together? How are they laid out?
   - How do the controls/groups interact with each other?
   - What information need to be displayed to the user?
   - 3DPreview, images, data records
   - Are some inputs invalid? How do you display that to the user?
3. Create a list of pages / forms and what controls are needed on each
4. Try different layouts and groupings, and get feedback from stakeholders

<div style="page-break-after: always"></div>

## 6. Prototype

A prototype is a high fidelity mockup of the various pages and controls. It is meant to be a representation of the final product, outside of DriveWorks. It is meant to be a way to quickly and easily visualize the layout and functionality of the configurator.

The flow diagram, wireframe, and even the user persona were meant to quickly ideate and iterate rather then needing to be polished. The prototype is meant to be polished and signed off by stakeholders.

This is similar to an engineering drawing: the full specification of the product, but not the product itself.

As such, using a purpose built tool is recommended. Figma and Adobe XD are industry leaders, but if needed, Indesign, Publisher, Photoshop, or even PowerPoint can be used.

1. Using your brand guidelines, start by setting the fonts, colors, logos, etc.
2. Start with the overall layout (header, sidebar, main content, etc.)
3. Design the controls and groupings - the component guide
   - DriveWorks gives several types of inputs, but you may have multiple label types for example (heading, validation, information, etc)
   - Make a master for each component, and use that master throughout the design
4. Make a prototype for each of your distinct pages / forms
   - You don't have to mockup each page, but you should mockup each distinct layout
   - Make additional prototypes for different screen sizes (if applicable)
     - mobile, laptop, half screen, etc
5. Get feedback from stakeholders
6. Iterate, iterate, iterate
7. Finally, save as a pdf and get it signed off by stakeholders

<div style="page-break-after: always"></div>

## Figma

- Industry leading software for UI design
- Quickly iterate through ideas
- Focus on design while isolating from minutia of implementation
- Excels at collaboration
      - Can have multiple people work on it at once, unlike DriveWorks Project Form Designer
      - Can capture comments right on design
      - Use "Present" mode to create links to share with stakeholders earlier in process
      - Use "Dev" mode to easily identify spacing, position, styles
- Don't need to be Technical to design or modify
      - Can be handed off to graphic/web designer without DriveWorks license
      - Professional alignment, spacing, grouping without variables
      - GUI to quickly and easily design and have it write CSS for you
- Can create assets and reuse them (or modify them later)
      - Icons
      - Form Controls
      - Metadata tags
- Frames in Figma are meant to group items: encouraged to use same thought process with Frame Controls
- You can create a navigable website to test with users
- Component Guide can be made from "components" like master files in DriveWorks

<div style="page-break-after: always"></div>

## 7. Implement

Use your component guide to make a form that has an example of each of the items (or groups) you need.

Use variables wherever possible to keep things consistent. If you set the standard width of a control via a variable you can edit it from anywhere as opposed to finding the original control and changing it.

You may wish to set your brand colors and fonts in either CSS variables or DriveWorks variables. This makes it easier for others to contribute and not have to train them on your brand guidelines.

If you are using DriveWorks 21+, you can use CSS to style your components.
This allows for way more customization than DriveWorks alone, and can be used to match your brand guidelines. It can also allow advanced styling such as animations, shadows, on hover effects, etc.

Don't set the positions of the controls in CSS.

As a general rule, all of the functionality of the forms should work with CSS disabled. However, with CSS, you can make it a nicer (more modern) user experience.

If this is available via the web, make sure to test it on different devices and browsers. (Mostly applicable if you are using CSS)

Test it against a small group of users, and get feedback before rolling it out to everyone.

<div style="page-break-after: always"></div>

## 8. Feedback loop

Your job is never done: you can always take feedback and improve.

More objectively, the goal of this exercise was to make things better for your users, and how do you know if you have done that if you don't ask them?

If you had an existing configurator, maybe you decided to take baby steps and only change a few things. You can collect feedback and use it to decide what to change next and how, making sure you stay true to your objectives, priorities, and principles.

<div style="page-break-after: always"></div>

## Closing Remarks

### Key takeaways:


- Planning: Ensure that you have a clear understanding of your goals, priorities, audience, and resources before you begin.

- Conceptual Design: Freeform brainstorming, sketching, and ideation. This is the time to think big and explore possibilities.

- Flow Diagram: Map the flow of the user through the configurator, include states and information sources, iterate based on stakeholder feedback.

- Wireframe: Focus on layout and functionality, group controls, display necessary information, gather feedback from stakeholders.

- Prototype: Create a high-fidelity mockup of the configurator, design controls and groupings, iterate based on feedback, obtain stakeholder approval.

- Implementation: Use the component guide to build the form, utilize variables for consistency, consider CSS for advanced styling, test on different devices and browsers.

Remember, the UX development process is iterative. Keep refining and improving for a better user experience.


