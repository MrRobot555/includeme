The widget can be placed on any HTML (or PHP) page.

These two lines has to beincluded in the head section:

    <script defer src="https://unpkg.com/alpinejs@3.x.x/dist/cdn.min.js"></script>
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">

One is for Alpine JS, the other one for Tailwind CSS.


The widget is imported with this single line which should be placed just above the closing tag of the body:

    <script src="embed.js"></script> 


Two injections takes place : first the code is injected into the HTML page. Second, upon clicking onto the icon in the right bottom corner, the embed code gets
injected into the modal, and runs.

The embed.js is a one line style on purpose so that it's kind of invisible for the user. However I have prepared a second version: index_injected.html - this is
not needed to run the widget, it only serves for a better understanding of my code as it is the human readable format.

I tried to make the whole composition as lightweight as possible.