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

High level design process for anyone with a new or existing DriveWorks implementation.
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

# Accessibility

Readability and simplicity are key


- Use large, easy to read fonts
- Use high contrast colors

<img src="/Contrast-Example.jpg" alt="Contrast Example" class="h-75 ml-30 mt-2">


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

For invalid input don't just turn the outline from green to red...
-->

---

# Accessibility

Don't rely on color alone to denote meaning

<img src="/interface-with-icons.png" alt="Interface with icons" class="h-80 mt-2">


<!--
...  consider adding a message, or use an icon.
-->

---

# Accessibility

Don't rely on color alone to denote meaning

<img src="/paint.png" alt="Paint colors with names" class="h-80">


<!--

If you have a color picker for paint, make sure to include the color name, not just the color.

-->

---

# Accessibility

Make sure there is ample space between elements

- Group like items together

- Spread controls out over multiple pages or tabs

- Every element has a purpose

<img src="/grouping.png" alt="Grouping" class="absolute inset-y-0 right-20 max-h-full">

<!--
 

Make sure there is ample space between elements, and group like items together. 
Not only is this very helpful for folks with dyslexia or ADHD, but consistent spacing looks more professional, is easier to read, and is easier to understand and navigate.
Try not to put too many controls on the page, but rather spread them out over multiple pages or tabs.

[click] Along the same lines, don't have items on the page just because. Everything on the page should have a purpose: function, information, or grouping.
If a control is is not accepting input either hide it or make it clearly disabled.

All of these accessibility tips benefit everyone. 
-->


---
title: Roadmap
---

# The Design Process Roadmap

<style scoped>
  li {
    @apply my-2;
  }
</style>

<v-clicks>

