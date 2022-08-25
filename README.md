Questions that came up during the site build:

- Hero Section
  1. Is there a better way to handle the floating icons than a relative position container and absolute position items?

- Why Front? Section
  1. The only way I could get the bubble components to not overlap was to set a width for each bubble item. Is this the best way of accomplishing this section, or would there be a property that could accomplish this better?
    - I tried justification properties on the flex container, but everything left a gap between the lines, or cause significant overlap unless paired with a set width.
    - I think I was able to get this sorted out by setting a length on the line itself. It is not responsive in mobile without changing the style at a snap-point, which I would have to do anyways as it is changing to a vertical layout.

- Spotlight (Hubspot) Section
  1. This section caused me a lot of problems. I couldn't find a better way to position everything correctly without setting the height and width of the image container in rem units. I tried using flex properties but nothing was able to adjust it correctly. Is this the best approach to something like this? (Short of making it one image to deal with instead of overlapping)

- Pricing Section
  1. Why when I set a max width of anything on the info-card does it put all of the grid items in a single column?
    - I had a bandaid solution of setting the wrapper grid-template-column to 1fr 1fr, but then it doesn't wrap properly. With the repeat in the grid-template-column, I can't seem to find the right adjustments.

- Form Section
  1. I had issues with the sizing of the form in this section. It seemed to want to take up too much space.


- Responsive Design
  1. Is there a better way to handle the icons so that they shrink to fit the space? I ran into an issue of the icons going off screen between the tablet snap point and the mobile snap point.

  2. I think the answer to #1 will also answer resizing the Hubspot pictures to fit the viewport properly.



Thank you very much for your feedback! I have had an awesome time learning this stuff. I had a pretty good general knowledge of HTML and CSS coming into the course, but I feel like this course has helped me to understand why properties and elements work the way they do. Being able to look at a page and understand the general flow and figure out how you want to tackle sections is not a skill I had before this course, so to you and everyone else at Devslopes, thank you!