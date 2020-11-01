# EJS Partials
- Partials are basically just views that are designed to be used from within other views. They are particularly useful for reusing the same markup between different views, layouts, and even other partials.
*Partials come in handy when you want to reuse the same HTML across multiple views.

- Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

- In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters

- Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

- The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…

![](https://miro.medium.com/max/850/1*usicWavHRKy4Sjm2XTCBMA.jpeg)



--------------------------------------------------



[Table Of Content](https://github.com/omarXzain/301-reading-notes)
