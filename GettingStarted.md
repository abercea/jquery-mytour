# Introduction #

Have you ever though into create a virtual tour for visitants of your website? With a tour you can guide people who access your site across the main information or funcionalities! Isn't cool?


# Details #

Since you're using MyTour plugin you can expect:

  * An easy way to implement a virtual tour;

  * Totally customizable;

## How to use it ##

> Import "mytour.js" on the HEAD of your page:

```
  <link rel="stylesheet" type="text/css" href="mytour.css" />
  <script type="text/javascript" src="mytour.js" ></script>
```

> Set all steps of your tour:

```
  <!-- TOUR CONTENT -->
  <ul id="my-tour-steps" style="display: none;">
    <li data-id="#element-id-1" data-position="bottom" >
      <!-- PUT ALL YOUR STUFF HERE -->
    </li>
    <li data-id="#element-id-2" data-position="top" >
      <!-- PUT ALL YOUR STUFF HERE -->
    </li>
    <li data-id="#element-id-3" data-position="left" >
      <!-- PUT ALL YOUR STUFF HERE -->
    </li>
    <li data-id="#element-id-1" data-position="right" >
      <!-- PUT ALL YOUR STUFF HERE -->
    </li>
  </ul>
```

> Then, you just need to call it:

```
  <link rel="stylesheet" type="text/css" href="mytour.css" />
  <script type="text/javascript" src="mytour.js" >
      jQuery(document).ready(function(){
         $('#trigger').mytour();
      });
  </script>
```

> Done! Isn't cool?

## What will happend ##

That's ok! It's too much easy, but what will happend after?

When you click on the trigger element, the tour will starts. Also there is an option to play it automaticaly.

For each li that you set on "my-tour-steps", a balloon will be showed with your stuff. The viewer can control which step s/he wanna goes thru and can goes backward or forward anytime.

---

Well, that's it! Easy, don't you think?

If you have any suggestion, critics or just wanna say hello, feel free to mail me or leave a comments here. I'll certainly answer as soon as I can.

Happy coding! =)