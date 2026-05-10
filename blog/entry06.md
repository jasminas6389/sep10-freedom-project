# Entry 6
##### 5/10/26

### Content
#### How I made my MVP
For my Freedom Project, I chose the topic Medical Practice because I want to work in healthcare in the future. After I researched existing medical apps like Virtual Practice Healthcare, Jotform Health, and the NHS App, I wanted to make a model of a Teleportation Device that could improve access to healthcare worldwide. I made my MVP using bootstrap and A-frame which is what I used for my tool. The Teleportation Device could save millions of lives because it can transport a patient anywhere in a matter of seconds. This could be life-saving if someone needs urgent care or specialist treatment far away.

#### Here is the preview of my MVP
<img width="800" height="500" alt="Screenshot 2026-05-10 11 47 30 AM" src="https://github.com/user-attachments/assets/e3823368-e90f-43ff-91ea-737d787defde" />

<img width="800" height="500" alt="Screenshot 2026-05-10 11 47 38 AM" src="https://github.com/user-attachments/assets/2ee601fc-bfc0-4519-aaa3-726c6437eabd" />

<img width="800" height="500" alt="Screenshot 2026-05-10 11 47 43 AM" src="https://github.com/user-attachments/assets/cf3d7af1-7637-4631-ba7d-e45bfa2cc1e2" />
<img width="800" height="500" alt="Screenshot 2026-05-10 11 47 46 AM" src="https://github.com/user-attachments/assets/24479549-4c97-48df-aa31-67dd6aa76a0d" />

#### Challenges
One challenge I had was making sure that the text sizes and words look good on all screen sizes. For example a heading that looks good on a big desktop screen can be very big on a mobile phone or tablet, and it won't look as good as its supposed to. So I used a media query which makes the text be a specific size on a specifc screen size. 
``` CSS
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
I used this media query for my Medical Practice title. Originally I didn't put a media query for it but after I finished my MVP I decided why not search up my website on my phone and see it from other perspective. The first thing I noticed was how big the title was, so I went into my IDE and added the media query to make the text sizes smaller on a smaller screen size. 

### Sources

### Engineering Design Process

### Skills
Some skills I've gotten better in is organizing all of my things. Especially all the information I've used in my project, and putting everything in its specific place. 


[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
