1. Welcome / Introduction
2. Overview of what will be covered
3. What is UX Design?
4. What is UI Design?
5. Why should you care about UX?
6. Identify
   1. Why do you have a configurator? (what is the goal?)
   2. Who is your audience? (exisiting users, new users, internal, external, etc)
   3. If you have an existing implementation, what are the pain points?
   4. Work with stakeholders to identify goals, timeline, and resources
7. Research
   1. Collect user feedback from the way they are currently accomplishing these tasks (existing implementation, manual process, etc)
   2. What tools are they already using? (can you make your tool similar to those?)
   3. What are the pain points? (what have users complained about, what errors have occured?)
   4. What are the users needs, goals, and expectations?
   5. What devices / browsers are they using?
   6. What accessibility needs do they have?
8. Accessibility
   1. What is accessibility?
   2. Why is it important?
   3. How can you make your implementation more accessible?
9. Planning
   1. Once you have identified the pain points, set goals, timeline, and budget
   2. Are you going to make incremental changes, or a complete redesign?
	  1. Top Down vs Bottom Up
	  2. Modify existing projects, or start from scratch?
   3. Identify who will be working on what
	  1. Do you need assistance from other departments such as marketing or IT?
10. UX Design (Top Down)
	1.  Start by writing down notes and thoughts
	2.  Draw a flow diagram
			Pen and paper, LucidChart, Figma, PowerPoint, whatever you are comfortable with
		1.  What pages are there?
			1.  Who can access them?
			2.  What is their purpose?
		2.  What sources do they draw information from? 3D Preview, SQL, API, etc
		3.  Collect feedback from stakeholders
	3.  Create list of pages (or frames) and what controls are needed on each
11. UI Design
	1.  Create wireframe mockup
			Pen and paper, Figma, etc
		1.  First the overall layout (header, sidebar, main content, etc.)
		2.  Then how the controls are laid out, grouped together
			Feel free to put controls on index cards and move them around on a table or whiteboard
		3.  Mockup for different size screens (if applicable)
		4.  Iterate, iterate, iterate
		5.  Get feedback from stakeholders
	2.  Design components
			You'll want to use the same method here as you will for your high quality mockup
		1.  Which font, color, size, etc for individual components
			Involve your marketing department to get brand rules of any brand representation
		2.  Common groupings of components
		3.  Common spacing or alignment
		4.  Get feedback from stakeholders
	3.  Create high quality mockup
		1.  A representation of the final product, outside of DriveWorks
			Typically Figma or Adobe XD, but could be PowerPoint or something else
		2.  Iterate, iterate, iterate
		3.  Get feedback from stakeholders!!!
		4.  Once completed it should be saved as pdf and signed off by stakeholders
			Think of this as like a CAD drawing before you start manufacturing
12. Implement
	1.  Use your component guide to make a form that has an example of each of the items (or groups) you need
		1.  If you are using DriveWorks 21+, you can use CSS to style your components
			1.  Define a list of metadata tags that you will use and how they are used
			2.  You can assign metadata tags now, then write CSS for them later
	2.  Use variables wherever possible to keep things consistent
		1.  If using CSS, you can create variables there as well
		2.  I recommend retaining size and position in DriveWorks, and using CSS for color, font, etc
	3.  Use your high quality mockup as a guide
13. Feedback loop
	1.  Your job is never done: you can always take feedback and improve



## Why?
"Why should I care about UX?"
Let me answer you with another question:
Why do you have a configurator?
- Is it to drive more sales?
- Is it to reduce errors?
- Is it to save engineers time?
The goal of UX design is to help make technology easier to understand and more enjoyable to use.
By being easier to use, will you be able to get more people to use it? Will they be more likely to buy into it / get excited with you?
- can you increase the adoption rate?
- can you change the configurator decrease errors? save time?
- can you change it so you don't have to train people to use it?
If by making the configurator easier to use, you can increase sales, reduce errors, or save time, then there is your UX value.

If you acre starting a new implementation, you can use from a "top down" approach, where you can focus your DriveWorks efforts on implementation instead of design and move forward with a clear design plan.
If you are modifying an existing implementation, you can use a "bottom up" approach, where you can start by identifying pain points and solving them one at a time. 
Some sites and apps go through a complete redesign when they go through a "top down" design approach, and they can use them as an opportunity to market the new features and improvements.
"New and Improved" "Try our Configurator 2.0!" etc.
Sometimes this is neccessary if your users have it in their head that your site is unfriendly, whether you have since solved their pain points or not

