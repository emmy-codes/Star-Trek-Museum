# Star Trek Museum -  Testing

![Star Trek Museum](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/506ff96d-2bfc-4d33-b730-b194c3816380)

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [User testing](#user-testing)

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used for both HTML and CSS testing as Jigsaw is a part of this page. I received a plethera of info notifications about the forward slash on all of my self closing tags, stating it has no effect and interacts badly with unquoted attribute values.

To me this feels an unnecessary problem to fix because it is considered an industry accepted standard to have self closing tags with the slash in them, and since plugins like Prettier add them by default it would be impossible to steer away from using them.

* The contact page had 2 errors and a warning. The errors informed me I cannot have a paragraph tag as a child element of a span. This has now been solved.

### Lighthouse

Lighthouse in Chrome Developer Tools allowed me to test the performance, accessibility, best practices and SEO of my pages.

### Mobile Results

Since the threshold for passing performance is much higher on mobile, I opted to run everything through there first. If it all came out well then I knew that the desktop would be sucessful also.

* [Homepage](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/dac80a5f-912a-493a-98e2-c94f4388c6a5) - Pass.
* [Crews Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/af2d315b-2557-456a-b3c8-0df854d70b73) - Pass. On first try I received a disasterous performance score due to my images from IMDB being extremely large. I ran the images through Squoosh and was able to reduce the image size by 94%.
* [Contact Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/c52db375-ef1d-4eb4-8090-acc3772377ff) - An 83 on Best Practices but this is due to the iframe being used on the map, which was a necessary part on my page.
* [Form Submission Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/fe820606-2a53-421b-8b75-49cd23a4dc79) - Pass.
* [404 Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/84b7c45c-fde0-443a-b0a7-e673e3474c4f) - An 83 on Best Practices due to using a gif rather than an image. I will look for a more appropriate error image, but lil' ol' facepalming Picard was just too perfect of a Trek meme reference to leave out!

## MANUAL TESTING

### User Testing

I posted my website onto Facebook for my family and friends to trial and give their input. The decision was unanimous - despite my code passing all the automated testing, users were finding it hard to read the text due to the brightness of some stars in the background. After some panic and research I discovered linear-gradient which allowed me to place a semi-opaque black layer on top of the image, thus allowing for more readability whilst still seeing the majority of the stars.

![User trials](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/614878f2-95b0-408b-9f02-7d9de66d629e)
