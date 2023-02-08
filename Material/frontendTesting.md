**Unit Testing**

**Functional Testing (e2e Testing)**<br>
Protractor: <br>
Used to write e2e tests using Protractor
Cypress: <br>

**Visual Testing** <br>
Visual testing evaluates the visible output of an application and compares that output against the results expected by design. 
* We used the testing tool called applitools for visual testing.
* On every run, it takes the screenshots of the particular elements or entire page. 
* On initial run, it saves all the images as baseline image.
* On the every next run, it validates against the baseline image. If there is any difference even small alignment or color or icon style difference will be caught and shown as failed.
* If that is the new change going forward then we can make the new image as baseline image and save it.
* Again on next run, it validates against new baseline image. <br>

**Accessibility Testing**