## What?
"What is UX Design?"
- UX stands for User Experience, and it is the process of enhancing user satisfaction with a product by improving the usability, accessibility, and pleasure provided in the interaction with the product.
- reduce roadblocks and friction
- make it easier to use
- reduce mental load
- reduce mistakes
- improve user adoption

"What is UI Design?"
- UI stands for User Interface, and it is the various elements a user interacts with to control a machine or software. This includes everything from screens, pages, buttons, icons, etc.
- the look and feel of what the user interacts with
- colors - what does each one signify?
- font-family, font-size, font-weight - what does each one signify?
- contrast, delination, spacing, alignment
- readability, clarity, consistency

If you have two different people working on these you can think about them as being like the difference between an engineer and a draftsman. The engineer identifies and solves problems, prototypes, experiments, and iterates on the design (like a UX designer) while the draftsman implements how it is shown to a user (the UI designer). Just like your draftsman likely have templates for various drawings, in UI design you typically start from a template and existing components, and modify them to fit your needs.

## Who?
Who is your audience?
- What are their needs, goals, and expectations?
- What devices / browsers are they using?
- What accessibility needs do they have?
- Are you making a public facing website, an internal tool, or a tool for a specific user?
- What tools are they already using? Can you make your tool similar to those?

"UX designers help make technology easier to understand and movre enjoyable to use" -Google
-how people use or interact with products

The user experience is how a person feels about interacting with a product
-improve usability
-make something easier to use
-design, structure, and purpose are clear to everyone
-think about everyone who uses the product: make it so it is equitable to them
-make a positive connectection between the user and the product

UX designers come from different backgrounds and educations
-gookd sense for visuals
-desire for optimization
-curious about how people's minds work
-empathetic

Intercation, Visual, Motion
Interaction- match users needs to business goals and what's feasilbe
Visual - logo, imagery, font, layout
Motion - smooth transition from page to page or state to state
Research - determine users needs, feelings, feedback
Production - assets like component templates, CSS, variables
 - design intent to functioning experience

### Interaction
At this point don't worry about branding, rather focus on the user flow
Strive to make the product easy to navigate and simple for users to interact with
How do we make this action easy for users to complete?
How are things laid out?
Are they consistent?
Do they match the users expectations?
Do they match the users expereince?
Are they logical?
What might a user want or need to do?
-define/scope these actions
-is it feasible?
-is it clear how to start/complete these actions?
-identify friction points

### Visual
-what is the tone of the product? should it have it?
-is this different then the tone of your brand? why?
-logos, illustrations, product images, previews
-colors, fonts, sizes, spacing
-insprie, engage, excite, clarify
-appealling and exciting but not foreign

### Motion
-how do users move through your product?
Any dead ends?
Is it clear how to go somewhere else?
-what are the reprecussions of leaving? If they are irreversible, make sure it is clear
-is it clear how the user got here? (trace, breadcrumbs, page title matches link)
-popups / modals / alerts can be useful, but many users skip them without reading, especially if they are frequent
-these introduce friction, since you work hard to decrease friction ensure they are necessary
-at what points may the user not bail, back up, go somewhere else? Is it intentional? Is it clear? Is it necessary?
-balance flexibility with focus

### Research
-As designers, engineers and managers it is our job to identify pain points and solve problems. As a product creator you have no product unless it solves a problem
- CAD solved the problem of needing to hand draw every part
- SOLIDWORKS solved the problem of allowing CAD to be flexible, editable, and dynamic (parametric)
- DriveWorks solved the problem of needing to create a new CAD file for every variation
- UX research seeks to identify what the pain points are, and how to solve them so you may start to solve them
- if your design is perfect with no pain points, no need to bother redesigning
- why might a user decide not to use your product?
- what might frustrate them or slow them down?
- what might they not understand?
- who are your users? what are their needs? what are their goals? what are their expectations?
- what devices / browsers are they using?
Most of all get feedback from your users. FEEDBACK FEEDBACK FEEDBACK

### Planning
- set goals
- set a timeline
- set a budget
- allocate resources
- what is appropriate for your goals, budget, and resources?

