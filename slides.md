---
theme: slidev-theme-tpm

title: UX Development Process
author: Joseph C. Caswell
keywords: presentation, DriveWorks, TPM, UX, UI, Design
presenter: true
exportFilename: UX Development Process

# enable slide recording, can be boolean, 'dev' or 'build'
record: true

# favicon, can be a local file path or URL
favicon: "./favicon.png"

# default frontmatter applies to all slides
defaults:
  layout: default
  # ...

# drawing options
# Learn more: https://sli.dev/guide/drawing.html
drawings:
  enabled: true
  persist: false
  presenterOnly: false
  syncAll: true

# HTML tag attributes
htmlAttrs:
  dir: ltr
  lang: en

# First Slide
layout: cover
hideInToc: true
---

# User Experience Design

Joseph C. Caswell, Technical Solutions Consultant, TPM, Inc.

## The road to a user-focused DriveWorks configurator

<!--
Hello! And welcome everyone to 
User Experience Design for DriveWorks!

This presentation is for anyone who wishes to learn more about how to make their DriveWorks implementation more user friendly and more user focused. Ultimately leading to a more successful implementation.

My name is Joseph Caswell, and I am a Technical Solutions Consultant at TPM, a DriveWorks reseller based in the southeast US. 
It is my job to consult with a variety of customers to guide them to a successful DriveWorks implementation, and in many cases I am directly involved in bringing their DriveWorks projects to life.
-->

---
title: Overview
hideInToc: true
---

# Overview

High level process for anyone with a new or existing DriveWorks implementation.
<br><br>

### [What is UX/UI Design and why should you care?](#what-is-ux-design)

### [The importance of Accessibility](#accessibility)

### [The Design Process Roadmap](#the-design-process-roadmap)

### [Tools of the trade](#flow-diagram-software)

<!--
Don't worry if you have no idea what UX is, or what it entails, this presentation will go over just that.
We are going to take a high level overview of the UX design process from cradle to grave.

We'll go over UX design, UI design, and accessibility. 
What they all are and why they are important.

Then we'll walk through the design process step by step and showcase some tools of the trade along the way.

So let's get started!
-->

---
title: UX Design
---

# What is UX Design?

Designing from the perspective of the user


<v-clicks>
  
- User journey to solve a problem, not just the interface

- Create products that provide meaningful and relevant experiences
  
- Integrate branding, design, usability, accessibility, and function

</v-clicks>

<!--
What is User Experience Design?

UX Design the process of designing a product from the perspective of the user. 

You may have heard of DFM, or Design for Manufacturing. That is the process of taking a look at your products and seeing how you can modify them to be better for manufacturing. 

This isn't all that different: instead we are going to be looking to see how things can be improved for the user. 

[click] UX specifically, is focused on the entire journey, or experience of the user: not just the interface.

[click] UX Design is the process of creating products that provide meaningful and relevant experiences to users. 

[click] It involves the designing with the intent to integrate aspects of branding, design, usability, and function.
-->

---
layout: quote
name: Google UX Quote
---

## "UX designers help make technology easier to understand and more enjoyable to use" 

Google UX Team

<!--
UX designers help make technology easier to understand and more enjoyable to use.
-->

---
title: UX Design
---

# What is UX Design?

Holistic design of the experience from cradle to grave

Analogous to an engineer designing a car

<v-clicks>

- What size, what region, what price, what features, etc

- How does it make the driver/passenger feel

</v-clicks>

<!--
Let me bring this back to engineering:

Before you can design the door handles of a car, or the dashboard, or even the muffler, you need to know what, or rather, who the car is for. 

[click] Who will be driving it? In what regions? What weather conditions? What are their expectations? Price point?

[click] What is the car supposed to make the driver/passenger feel?

A Ferrari supercar is going to be a very different experience from a chrysler minivan, and every aspect of the design should reflect that. Failing to consider this leads to a bad user experience which means unhappy customers.
-->

---
title: UI Design
---

# What is UI Design?

Specific design of controls and layout

<v-click>

UI Design is the process of making interfaces with a focus on looks or style.
</v-click><v-click>

In DriveWorks this is the look, layout, and functionality of the form controls
</v-click><v-click>

Analogous to an engineer designing a door handle, steering wheel, etc
</v-click>

<v-click at="-1">

  <img src="/form-controls.png" alt="Form Controls" class="mx-auto" />

</v-click>

<!--
What about UI? What's the difference?

