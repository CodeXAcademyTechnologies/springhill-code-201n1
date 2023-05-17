# Problem Domain

The Seattle Dog Rescue has tons of dogs who need good homes. One of the best ways to reach prospective adoptive homes is to have profiles for each dog available on a website. There are hundreds of dogs, though, and only a few volunteers; it's too time-consuming to hand-code each dog's profile on their website. They need a better way.

## what would you like to have as features?

### required features

- The volunteer would go to the website, type in the dog's name, age
- create a narrative of who this dog is - personality, likes, etc.
- breed
- good with kids/dogs/other cats
- picture(s) - one at minimum, more is nice

### nice to have

- what their story is
- notes from the foster human
- health history
- videos
- animated gif
- social media links - linkedIn profile
- blink tag

 ## user scenario

 Jose is a volunteer for Seattle Dog Rescue. He has some level of comfort with a browser and copying/pasting/saving/uploading/etc. He navigates to the enter a dog form and enters the above info in a form box. When he clicks the "submit" button, the dog's profile is displayed on the page.

### out of scope

   removing dogs from the site
   videos, health history, foster notes, social media, blink tag

## user stories

1. As a volunteer for Seattle Dog Rescue, I want to have dog bios show up on the page without having to write html myself, so that my workload is lessened. I will know this is done when I can hard-code a dog bio in JavaScript and that dog's bio is rendered on the page.

1. As a volunteer, I want to enter the dog's data into a form, and have that dog's specific profile automatically show up on the page, so that my workload is lessened. I will know this is done when I can enter dog data into a form, and that dog's bio shows up on the page

1. As the web services manager for Seattle dog Rescue, I want the code for the bio generation to be written in plain-vanilla JavaScript, so that it can be easily maintained. I will know this is done when I can look at a JavaScript file for the site, and see it written in ES5, with no use of libraries or frameworks.
