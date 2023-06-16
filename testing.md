# Star Trek Museum -  Testing

![Am I Responsive Index](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/f6d9256b-dc20-49c0-b1ef-da1b785a9987)

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [User testing](#user-testing)

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used for both HTML and CSS testing as Jigsaw is a part of this page. 

##### HTML

I received 9 notifications about the forward slash on all of my self closing tags, stating it has no effect and interacts badly with unquoted attribute values.

To me this feels an unnecessary problem to fix because it is considered an industry accepted standard to have self closing tags with the slash in them, and since plugins like Prettier add them by default it would be near impossible to steer away from using them. I have filtered them out of the screenshot for ease of reading.

* [HTML Check Index](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/09561864-8773-4016-ba10-ee5bff22ff99) - No errors or warnings.
* [HTML Check Crews Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/bfdc27f6-e838-4b06-ae02-04c915444be8) - No errors or warnings.

* [HTML Check Contact Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/e14128ad-2d1f-416c-a2ba-cb7a2116fe89) - The contact page had 2 errors and a warning. 
  The errors informed me I cannot have a paragraph tag as a child element of a span. This has been solved.
  The warning reminded me to not use a section tag when there are no H tags inside of it. Changing this tag to a div tag made many changes to my CSS that I unfortunately didn't have time to rectify before handing in. My commits throughout the project have notations about changing other section tags due to lack of H tags so I was aware of the issue, but had unfortunately missed this one out.
  
* [HTML Check Form Submission](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/9f7be74c-1eb7-4e5e-b202-1879a81a4531) - No errors or warnings.
* [HTML Check 404](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/8b5094a7-77ca-4247-bca9-7eb50d3a2f05) - No errors or warnings.
  
##### CSS
  
* [CSS Check Index](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/fe8e2a48-0241-4060-ae26-3ac3d5aa718b) - Validated/no errors.
* [CSS Check Crews Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/3ce4e8b8-c04b-4028-820f-22f2559e431b) - Validated/no errors.
* [CSS Check Contact Page](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/6c25a5d4-eec7-4161-9e9f-f6a124d7c9e9) - Validated/no errors.
* [CSS Check Form Submission](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/29bf1cc1-eba5-4f07-ab9b-423d4582ab09) - Validated/no errors.
* [CSS Check 404](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/1cacffaa-aae5-4f98-84d8-c03dfda176cb) - Validated/no errors.

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

#### User Stories

* New Users:

I wanted to see how new users would experience my site, so I posted it to Facebook for my family and friends to try and give their input. The decision was unanimous - despite my code passing all the automated testing, users were finding it hard to read the text due to the brightness of some stars in the background. 

[User trials](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/614878f2-95b0-408b-9f02-7d9de66d629e)

The same feedback came from posting on peer-review on Slack, so after some panic and research I discovered linear-gradient which allowed me to place a semi-opaque black layer on top of the image, thus allowing for more readability whilst still seeing the majority of the stars.

* Existing Users:

I asked two of the people giving this feedback to check after I made the change to see if it was adequate. 

[Existing User Feedback](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/f9b625ff-8a3e-4844-a51b-dbc5a022e32b)

I had planned to have more guidance in the form of extra navigation buttons and some CTAs but due to time constraints they were left out, but I am glad to see that the page is intuitive enough for both new and returning visitors to the site. 
