# Bluewindow-tablet-task

In practice, many designers convert pixels to ems, largely because ems afford better zooming. At standard zoom 1em === 16px, multiply pixels by 1em/16px to get ems. For example, 320px === 20em.

In response to the comment, min-width is standard in "mobile-first" design, wherein you start by designing for your smallest screens, and then add ever-increasing media queries, working your way onto larger and larger screens.


# NOTE

I dont know if I'm right but it's harder to target specific devices or sizes. In the project I'm trying to reframe the term 'Breakpoint':

1: Develop the site for mobile first using percentages or ems, not pixels. (in the project I'm using both.)
2: Then try it in larger viewport and note where it begins to fail. (I have never own or worked on Tablet so it was very challenging for me to visualise and solve the problem)
3: I'm trying to redesign the layout and add a CSS media query just to handle the broken parts. (I want to show you the stages of my thinking process, I'm going to find solution for the broken parts of the site and the app)
4: I decide to give you the project the way it is. So you can see my weak parts of using CSS. I've got planty of experience but the projects and the tasks you gave me was challenging. You helped me a lot in my learning journey.

# I'm trying to use NATURAL breakpoints
The 'breakpoints' become the actual point at which your mobile design begins to 'break' i.e. cease to be usable or visually pleasing. Once I have a good working mobile site, without media queries, I wil stop being concerned about specific sizes and simply add media queries that handle successively larger viewports.

![tablet-solution](https://user-images.githubusercontent.com/117073615/225906608-bc16ea21-0b9e-42e7-b15e-379174f85beb.png)
