# A short reflection on this school project

After a year of studying Multimedia design, I still find it challenging to delegate my time and determine priorities. Especially when it comes to working on multiple pages like this one, but despite all of the struggles I am generally happy with the result.

 However, having said that, I will already let you know I had completely forgotten about making a burger menu in mobile view, so good luck navigating around on a smaller viewport than 600px. 🤥

## So, what are some more practical take-aways?

In earlier assignments, I have often had the responsibility to work with slugs and data fetching, so that in itself wasn't too hard for me to figure out. 

I believe the main struggles have been to figure out how to make things as least complicated as possible. Especially with styling and structuring the websites and/or components. It sometimes feel as if I have to jump between dedicated .css files, to pages and/or to components to be able to get the right train of action going on. But towards the end I was actually able to figure out how to communicate "across" files, which propbably would have saved me some hours 😵‍💫

![Screenshot](styling.png)

In this example above, I am inside the component of **SingleViewCard.astro**, where I want the **TitleColored.astro** component to change colour when the *entire card* is being ***hovered***. All of this because I wanted to be able to reuse my one component instead of creating a new one or copying the one I already had. 

As a general, I feel as if I have gained a much better understanding of the usability of working with components, especially after we learnt about the use of **[data-theme]** values in CSS. It has not only sped up and simplified web developing, but also become such a huge proponent *for* using compnents. It is just mad cool how one can create one simple button, that is essentially empty of all content, as seen in this picture:

![Screenshot button](btn1.png)

All it has is one element, *<button>*, but it is using JavaScript (what you see in the curly braces {}) to dynamically set its attributes and content. And not only that, but Astro is pretty neat and handles all the js for this, so I don't have to deal with all of that routing as well. 

To finish up the talk about this very dear button, here is the general styling of it:
![Screenshot button](btn2.png)

And here, the button is being used in the **team** page.
![Screenshot button](btn-html.png)

And voilá, a beautiful button, for the client-user! 
![Screenshot button](btn-web.png)

It's beautiful. 

