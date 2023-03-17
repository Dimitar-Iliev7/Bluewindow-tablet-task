# Bluewindow-tablet-task

@media (min-width: 320px) {
  /* smartphones, iPhone, portrait 480x320 phones */
}
@media (min-width: 481px) {
  /* portrait e-readers (Nook/Kindle), smaller tablets @ 600 or @ 640 wide. */
}
@media (min-width: 641px) {
  /* portrait tablets, portrait iPad, landscape e-readers, landscape 800x480 or 854x480 phones */
}
@media (min-width: 961px) {
  /* tablet, landscape iPad, lo-res laptops ands desktops */
}
@media (min-width: 1025px) {
  /* big landscape tablets, laptops, and desktops */
}
@media (min-width: 1281px) {
  /* hi-res laptops and desktops */
}

In practice, many designers convert pixels to ems, largely because ems afford better zooming. At standard zoom 1em === 16px, multiply pixels by 1em/16px to get ems. For example, 320px === 20em.

In response to the comment, min-width is standard in "mobile-first" design, wherein you start by designing for your smallest screens, and then add ever-increasing media queries, working your way onto larger and larger screens.

![tablet-solution](https://user-images.githubusercontent.com/117073615/225906608-bc16ea21-0b9e-42e7-b15e-379174f85beb.png)
