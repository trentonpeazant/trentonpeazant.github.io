# Write up:

## Tool evaluation:
1. Jekyll. Pros: simple, prebuilt websites that do not require much but terminal, and a few Ruby/Homebrew downloads.
Also has native Github Pages support. Cons: difficult to use when going at it the "easy" way, which involves forking a repository,
cloning it and such. Can also be tedious for a new user trying to use Git through terminal and can lead to some hangups.
2. Hugo. Pros: Extremely fast and does not require many downloads, unlike Jekyll. It has better handling capabilities for some
specific use cases than Jekyll. Cons: Go can be a steeper learning curve, is too complicated for smaller sites like the ones we are
creating in this class.
3. HTML/CSS. Pros: Gives the user total control over the website, also doesn't have any dependencies due to no reliance on Ruby or Go.
Cons: Can be extremely tedious, especially when not using an LLM. Complex features like search can require a user to write
JavaScript that they originally weren't prepared for.

## Development log:
Most of the site creation was done by following a YouTube tutorial, linked here: https://www.youtube.com/watch?v=fV01b0duZwU&t=2798s.
However, I used Gemini 3 Fast to add some of the finishing touches such as the conversion of my resume into Markdown and the formatting
of my homepage and blogpost pages. What worked was giving the model specific issues or ideas that I had to improve my site, and what didn't work
were some attempts at jazzing up my blogpost page further. I iterated by breaking an issue or a want down into more granular steps, and working along with
the model versus just telling it what to output for me.

Key prompts include:
1. "how can I make my posts page a bit more friendly? it is a bit bland." - Improving the look of the blog page
2. "how can i make my homepage more appealing? all it has is my "recent posts" of which I have one.
I would like to make it an overview of the site along with a heading-like picture" - Improving the landing site
3. "how do i change the colors to a dark theme" - Putting my personal touch on the site

## Site description:
This is a website that will be used for personal and professional purposes. It has my contact information in my About page (that also
includes some more info about me), resume, and 
a blog for me to post about my cultural interests, as well as whatever may be going on in my personal research, coursework, or (hopefully) a
job in these coming months (hopefully). I used the "minimal mistakes" Jekyll theme, and I changed the skin to be dark because I 
personally like all of my devices to use dark mode.

## Reflection:
In making this website, I learned that AI is a good tool for at least providing some stylistic touches to a website using Jekyll in my case.
AI has helped me with some of the annoying syntax for these .yml files which proved to save tons of time. I did not use it much, but some of the
limitations in my usage were that the model seems to stick to issues that were previously solved, especially when a user passes in previous files
for model review. This can be frustrating as it will eat up tokens by lengthening its output to include an issue that was fixed 5 prompts ago. 
I do not think I would do anything differently next time, but if I were to choose something, I would read some more of the documentation before running
to an LLM for help. Either that, or just giving the AI the documentation and have that be a foundation for all the help and questions I may have.
