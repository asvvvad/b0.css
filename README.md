# b0.css
simple responsive css style for things

based on [starveling](https://github.com/any-code/starveling)

CSS style I made back in 2017~ when I was into web

I was aiming for something lightweight and simple but looked beautiful and is responsive.

It's based on Starveling CSS but I changed most of the stuff for what I saw fit
I made it for my website and my chat (which was meant to have the same characteristics)


I lost both the chat, it was beautiful, the back-end was spaghetti code but the interface was
how i wanted it to be and I was proud of it. I might recreate it again since this was saved, but not so soon; still unlikely.


this site is an example of this style. it have two themes: Black and White. I did a dark blue theme but I got rid of it.
it's easy to make themes since this style is pretty simple, see the white.css or black.css for reference.
The b0.css don't have any color definitions so a theme.css is required; well not really, it looks like a plain black on white page, links will look blue after you visit ect, you may be okay with that which is good so do as you wish-if someone use this at all.

## Quick Guide:
```
<body>
	<div class="container">
		<nav class="tacenter amiddle">
			<a href="#">link</a>
			<a href="#">link</a>
			<a href="#">link</a>
			<a href="#">link</a>
		</nav>
		<header class="tacenter">
			<h1>Title</h1>
		</header>
		<hr>
		<div class="content">
		<article>
			<h2>Article Title</h2>
		</article>
		</div>
			<footer class="tacenter">
			<p>Copyleft&copy;</p>
		</footer>
	</div>
</body>
```

the container div keeps the content centered it will expand on mobile, good for blog ect
it can be removed if you want to handle the margins manually (like i did for my chat which took all the screen)</p>

That's about it, any questions [contact me](https://asvvad.eu.org/?page=about#contact) or open an issue