[click]User Interface design is the process of designing the individual interfaces that make up the product. 

[click]In our case, this will be the forms and controls that make up the DriveWorks project. 
How big is your text input? What happens when you type in an invalid input?
How are the different controls laid out on the screen? How about for a mobile device?

UX and UI are terms that are often used together, but they have disctinct meanings. 
A UI designer is focused on the specific design of the controls and layout of the product where UX focuses on higher level concepts then that.

[click]Bringing it back to designing cars, this is the point where we are designing the door handles, the steering wheel, the dashboard: all the parts that the user interacts with.

Remember, with UX we were focused on the experience as a whole.
-->

---
title: UX - Users
---

# Why should you care about UX?

<v-click>

Ease of use is the best way to retain users

## User Adoption

User acceptance is the #1 reason for DriveWorks implementations to encounter serious roll-out difficulties, if not outright fail.

</v-click>

<!--
So why should we, as DriveWorks administrators care about user experience?

[click] #1: User Adoption

You need people to actually use your configurator for it to be successful and ease of use is the best way to attract and retain users. Not hitting that mark is the number one reason for implementations to be unsuccessful.

Just about all of us, at some point in our life has built an automation tool we are really proud of, but no one ends up using it. 
It's frustrating.

Later we'll talk more about uncovering the needs of you users so you can focus your efforts on what they need.
-->

---
title: UX - Planning
---

# Why should you care about UX?

Failing to plan is planning to fail

## Planning can save time and effort

Any planning work - no matter how crude - will make future execution efforts smoother.

<!--
This ties directly into the next reason: planning. 

Planning can save time, money, and effort, and will make future efforts smoother.

Working in DriveWorks, we can sink a lot of time into trying to get something to work just right. 
How often is that time ultimately wasted because we didn't have a clear understanding of what we were trying to accomplish?

Maybe you fought with the oddities of making an HTML email quote, but your customer is frustrated because it can never print out right? 
Should you have made a PDF instead and attached it to a simple email?

Maybe you stuck a ton of options into a single form, but your sales team or your customers could have told you that most of them are obsolete?

It may not feel as productive up front, but ultimately it's easier and quickier to integrate the user experience into your planning. Believe me, the dividends will pay off later
-->

---
title: UX - Training
---

# Why should you care about UX?

Intuition is the best training

<v-click>

## Less Training and Support

A good UX can mean that you don't have to train on how to use it: it should be intuitive

</v-click>

<v-click>

## Less Rework or rejections

Inform and guide users to make the right choices

</v-click>

<!--
Good designs leverage user intuition and past experiences. 
You can build on this by incorporating visuals such as images or DriveWorks 3D Preview.

[click] Ultimately, good UX leads to having take less of your valuable time training new users, and less effort fixing things because users input invalid parameters.

[click] You can save yourself from having to reject specifications by not allowing invalid combinations. Catch errors before they happen, and make it easy for the user to fix them
-->

---
title: UX - Sales
---

# Why should you care about UX?

Attractive interfaces entice, and good experiences retain

## Drive More Sales

Modern interfaces are attractive, and can be a great selling point

Users are more likely to continue to use interfaces that are easy, and they can trust to get the job done

<v-click>
Rebuild trust and re-engage frustrated customers with a new, intuitive design
</v-click>

<!--
In some circumstances, a good UX can drive more sales as well.

DriveWorks Live allows us to have configurators open to the public, not just for internal use.

Doing so means our user base is larger, more diverse, and we have to compete with all the other sites out there. 

You can drive initial interest by having an attractive UI, but, just like anything else, they won't come back unless they had a good experience.

[click] If you have had a configurator for a while it's possible people have built up distrust or an ick factor.
Introducing a new, better, more intuitive design is an opportunity for a marketing blast, and a chance to re-engage customers that may have been frustrated with the old design.

Hey everybody try out Configurator 2.0! It's so much easier to use!

-->

---
title: UX - Review
---

# Why should you care about UX?

Recap

### User Adoption

### Planning can save time and effort

### Less Training

### Less Support

### Drive More Sales 

<!-- 
To recap,
you should care about the user experience because 

a good UX attracts and retains users, 

saves time, money, and effort and can lead to more sales.

All affecting your bottom line
 -->

---
title: Accessibility
layout: image-right
image: /accessibility-medium.webp
backgroundSize: contain
---

# Accessibility

Ensure everyone can use your product, regardless of their abilities.

