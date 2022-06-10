# The Pitbull Information Page

I have created this website to educate people about the American Pitbull Terrier, a highly misunderstood and discriminated against breed of dog. In my website, I have included a homepage (featuring a breed charactersitics section, a breed histroy section and breed misconceptions section), a gallery and a quiz. The homepage educates the public about the Pitbull Terrier whilst the gallery showcases photos and videos of various American Pitbull terriers and the quiz tests users' knowledge about the breed. The target audience of this website is dog lovers and anyone who has a negative opinion about the APBT. This website hopes to change that opinion.

## Screenshots of the Pitbull Information Page on varying devices.

I used google dev tools to emulate different device screens to show responsive design of the website. This responsive design was achieved through the use of media queries and using relative measurement units for the widith and height of elements on the page (vw and vh).  Please see the pictures below for evidence of responsive design.

Laptop (Screen Size: 1440 x 1440px)

![Laptop 1440x1440 display of website](assets/readmepics/Laptop-1440x1440.png)

iPhone 12 Pro (Screen Size: 390 x 844px)

![iPhone 12 Pro displaying website](assets/readmepics/iPhone12Pro-390x844.png)

iPhone 12 Pro Landscape (Screen Size 844 x 390px)

![iPhone 12 Pro displaying website in landscape](assets/readmepics/iPhone12Pro-Landscape.png)

Microsoft Surface Pro 7 (Screen Size 912 x 1368 px)

![Microsoft Surface Pro 7 displaying website](assets/readmepics/SurfacePro7-912x1368.png)

## Features

### Nav bar 

There is a navigation bar at the top of everywebpage that links to each different page, namely the homepage, thee gallery and the quiz page.

### Footer

The footer contains social media icons (sourced from [https://Iconsdb.com]) which link to twitter, instagram and the wikipedia page for American Pitbull Terriers. All links open in new tabs and have aria-labels. All non text elements on the website contain either aria-labels or alt attributes for accessibility. The footer is a sticky footer. This was done by setting a fixed position using CSS and fixing it to the bottom of the page.

### Homepage

On the homepage, there is a picture of a white ABPT accompanied by some text explaining the purpose of the website, as well as a section detailing some characteristics about the dog breed. 

Underneath the breed characteristics, I used an iframe element to link to [https://lillytheheropitbull.com/pit-bull-resources/history-of-the-pitbull/] as this offered great insight into the history of the breed. I set the width of the iframe to 100vw and height to 400px for responsive design. 

Underneath the iframe element, which is in the breed history section, there is a breed misconceptions section. This lists breed stereotypes as well as the opposing facts abput the breeds under the title "In reality."

Image of Homepage:

![Image of homepage of website](assets/readmepics/Laptop-1440x1440.png)

### Gallery

In the gallery, I divided images and videos into their own sections. The images were sourced from [https://unsplash.com/s/photos/dog-pitbull],[https://www.istockphoto.com/search/2/image?phrase=pitbull] or my personal gallery. The videos are both from my personal gallery. For the videos, I inluded video controls and muted them so they would not play automatically upon loading the page.

Images of Gallery Page:

![Image of images section of gallery](assets/readmepics/gallerypics.png)
![Image of video section of gallery](assets/readmepics/galleryvids.png)

### Quiz

The quiz page was made to allow users to test their knowledge about the breeds. Initially, I wanted to create an interactive quiz using a form element that would return a response to users' answers but realised this was not possible without the use of javacript. Equipped with only HTML and CSS, I decided to create a static quiz which had a quiz section accompanied by an answers section, where users could check their answers to the quiz. 

The quiz's questions were sourced from [https://www.mspca.org/wp-content/uploads/2015/09/pitbull_fact_fiction.pdf]

Image of Quiz Page:

![Image of quiz page](assets/readmepics/quizandans.png)

## Bugs

No bugs were found.

## Testing

As mentioned, I used Google developer tools to emulate different screen sizes to check for responsiveness of the website.
I also used replit to continuously run my code during development to test the layout that my CSS code was conveying to the browser.

## Validation

I used the W3C HTML validator to test all the HTML code and the Jigsaw validator to test all CSS code. 
There were no errors. 

## Deployment

I deployed the website using github pages.

## Media

As mentioned previously, some pictures of pit bulls on the gallery page were sourced from 2 different websites:

- https://unsplash.com/s/photos/dog-pitbull

- https://www.istockphoto.com/search/2/image?phrase=pitbull

Icons for the footer were sourced from : https://Iconsdb.com

I used the website imageresizer.com to resize images.
I used clideo.com to resize videos. 