1. [Identify](#1-identify) - Goals, Priorities, Audience, Resources
2. [Research](#2-research) - Users, Competitors, Alternatives
3. [Plan](#3-plan) - Project, Timeline, Resources
4. [Conceptual Design](#4-conceptual-design) - Brainstorm, Sketch, Ideate
5. [Wireframe](#5-wireframe) - Quick low fidelity mockups
6. [Prototype](#6-prototype) - High fidelity mockups
7. [Implement](#7-implement) - Build in DriveWorks
8. [Feedback loop](#8-feedback-loop) - Continuously improve
</v-clicks>

<img src="/StreamlineArrowRoadmap.svg" alt="Roadmap" class="h-80 absolute bottom-20 right-10">

<!-- 
Now that we've learned about what UX and UI design are, and why they are important, let's take a look at the design process roadmap.
We'll go through each of these steps in detail. 

[click] One: Identify your goals, audience, and priorities

[click] Two: Research your users, competitors, and alternatives

[click] Three: Plan your project, timeline, and resources

[click] Four: Conceptualize: brainstorm, sketch, and ideate

[click] Five: Wireframe: create quick low fidelity mockups of your pages

[click] Then, build a prototype to get feedback from stakeholders

[click] Now you're ready to Implement your design in DriveWorks

[click] Lastly, don't forget to continuously get feedback to improve your design
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
The very first step of UX design is the same as the first step in any project: identify your goals.
Define what it is that you wish to accomplish with your implementation or redesign.
Ask yourself, and your other stakeholders what are you trying to achieve? What are you trying to improve?

[click] We just covered many reasons to put effort into making a good UX and many of them align with the reasons you got into DriveWorks in the first place. Probably to make your life easier, less reptitive: and ultimately to make your company more money.

[click] But which of these specifically applies to your company and your implementation? Can you quantify or qualify the improvements you wish to make?
 -->

---

# 1.2 Identify Priorities

Priorities dictate focus

- Of your goals, which are the most important?
- Are there known issues that need to be addressed first?
- Is this more important then what you are currently working on?

<!-- 
During this process you may identify several goals. 
Now it is time prioritize. We can't do everything at once no matter how much we wish we could.

Identify which goals may be the easiest to implement, or will have the biggest impact.

Does it make sense to roll changes out incrementally, or should you do a complete redesign?

Are these goals more important then what you or your team are currently working on?
-->

---

# 1.3 Identify Audience

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
 -->

---

# 1.4 Identify Resources

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

# 2. Research

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

<!-- It's time to move on to the research phase. 

Now that you have identified who your users are, it's time to learn more about them.

And the best way to do so is go out and ask them a bunch of questions. 

What's their current process? What do they like about it? What do they dislike about it? What errors have they encountered? What do they wish it could do? What are their pain points, or what do they find stops or slows them down?

Do they have any accessibility needs? What devices and browsers are they using? What region, language, timezone, currency, etc?
 -->

---
title: Plan
---

# 3. Plan

- Are you going to make incremental changes, or a complete redesign?
  - Should you have a separate project for the UI and keep the existing project for the logic?
- Identify who will be working on what
  - Do you need assistance from other departments such as marketing or IT?
- Timeline, budget, resource allocation

---
title: Conceptual Design
---

# 4. Conceptual Design

This is also known as "The Big Picture."

1. Start by writing down notes and thoughts

- What are some common complaints you have heard from users?

What are some things you have seen in other sites that you are inspired by?

---
<!-- Slide Styling -->
---

### 4.2. Define the problem(s) you wish to solve and a way to measure success

- Reduce user input errors by implementing input validation
- Retain users by making the configurator more modern and easy to use
- Reduce training time by making the configurator more intuitive
- Reduce number of rejected quotes by implementing logic to prevent invalid configurations
- Decrease time between quote request and quote delivery by making the configurator require less manual input

---
<!-- Slide Styling -->
---

### 4.3. Create User Personas: Typically 1 per user type (Team)

- What is their role / relationship to the company?
- Which groups, projects, or forms should they have access to?
- Why should they use your configurator?
  - "It is an improvement over their existing solution because..."
  - "This will save them time/effort/money because..."
- Review this with stakeholders to ensure it matches their understanding

---
<!-- Slide Styling -->
---

### 4.4. Define user workflows

- what are the different things that a user can accomplish?
- These should match the goals you defined earlier
- Request a quote, check status of a quote, create a new project, update password, etc
- Are there different paths that a user could take to accomplish the same thing?
- Which Teams use each workflow?

---
<!-- Slide Styling -->
---

### 4.5. Define Design Principles and Guidelines

Use everything you have gathered so far and work with other stakeholders on defining high-level design principles and guidelines that will guide the design process now and in the future.

- "We want to make the configurator as easy to use as possible"
- "We want to match the design of our website"
- "We want to ensure that the configurator is accessible to users in North America"

---
<!-- Slide Styling -->
---

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

---
<!-- Slide Styling -->
---

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

---
<!-- Slide Styling -->
---

# 5. Wireframe

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

---
<!-- Slide Styling -->
---

# 6. Prototype

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

---
<!-- Slide Styling -->
---

# Figma

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

---
<!-- Slide Styling -->
---

# 7. Implement

Use your component guide to make a form that has an example of each of the items (or groups) you need.

Use variables wherever possible to keep things consistent. If you set the standard width of a control via a variable you can edit it from anywhere as opposed to finding the original control and changing it.

You may wish to set your brand colors and fonts in either CSS variables or DriveWorks variables. This makes it easier for others to contribute and not have to train them on your brand guidelines.

If you are using DriveWorks 21+, you can use CSS to style your components.
This allows for way more customization than DriveWorks alone, and can be used to match your brand guidelines. It can also allow advanced styling such as animations, shadows, on hover effects, etc.

Don't set the positions of the controls in CSS.

As a general rule, all of the functionality of the forms should work with CSS disabled. However, with CSS, you can make it a nicer (more modern) user experience.

If this is available via the web, make sure to test it on different devices and browsers. (Mostly applicable if you are using CSS)

Test it against a small group of users, and get feedback before rolling it out to everyone.

---
<!-- Slide Styling -->
---

# 8. Feedback loop

Your job is never done: you can always take feedback and improve.

More objectively, the goal of this exercise was to make things better for your users, and how do you know if you have done that if you don't ask them?

If you had an existing configurator, maybe you decided to take baby steps and only change a few things. You can collect feedback and use it to decide what to change next and how, making sure you stay true to your objectives, priorities, and principles.

---
<!-- Slide Styling -->
---

# Closing Remarks

### Key takeaways:

- Planning: Ensure that you have a clear understanding of your goals, priorities, audience, and resources before you begin.

- Conceptual Design: Freeform brainstorming, sketching, and ideation. This is the time to think big and explore possibilities.

- Flow Diagram: Map the flow of the user through the configurator, include states and information sources, iterate based on stakeholder feedback.

- Wireframe: Focus on layout and functionality, group controls, display necessary information, gather feedback from stakeholders.

- Prototype: Create a high-fidelity mockup of the configurator, design controls and groupings, iterate based on feedback, obtain stakeholder approval.

- Implementation: Use the component guide to build the form, utilize variables for consistency, consider CSS for advanced styling, test on different devices and browsers.

Remember, the UX development process is iterative. Keep refining and improving for a better user experience.