UX design is all about making your product easy to use, and so that includes making sure you are not excluding your users.

<!--
Before we jump into how to get started desiging, I would like to take a moment to talk about something that is very near and dear to my heart - Accessibility

Accessibility is the term for making sure that everyone can use your product, regardless of their abilities.

We are not all perfect humans: Everyone has a different set of eyeballs, brain, hands, experience, etc

If your implementation is public facing, then folks will be accessing it from different browsers, devices, operating systems, and screen sizes.

During the research phase, which we'll cover later, you will uncover which of these to focus on, so you can accommodate those differences in your UI.
-->

---
title: Accessibility 2
layout: image-right
image: /curb-cut.jpg
backgroundSize: fit
---

# Accessibility

Everyone benefits from accessibility.

<br>

<v-click><mdi-elevator /> Elevators <br><br> </v-click>
<v-click><guidance-ramp-down /> Curb cuts <br><br> </v-click>
<v-click><icon-park-outline-font-size-two /> Large print <br><br>
<icon-park-outline-contrast-view-circle /> Color contrast </v-click>

<!--
Everyone benefits from accessibility. 

We are surrounded by technology or design descions that, while they may be required for people with certain limitations, they are helpful for everyone.

[click] Take elevators for instance: Here in the US they are required by law by the Americans with Disability Act because that is the only way some folks can get from floor to floor.

[click] Curb cuting is the term for sloping a sidewalk down to a crossing as seen here. This design decision shapes and guides you on where to cross the street. But it's also there to assist those confined to wheelchairs. 
Both elevators and curb cuts assist all of us with our luggage, strollers, bikes, or pulling a cart. 

[click] Having large print, and ensuring there is high contrast between text and it's background vastly improves readability for everyone.
-->

---
title: Accessibility Quote
layout: quote
---

### “When UX doesn’t consider ALL users, shouldn’t it be known as “SOME User Experience” or… SUX?”

— Billy Gregory, Senior Accessibility Engineer, The Paciello Group

<!-- “When UX doesn’t consider ALL users, shouldn’t it be known as “SOME User Experience” or… SUX?” -->

---
layout: image
image: /Contrast-Example.jpg
alt: Contrast Example
height: 55%
---

# Accessibility

Readability and simplicity are key


- Use large, easy to read fonts
- Use high contrast colors


<!--
Here are some key things you can do to make your DriveWorks implementation more accessible:

Use large, easy to read fonts and make sure there is enough contrast between the text and the background.
Make sure there is enough space between elements so that they don't run together.

-->

---

# Accessibility

Don't rely on color alone to denote meaning

<img src="/interface-no-icons.png" alt="Interface without icons" class="h-80 mt-2">


<!--
Don't rely on color alone to denote meaning. 

A majority of us in mechanical and manufacturing engineering are male, and we are 17 times more likely to be color blind then women.

Let's take a look at this interface. It's a simple form with a few inputs with some user validation.
If we rely on just the color of the border to determin valid input, not everyone may be able to tell if the input is valid or not.

-->

---

# Accessibility

Don't rely on color alone to denote meaning

<img src="/interface-with-icons.png" alt="Interface with icons" class="h-80 mt-2">


<!--
Here we have modified it to include not only an icon, but also a text label telling the user what is wrong with the input.
-->

---
layout: image
image: /paint.png
alt: Paint colors with names
height: 70%
---

# Accessibility

Don't rely on color alone to denote meaning

<!--

If you have a color picker for paint, make sure to include the color name, not just the color.

-->

---

# Accessibility

Layout

 - Ensure adequeate spacing between elements

- Group like items together

- Spread controls out over multiple pages or tabs

- Every element has a purpose

<img src="/grouping.png" alt="Grouping" class="absolute inset-y-0 right-20 max-h-full">

<!--

We can consider making things accessible to those with dsylexia or ADHD by making sure there is ample space between elements, and grouping like items together. 

Let's take a look at this interface from Microsoft Office:

We have 3 sections of controls, each related to each other: labeled, grouped, and spaced out.

Then, there is a live preview of the changes you have made. 

There's too many controls to fit on a single page, so they have seperated them into tabs. 

With this selection, one of the checkboxes is not available and they have made it obvious by graying it out.

This is an accessible, easy to follow design, and not difficult to implement.

-->

---
layout: section
---

# The Design Process

<!-- 
We've learned about why UX and UI design are important, and what they are.