### Accessibility
- 1:6 people have a disability: don't alienate them
- making things accessible benefits everyone
- Not everyone will interact with your implementation the same way
- Everyone has a different set of eyeballs, brain, hands, experience, etc
- Unless you are just running DriveWorks User on a single machine, they will experience via different monitors, computers, screen sizes, etc
- Focus your efforts on your expected users / your target audience
- If you are making a public facing website, you should consider everyone
- if you are making an internal tool, you may be able to focus on a smaller set of users 
- If you are making a tool for a specific user, you should focus on that user
- hardly anyone wants to read small print, or low contrast text, or even disorganized inputs
- so what's the harm in making text larger, or higher contrast, or more organized?
- a majority of folks in mechanical and manufacturing engineering space are males over 25. Vision accuity declines with age and males are much more likely to have color blindness
- - if this is your target audience don't rely on color alone to denote meaning
- for example, to denote a required field, don't just make the outline red, also put an asterisk
- if you have a color picker for paint, make sure to include the color name, not just the color
- don't put colored text on a colored background: at least one of the two should be neutraly
- monitors only product light in red, green, and blue, so yellow and white can be hard to distinguish
- forms can be navigated using the tab and shift tab keys (tab index)
- this was originally intended for folks who can't use a mouse, but it is also much faster for everyone
- Avoid distractions. No flashing!
- Avoid clutter - everything on the page should have a purpose: function, information, or grouping
- are like items grouped together?
- are items not relevant hidden? If a control is disabled, is it clear why?
- setting the height of an element to 0 is a neat trick if each of controls use each other for placement, but it's more performant and less jarring most of the time to just hide it
- too many controls on a page can be overwhelming
- are they all necessary?
- if you have a lot of controls, consider breaking them up into sections using pagination or tabs
- Some people use screen readers to assist navigating the web: DriveWorks is not yet setup for this, so consider giving an alternative method, such as a phone number or email address
- some people are dsylexic. there are fonts that are firendlier such as Georgia, and OpenDyslexic, but even sticking to sans-serif fonts and avoiding italics can help. 
- even if you aren't dsylexic, it's faster to scan and typically takes less energy to read
- Avoiding long sections of text is also helpful - people will likely skim it anyway
- Let eacvh element breathe!
- Consistent spacing look more professional, is easier to read, and is easier to navigate


# Process Outline

1.  Start by writing down notes and thoughts
2.  Turn notes into Flow Diagram
	1.  User Flow
		1.  Do different users have different flow? Such as Admin vs customer vs sales?
	2.  Data Flow
	3.  Process Flow
	4.  Spec Flow
3.  Create project outline of who does what when
4.  At this point you can split into individuals to each work on different things
	- File management, renaming
	- CAD creation, optimization
	- Document management, creation, optimization
	- API connections
	- Web Creation
	- 3D Preview
	- etc
	- **UI / UX** 
	- This includes everyone working in their own DriveWorks project
5.  Look through other implementations for inspiration.
	- Existing solution
	- Other processes in the company
	- Competitors
	- Software common to users: such as SOLIDWORKS or Outlook, etc.
6.  Get brand rules from Marketing department
	- Fonts, colors, logos, etc.
7.  Quickly sketch out rough ideas on pen and paper or whiteboard
	- Iterate, iterate, iterate
8.  Create wireframe mockup (in Figma) to capture roughly where things will be, and what buttons, inputs, pages
	- Iterate, iterate, iterate
	- Get feedback from stakeholders
	- Wireframe should include possible future features
9.  Create high quality mockup (in Figma) with icons, colors, full professional look
	- Iterate, iterate, iterate
	- Get feedback from stakeholders, marketing
		- With Figma you can share an interactive link
	- Leave possible future features as wireframe, and circle back as needed when applicable
10. Identify which items correspond to which DriveWorks components
11. Identify patterns of similar items for metadata tags (and/or copy paste in DriveWorks)
12. Make a Form that has an example of each of the items you need: by component, by tag
13. Write CSS for these components 
	- Component default CSS
	- Metadata Tag CSS
	- Iterate, iterate, iterate
14. Build UI in DriveWorks (keep it in it's own project)
	- Use Name CSS sparingly
	- Use positional CSS not at all or sparingly
	- Use relational CSS not at all or sparingly
15. Finally, integrate with the other projects
	1.  You can import a project into another group
	2.  You can copy your form controls into another project
	3.  You can export forms as templates (with associated variables, tables)
	4.  You can run your UI project standalone and call other projects using spec host
		- Great for larger projects with several people working on them
		- Can be done earlier in the process if needed
		- Easier to isolate issues
		- Better for collaboration
		- Better for project reuse

# Why to use Figma

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

&nbsp;

# Flow Diagram Software

If you have something already, use that. If you know something already, use that. Talk with your company with what others are using. Otherwise, consider these:

- Figma has an option called FigJam
	- Easier to learn Figma + FigJam then Figma + other software
	- Integrates well with Figma
	- Consolidated licensing
- LucidChart is industry leader
	- integrates with Professional services such as SalesForce, Microsoft 
	- Use LucidSpark to quickly capture ideas, then LucidChart to make flow diagram
	- Most features, most templates
	- AI assist
- PowerPoint
	- Likely already have license(s)
	- Likely already know the software*