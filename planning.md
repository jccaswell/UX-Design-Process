# UX Development Process

## Request

I am very interested in presenting on UI/UX design. I have been diving into the deep end of using Figma to design user interfaces for people and then using the CSS it generates to help create CSS for DriveWorks and have been digging into many ways of using CSS with DriveWorks. I am happy to have some pre meetings with your team to come up with a scope of things to cover.

- 2024-10-23

## LinkedIn Post

I'm happy to announce I will be one of the presenters this year. Come join to learn all about an often overlooked part of making DriveWorks configurations: designing a User Interface. 
I'll be discussing industry standard UI/UX practices, how to take it from cradle to grave, and how you can implement it in your next or current DriveWorks implementations!

- 2024-01

## Outline

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

I also have these notes on software that I am on the fence if I am going to include or not.

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


# Flow Diagram Software

If you have something already, use that. If you know something already, use that. Talk with your company with what others are using or what you have licenses for. Consider these:

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
      - Likely already know the software