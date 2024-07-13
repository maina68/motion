# motion
# Ways to integrate modules of code
One of the beauties of coding in the modern era is that many people share their code so that we can benefit from their work, cost-free. It's a mix of benevolence, wanting to move the world forward, trying to make a name for themselves, adding to their own résumé, and hoping that you too will open source your code so they can use it. One of the most important things we do as a JavaScript developer is integrate these modules of code. We'll see two ways to do that today.
# 1 option: Using Popmotion
There are so many things we could integrate. There are literally hundreds of thousands of libraries for JavaScript. But today we're going to use one called Popmotion. Popmotion is an amazing library that allows you to make super cool animations

Notice that we're using this popmotion object. This is being injected into the page by the script we loaded before ours in the HTML. This makes it possible for us to use the object.

The code we put there uses the Popmotion library to make it so the blue ball springs back and forth using realistic physics. Really cool, right? This is not something the browser knows how to do natively, but using JavaScript it can! If you want to play more with Popmotion, see their docs.https://popmotion.io/#quick-start-animation-animate-options

So this is the quick and easy way to integrate a library. An average website will have at least ten and as many as hundreds of these dependencies. It's not feasible to put all those script tags in your HTML. There is a better way!