and we've discussed the importance of accessibility.

Now let's walk through the design process step by step.
 -->


---
title: Roadmap
---

# Design Process Roadmap

1. Identify
2. Research
3. Plan
4. Conceptual Design
5. Wireframe
6. Prototype
7. Implement

<br>

<pajamas-repeat /> Feedback loop

<img src="/StreamlineArrowRoadmap.svg" alt="Roadmap" class="h-80 absolute bottom-20 right-10">

<!-- 
The design process occurs in a series of phases, each building on the last.

We'll start by identifying, researching, and planning our project.

Then we'll move on to conceptual design, wireframing, and prototyping and we'll touch on some software that can help with that.

And once we have a design we are happy with, we'll move on to implementing it in DriveWorks.

Along the way we'll make sure to get feedback from stakeholders and users to make sure we are on the right track, and even once deployed, there's always room for improvement by collecting feedback.

-->

---
layout: section
---

# 1. Identify

Goals, Priorities, Audience, Resources

<!-- 
The very first step of UX design is the same as the first step in any project: identifying and prioritizing your goals, specifying your audience, and identifying the resources you have available. 

This will likely involve project managers or department heads, and is an exercise that you may have already done when you first started your DriveWorks implementation.
 -->

---

# 1.1 Identify Goals

Aimless Effort without goals may be waisted

### Answer the why: What are you trying to accomplish?
<br>
<v-click>

- Reduce user input errors
- Reduce training time
- Reduce manual work
- Increase sales
- Retain/increase users
</v-click>
<br>
<v-click>

### Quantify and qualify your goals
</v-click>

<!-- 
First up is the goals.

Define, if you haven't already, what it is that you wish to accomplish with your implementation or redesign.
Ask yourself, and your other stakeholders what are you trying to achieve? What are you trying to improve?

[click] We just covered many reasons to put effort into making a good UX and many of them align with the reasons you got into DriveWorks in the first place. Probably to make your life easier, less reptitive: and ultimately to make your company more money.

[click] But which of these specifically applies to your company and your implementation? Can you quantify or qualify the improvements you wish to make?

During this process you may identify several goals. So...
 -->

---

# Priorities

Priorities dictate focus

- Of your goals, which are the most important?
- Are there known issues that need to be addressed first?
- Is this more important then what you are currently working on?

<!-- 
... now it is time prioritize. We can't do everything at once no matter how much we wish we could.

Identify which goals may be the easiest to implement, or will have the biggest impact.

Does it make sense to roll changes out incrementally, or should you do a complete redesign?

Are these goals more important then what you or your team are currently working on?
-->

---
layout: image-right
image: /Audience.svg
backgroundSize: contain
---

# Audience

Define who your audience is, and what you plan on improving for them

- General Public
- Sales Team
- Internal Designers
- Administrators
- Anonymous users

<!-- 
Next, identify who would be using your implementation. 

Will this be open to the general public or just your sales team?

Will this be used by internal designers or administrators?

Will you have anonymous users or will everyone have to login?

Does it make sense to have different implementations for different users?

Will you prioritize one group over another?

You will likely use the groups you identify here as the baiss for Teams in DriveWorks Security.
 -->

---

# Resources

No resources, no progress

- Who is going to be working on this project?
  - Do they have the skills and time to do so?
- Other departments
  - Marketing
  - IT
  - Manufacturing
  - Sales

<!-- 
You can't begin to plan unless you know what resources you have available.

Who is going to be working on this project? Do they have the skills and time to do so?

Do you need to get other departments in your company involved?

Perhaps your marketing team has a graphic designer that can help with the design?

Maybe your IT department can help with setting up a server or web hosting?

Do you already know everything about the product, or do you need to get manufacturing or sales involved?
 -->

---
layout: section
---

# 2. Research

Users, Competitors, Alternatives

<!-- 
We've finished identifying our goals, audience, and resources. 

Our next step in the design journey is research.

We need to find out more about our users, our competitors, and what alternatives are out there.
 -->


--- 
layout: image
image: /user-persona.svg
---

# Users

User Personas document crucial info

<!-- 
In a previous phase we, with our manegerial hat on, identified the groups we wish to target.
Now it is time to put on our detective hat and find out what we can about them.

What are their motivations and goals in their role?
What is their existing solution or workflow and what challenges do they face with it?


Based on this we can focus our efforts on what will make the biggest impact for them, which will go a long way towards their willingness to adopt, or keep up with the new system.

