# nav-menu
In this article, [Solodev]() will teach you how to create a responsive navigation menu with pure CSS. Typically, a mixture of JavaScript and CSS are involved in creating responsive navigation menus which can cause slower load times and and a depreciated user experience (UX). By creating a responsive nav menu with pure CSS, you optimize website load speed and create a more seamless, quick navigation experience for website visitors.

## Tutorial

For detailed instructions, view Solodev's [Creating a Nav Menu with Pure CSS](https://www.solodev.com/blog/web-design/creating-a-nav-menu-with-pure-css.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/1k6t1zhf/).

## HTML

The nav-menu contains the following basic HTML markup.

```
<nav>
   <div class="navbar navbar-fixed">
      <div class="container">
         <div class="navbar-header">
            <a href="/"><img alt="Logo" src="images/logo.png"></a>
         </div>
         <ul class="navbar-nav navbar-right">
            <li>
               <a href="/">About Us</a>
               <ul class="navbar-nav navbar-right">
                  <li>
                     <a href="/">Blog</a>
                  </li>
                  <li>
                     <a href="/">Events</a>
                  </li>
                  <li>
                     <a href="/">News</a>
                  </li>
                  <li>
                     <a href="/">Photos</a>
                  </li>
                  <li>
                     <a href="/">Team</a>
                  </li>
               </ul>
            </li>
            <li>
               <a href="/clients/">Clients</a>
               <ul class="navbar-nav navbar-right"></ul>
            </li>
            <li>
               <a href="/services/">Services</a>
               <ul class="navbar-nav navbar-right">
                  <li>
                     <a href="/">Design</a>
                  </li>
                  <li>
                     <a href="/">Marketing</a>
                  </li>
                  <li>
                     <a href="/">Programming</a>
                  </li>
                  <li>
                     <a href="/">Sales</a>
                  </li>
                  <li>
                     <a href="/">Support</a>
                  </li>
                  <li>
                     <a href="/">Training</a>
                  </li>
               </ul>
            </li>
            <li>
               <a href="/resources/">Resources</a>
               <ul class="navbar-nav navbar-right"></ul>
            </li>
            <li>
               <a href="/">Contact Us</a>
            </li>
         </ul>
      </div>
   </div>
</nav>

```
## CSS

All required CSS is in nav-menu.css

## External Includes

This tutorial contains the following third party resources. 

```
<link rel="stylesheet" href="nav-menu.css">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```
