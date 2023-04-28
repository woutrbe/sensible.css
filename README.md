# sensible.css

## The reasoning behind sensible.css
In complex applications or websites, CSS can be extremely hard to maintain, you often find yourself duplicating values or colors. With tools like SASS or LESS, you can easily extract those values and introduce variables. But this requires and aditional build step, wheres traditional CSS can just be embedded into any web page, or as a single stylesheet.

Tailwind CSS has become an almost standard these days, many people enjoy using a set of default classes to quicly style their webpages. But one of the main downsides is that you'll quickly end up with bloated classnames, and making design changes can become a very tedious process. If during a redesign you want to change all blue buttons to a slighly darker blue, you'll need to do a find and replace all for `text-blue-300` and change it to `text-blue-500`. Instead you could've simply used traditional CSS, gave all those buttons a `.btn` class and you would only have to change a value once.

I do however understand the appeal of Tailwind CSS, having that set of default colours and values is extremely useful, this is where sensible.css originated from. My goal is to simply provide a set of default CSS variables, that can be used in any project.