It may also be helpful to identify if they have any accessibility needs, what devices and browsers they are using, and what region, language, timezone, and currency they use. 

You will, of course, wish to take note of the information you have gathered about your users.

In UX design, sometimes it's helpful to create cards that represent your users, or user personas.
Nice term to keep in your pocket if you end up working with a graphic designer, however, any way you can capture this information is fine.
 -->

---

# Users

Why should they use your configurator?

- "It is an improvement over their existing solution because..."
- "This will save them time/effort/money because..."

<!-- 
Try and answer the question: Why should they use your configurator?

Your answer may be something like "It is an improvement over their existing solution because..." or "This will save them time/effort/money because..."

This should tie directly in with the goals you identified earlier, but this time from the perspective of the user.
 -->


---

# Competitors / Alternatives

What's the other guy up to?

- Research the competitors and compare their sites

- What are the existing solutions?

<!-- 

Every designer, mechanical UX, or otherwise, takes inspiration from what is already out there.

See if you can find out what your competitors are using, does it seem to work for them?

Take some screenshots, if you can, try them out. read up on reviews, or simply have a chat with someone who uses it.

While researching your users, you figured out what they were currently using. If they are using your existing implementation, what are they saying about it?

We don't want to throw them off their routine: rather we want to make it better: less effort, more accessible, less errors or frustration.

-->

---
layout: section
---

# 3. Plan

Timeline, budget, resource allocation

<!-- 

 -->

---

# Planning

Failing to plan is planning to fail

<v-clicks>

- Incremental changes, or a complete redesign?
  - Separate project for the UI?
- Who will be working on what
  - Other departments
    - Marketing, graphic design, IT
    - Outsourcing
- Timeline, budget, resource allocation

</v-clicks>

<!-- 
Are you going to make incremental changes, or a complete redesign?
This likely depends on the goals you identified earlier, and if there are items that need to be addressed immediately.

[click] You may have multiple people collaborating, 
Since only one person can have a single project open in Administrator at a time, you may opt to seperate the UI from the logic using specicification host controls.

Not only should you plan who on your team will be responsible for which parts, but you may bring in other departments such as marketing, graphic design, or IT, or even outsource some of the work.
  
[click] And of course, no plan is complete with a timeline and budget.
-->

---
layout: section
---

# 4. Conceptual Design

The Big Picture

<!-- 
We have identified our goals, audience, and resources, and have done our research.

Now it is time put it all together and start sketching up some ideas.

-->

---
layout: image
image: /sketched-ui-wireframe.webp
---

# Pen and Paper

<!--
This is the time for pencil and paper, or a whiteboard, or even using scissor to cut up some screenshots you took.

We are all familiar with the "back of the napkin" phase of invention or design, and this is pretty much that.

Brainstorm is all about letting ideas flow quickly, not worrying about the details and not letting our anxiety about the final product get in the way.

Feel free to jump in and ideate or sketch on any ideas you have. Whether it be the process as a whole, the form layout, or even the controls themselves. 

Spend a few minutes on each idea, and then move on to the next.

Once you are done, take a step back and see if any of the ideas stand out to you, or if you can combine them into something better.
-->


---
layout: image-right
image: /flowchart.png
backgroundSize: contain
---

# Flow Diagrams

Hollistic map of the user experience

<v-click>

Pen and paper, LucidChart, PowerPoint, whatever you are comfortable with

</v-click><v-click>

- Map the flow of the user through the implementation

</v-click><v-click>

- States and transitions similar to specification flow 

</v-click><v-click>

- Collect feedback from stakeholders
- ITERATE ITERATE ITERATE

</v-click>

<!-- 
Now we focus on the flow of the user through the implementation.

[click] Using technology you are comfortable with, make a high level structure of the configurator. 
How do different pages/forms interact with each other? What sources do they send or receive information from?

[click] Remember, map their experience, not just the pages. This means documenting what caused them to decide to use it, what software might they be accessing the link from, what do they expect to get in return, and when.

[click] User flow and user states are not that different from specification flow and states. In fact, many of these states may be the same: submitted for approval, awaiting CAD generation, etc.

[click] Make sure to include your other stakeholders in this process, and iterate on the design as needed.
-->

---

### Flow Diagram Software

<!-- If you have something already, use that. If you know something already, use that. Talk with your company with what others are using or what you have licenses for. Consider these:

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
  - Likely already know the software -->

