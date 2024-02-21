This is a set of config files (PolyPane workspaces - .ppws extension) that are geared towards testing for accessibility issues. It is not an exhaustive collection, just a subset of views that I have personally found very handy to have available for side-by-side visual comparison.

Included here are:

* **Full Set** - A good cross-section of view that includes light mode and dark mode comparisons, forced colors (AKA 'High Contrast'), SC 1.4.4 Resize Text and SC 1.4.10 Reflow views and CSS disabled.
* **Light, dark & High Contrast Modes** - Just these three modes for easier comparison of color and contrast issues.
* **Resize and Reflow Checks** - Just two panes to assess text resize and reflow issues.
* **Text Spacing** - 4 panes set for mobile, tablet, laptop and large desktop with text spacing settings applied (to test SC 1.4.12 Text Spacing).
* **Color Blindness Simulations** - Side-by-side views showing the color blindness simulations for Deuteranomaly, Deuteranomia, Protanomaly, Protanopia, Tritanomaly, Tritanopia, Achromatomaly, Achromatopsia, and Achromatopsia (Cerebral).

## How to install

1. <img width="482" alt="Show the side panel by pressing the toggle button" src="https://github.com/lloydi/PolyPane-Config/assets/2778763/effa198f-c632-4ef3-9ba6-09f7c8e74d6b">
2. <img width="395" alt="Select 'Workspace' then 'Custom'" src="https://github.com/lloydi/PolyPane-Config/assets/2778763/40da0bb4-f2ca-4ac1-b597-24339ac3c560">
3. <img width="380" alt="Select the 'More options' button" src="https://github.com/lloydi/PolyPane-Config/assets/2778763/12828b05-fd75-473e-a309-04c6ea8985f8">
4. <img width="399" alt="Select 'Import' and choose the .ppws files" src="https://github.com/lloydi/PolyPane-Config/assets/2778763/80e075c5-986d-4051-bf2a-33cda96e3544">

## Important note re Text Sizing

The panes in the 'Resize and Reflow Checks' collection have been set such that they do not respond to font size adjustments, apart from the Text Sizing one. The chances are, you will have your font size set to 100%. 

<img src="resize-err-1.png" alt="">
<img src="resize-err-2.png" alt="The 200% setting shown on the pane is for scaling the pane, not the font size">

You will need to boost that up to 200%. Here's how you do it:

<img src="resize-err-3.png" alt="Change the text size by using View > Zoom Web Pages">

Note the difference between the two middle panes here (the second one is correct):

<img src="resize-err-4.png" alt="">
<img src="resize-err-5.png" alt="">
