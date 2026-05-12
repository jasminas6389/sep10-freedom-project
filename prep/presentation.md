# Presentation Plan

## Hook
* Did you know that over 116 million people worldwide used telemedicine apps in recent years, and that number keeps growing every year? Healthcare is changing because of new technology. Today people can talk to doctors through apps, schedule appointments online, and receive treatment without leaving their homes. 

## Product
* I will summarize the context into a few sentences so they know what my project is about.
* To show my website, I will show the existing software and hardware technology, and i will say how for the software technology you can click the link to learn more information about the website.
* then I will talk a little about my A-frame. and what inspired me to make it. 

## Process
* Explain how I researched medical technology and apps like Epic Systems and Zocdoc
* A challenge I had was making the text look good on every screen size. Some sections didn't look good on smaller screens like a phone or Ipad. So I used media queries and it was good because you can make a unique code only meant for a unique div, you can pick the text size and how much of the screen you want it to take up.
```css
  @media (max-width: 768px) {
    #part-a h3,
    #part-b h3 {
        font-size: 28px;
    }
 }
 @media (max-width: 480px) {
    #part-a h3,
    #part-b h3 {
        font-size: 24px;
    }
}
  ```
```css

@media (max-width: 768px) {
    #part-a h4,
    #part-b h4 {
        font-size: 18px;
    }
}

@media (max-width: 480px) {
    #part-a h4,
    #part-b h4 {
        font-size: 16px;
    }
}
```
* Heading 3 and heading 4 both have specific unique font sizes and as the size of the screen decreases so will the text size. Originally I didn't have a media query for my h3 and h4 texts but then when I opened my website on my phone, I noticed how the text was very big. 
* The same for my medical practice title I didn't have a media query and it was insanely big and took up the whole screen on my phone. SO I used a media query and made it smaller.
``` css

@media (max-width: 768px) {
    .main-title {
        font-size: 40px;
    }
}

@media (max-width: 480px) {
    .main-title {
        font-size: 30px;
    }
}
```
* Maybe show my AI generated technology device.
* Then talk about how transportation is very important especially in medical field, and the importance of time.

## Conclusion
* Technology is improving medical practice by helping doctors diagnose patients faster, organize medical records,and provide online care through telehealth apps and medical devices. Possibly in the future we might have inventions like robotic surgery, 3D printed organs and maybe even the teleportation device to make healthcare faster and safer.
* Technology and medicine together can save lives and make healthcare more accessible for everyone.

<!-- EXAMPLE

## Hook
* Verbal riddle of GGD

## Product
* GIF/Demo of example/non-example

## Process
* Flowchart of plan
  * MVP: noun -> door -> yes/no
  * Beyond MVP: noun -> word relation API -> noun API -> yes/no, with counterexample
* Code snippets of:
  * MVP
  * Both APIs
  * Challenge with API keys

## Conclusion
* [URL to project]
* Takeaways
  * Less = more: the heart of the riddle was one line of code; it obviously took more to make the entire thing work, but one complicated line of regular expressions was essentially the solution to the riddle
  * Expect the unexpected: it’s important to budget time for things you don’t account for; for example, I didn’t consider the fact that I would need another entire API to detect nouns
  * Determination is key: ironically enough, I had to make my API keys private. At first, it didn’t seem like it was possible, which meant I couldn’t publish my app. But after all of that hard work, I was determined to find a solution, and I found it in config variables.
* "Presentation can’t, but a speech can"


-->