---

# 5. Wireframe

<!-- A wireframe is a low fidelity mockup of the various pages and controls. It is meant to be quick and easy to iterate on. It is not meant to be a final product, rather a way to quickly and easily visualize the layout and functionality of the configurator.

Don't worry about colors, fonts, etc, rather focus on layout and functionality.

Use technology you are comfortable with. Pen and paper, whiteboard, cut out pieces of paper, Figma, PowerPoint, etc.

1. Start drawing the overall layout (header, sidebar, main content, etc.)
2. Which controls should be grouped together? How are they laid out?
   - How do the controls/groups interact with each other?
   - What information need to be displayed to the user?
   - 3DPreview, images, data records
   - Are some inputs invalid? How do you display that to the user?
3. Create a list of pages / forms and what controls are needed on each
4. Try different layouts and groupings, and get feedback from stakeholders -->

---

# 6. Prototype



<!-- A prototype is a high fidelity mockup of the various pages and controls. It is meant to be a representation of the final product, outside of DriveWorks. It is meant to be a way to quickly and easily visualize the layout and functionality of the configurator.

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
7. Finally, save as a pdf and get it signed off by stakeholders -->

---

# Figma

<!-- - Industry leading software for UI design
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
- Component Guide can be made from "components" like master files in DriveWorks -->

---

# 7. Implement

<!-- Use your component guide to make a form that has an example of each of the items (or groups) you need.

Use variables wherever possible to keep things consistent. If you set the standard width of a control via a variable you can edit it from anywhere as opposed to finding the original control and changing it.

You may wish to set your brand colors and fonts in either CSS variables or DriveWorks variables. This makes it easier for others to contribute and not have to train them on your brand guidelines.

If you are using DriveWorks 21+, you can use CSS to style your components.
This allows for way more customization than DriveWorks alone, and can be used to match your brand guidelines. It can also allow advanced styling such as animations, shadows, on hover effects, etc.

Don't set the positions of the controls in CSS.

As a general rule, all of the functionality of the forms should work with CSS disabled. However, with CSS, you can make it a nicer (more modern) user experience.

If this is available via the web, make sure to test it on different devices and browsers. (Mostly applicable if you are using CSS)

Test it against a small group of users, and get feedback before rolling it out to everyone. -->

---

# 8. Feedback loop

<!-- Your job is never done: you can always take feedback and improve.

More objectively, the goal of this exercise was to make things better for your users, and how do you know if you have done that if you don't ask them?

If you had an existing configurator, maybe you decided to take baby steps and only change a few things. You can collect feedback and use it to decide what to change next and how, making sure you stay true to your objectives, priorities, and principles. -->

---

# Design Process Recap


1. [Identify](#1-identify) - Goals, Priorities, Audience, Resources

<v-clicks>

2. [Research](#2-research) - Users, Competitors, Alternatives
3. [Plan](#3-plan) - Project, Timeline, Resources
4. [Conceptual Design](#4-conceptual-design) - Brainstorm, Sketch, Ideate
5. [Wireframe](#5-wireframe) - Quick low fidelity mockups
6. [Prototype](#6-prototype) - High fidelity mockups
7. [Implement](#7-implement) - Build in DriveWorks
8. [Feedback loop](#8-feedback-loop) - Continuously improve
</v-clicks>

<img src="/StreamlineArrowRoadmap.svg" alt="Roadmap" class="h-80 absolute bottom-20 right-10" />

<!-- 

And that's our journey from cradle to grave.

[click] we started by identifing our goals, audience, and priorities

[click] we researched our users and competitors

[click] we created a plan, and a timeline to follow

[click] we brainstormed, and doodled up some ideas

[click] then we wireframed the different pages and controls

[click] Using software such as Figma, we made a prototype that would be the blueprint for our implementation

[click] lastly, we implemented our design in DriveWorks. making use of variables and new features such as CSS

[click] Now that it's out in the wild, we can collect feedback and never stop improving
 -->

---
layout: end
---


# Thank you!

Joseph C. Caswell

<img src="/tpm_logo_white_transparent.png" alt="TPM Logo" class="absolute m-6 left-0 bottom-0 h-20" />

<!-- 
Thank you all for attending this virtual session at DriveWork! 

I hope you learned a lot about accessibility, UX and UI design, why they are important, and how to get started.

Don't forget to check out the other sessions in the DriveWorks World event app!
-->