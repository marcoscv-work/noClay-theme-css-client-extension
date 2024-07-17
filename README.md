# noClay Client Extension

This client extension removes the 96% of Clay usage, perfect for starting your non-Clay/Bootstrap based Liferay project.

The gziped weight of the `clay.css` and `main.css` is 18kb.

For testing, you can use the compiled file [noClay-theme-css-client-extension.zip](https://github.com/marcoscv-work/noClay-theme-css-client-extension/tree/main/dist), just move it to your `deploy` DXP 7.4 directory.

It includes the basic styles to use the Page Editor; grid, helper classes etc. And also includes a Basic set of Tokens.

https://github.com/user-attachments/assets/73713c31-3ee6-4858-af23-b319bc4ca481

If you need to add more Clay components, for example `Modal`, you can just uncomment the lines on:
[clay/_components.scss](https://github.com/marcoscv-work/noClay-theme-css-client-extension/blob/main/src/css/clay/_components.scss):


