
# creating a new website process : 

the first step that we should understand the audience that they are visiting our website also that we design the website for the audience to make them satisfy and help them to achieve there goals  that we can see the list below that the point we should follow to understand our target:

•	Age range of the audience 

•	The gender of target audience 

•	Where the audience living 

•	Occupation and income that they can control 

•	Hours that they work per week and the job position 

•	The king of device they are use

Then we should understand that *why the audience visiting the web site?* is the visitor have a specific goal ? our he just spend a time so that will help us to work out what information they need in order to achieve their goals quickly and effectively.

We should understand how match we need to update information to the audience  depend on the our product type , now that we can organize the information to appear in our website and divide it to the pages or sections 

Now ae can create the site map that will  show where is every information  should be ? and how these information will integration to each other for example see Fig 1 below 

![](https://github.com/MURADALSHORMAN/Readme/blob/main/fig1.JPG)


## wireframe

wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

The wireframe will make us sure that all information we are need that will be on the website also in the correction place for example see Fig 2 

![](https://github.com/MURADALSHORMAN/Readme/blob/main/fig2.JPG)












# HTML Layouts

HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them.

### Headers & Footers

The main header or footer that appears at the top or bottom of every page on the site.

For example
1. header
```
<header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
```

2. Footer 
```
<footer>
&copy; 2011 Yoko's Kitchen
</footer>
```

3. Navigation
The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.
  
```
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
```


4. Articles

The article element acts as a container for any section of a page that could stand alone and potentially be syndicated.

```
<article>
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>
<p>A five week introduction to traditional
Japanese vegetarian meals, teaching you a
selection of rice and noodle dishes.</p>
</article>
<article>
<figure>
<img src="images/teriyaki.jpg"
alt="Teriyaki sauce" />
<figcaption>Teriyaki Sauce</figcaption>
</figure>
<hgroup>
<h2>Sauces Masterclass</h2>
<h3>One day workshop</h3>
</hgroup>
<p>An intensive one-day course looking at how to
create the most delicious sauces for use in a
range of Japanese cookery.</p>
</article>
```

Article
The *aside* element has two purposes, depending on whether it is inside an <article> element or not.

```
<aside>
<section class="popular-recipes">
<h2>Popular Recipes</h2>
<a href="">Yakitori (grilled chicken)</a>
<a href="">Tsukune (minced chicken patties)</a>
<a href="">Okonomiyaki (savory pancakes)</a>
<a href="">Mizutaki (chicken stew)</a>
</section>
<section class="contact-details">
<h2>Contact</h2>
<p>Yoko's Kitchen<br />
27 Redchurch Street<br />
Shoreditch<br />
London E2 7DP</p>
</section>
</aside>
```


5. Sections
The *section* element groups related content together, and typically each section would have its own heading.

 ``` <section class="popular-recipes">
<h2>Popular Recipes</h2>
<a href="">Yakitori (grilled chicken)</a>
<a href="">Tsukune (minced chicken patties)</a>
<a href="">Okonomiyaki (savory pancakes)</a>
<a href="">Mizutaki (chicken stew)</a>
</section>
<section class="contact-details">
<h2>Contact</h2>
<p>Yoko's Kitchen<br />
27 Redchurch Street<br />
Shoreditch<br />
London E2 7DP</p>
</section>
```
 


6. Heading Groups
The purpose of the *hgroup* element is to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.

```
<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>
```

7. Figures

You already met the *figure* element in Chapter 5 when we looked at images. It can be used to contain any content that is referenced from the main flow of
an article (not just images).

```<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
```


8. Sectioning El ements

It may seem strange to follow these new elements by revisiting the <div> element again. (After all, the new elements are often going to be used in its place.)

```
<div class="wrapper">
<header>
<h1>Yoko's Kitchen</h1>
<nav>
<!-- nav content here -->
</nav>
</header>
<section class="courses">
<!-- section content here -->
</section>
<aside>
<!-- aside content here -->
</aside>
<footer>
<!-- footer content here -->
</footer>
</div><!-- .wrapper -->
```

