# TailwindCss_Learning


-display
    Determines how the element behaves in terms of layout and visibility within the document
        .block
        .inline
        .inline block
        .none 
        .flex
        .grid

-Position 
    Detemines how an HTML element is positioned within its containing element or overall website
        .Relative
        .Fixed
        .Absolute
        .Sticky

-overflow

-Dark theme :
    1st modify the config.jd And Add [darkMode: "class",]
    in the class add dark: to add a specification for the dark theme
    google the rest

Custom styles:
1st method:
    text-[#97F29]
    p-[16px]
2nd method:
    add to the extend in the config file 



directives:
    add to the base CSS file and add the next code (example)
    @layer components {
        .card {
            @apply  tailwind classes example : m-10 bg-white ....
        }
        <!-- you can add more here and use them in the html in the class  -->
    }


you can use already existing components libaries
    -shadcn
    -tailwind ui
    -headless ui
    -etc....


Margin -- Border -- Padding -- XXX -- Padding -- border -- Margin 