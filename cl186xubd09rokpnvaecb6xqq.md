## My experience as a part of the initial product launch team at ZuPay.

I have always been a big fan of having a lifetime checklist of things that you want to do at least once in your lifetime. A shorter version of it is what I call my engineering life checklist which has a lot of things and one of them was working at a funded startup early in my career. 

Hey, I am Aman. I am right now in my 2nd year of engineering at MAIT. I am currently working at ZuPay as a Flutter developer intern. This is my story of how I got into ZuPay and how I contributed to the initial release of ZuPay.

### Getting into ZuPay

It’s the month of October and I’m done with taking a rest after my previous freelance work, now I’m looking for an internship at a good-funded startup. I have started applying at startups and It’s been 3 days and I have gotten some response when I saw a post from [Anubhav](https://www.linkedin.com/in/anubhavmishra-lm/) that they are hiring flutter interns at ZuPay. I instantly cold dm-ed him telling my experience and how can I be a good fit for this role. He gave me the contact of [Arpit](https://www.linkedin.com/in/arpitkotecha/) and told me to email him. I got on a call with Arpit the next day, He asked me about my work experience, projects I have done, currently what I am doing, and other details. At last, he asked me to submit a flutter project for him to review, But I submitted 2 because I was unsure If a 6 months back project would properly portray my current skills.

He reviewed my project, and I got selected.

### About ZuPay

**ZuPay** is an investing cum learning app for teenagers. It’s a platform where a teenager can do all sorts of things from learning about investment to actually investing in the market and buying real stocks.


![Untitled.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647930907918/AG8MZPKR5.png)

**First Task**

I was given access to the codebase of ZuPay and was added to height (A task management solution we use at ZuPay) and Figma. I cloned the project and started going through it, my first experience going through it was not the best. I got on a call with Arpit and he assigned me the first task to structure the project. I sat with the project and made a list of things we can do to improve the project.

There were a lot of things that could have been fixed, I started with enabling lints to project and suggested teammates follow dart guidelines while coding.

### Engineering insights at ZuPay

- **Our Goal**
    
    Since the main product of ZuPay is the mobile app so the goal of our team was to build it in a scalable manner while maintaining the best practices of coding. Since I was given the task to restructure the project so Arpit asked me to come up with the architecture of our app.
    
- **Architecting the initial app of ZuPay**
    
    The main goal behind coming up with this architecture was to make codebase scalable since we are a product based company and our mobile app is user facing product which will have hundreds of feature in future. So the codebase should be simple enough that addition of new features were easy and at the same time we should be able separate UI and logic clearly. We are following a folder based approach to structure the app and using `riverpod` to manage states, `get_it` for dependency injection and `dio` for making network calls.
    
- **Full-timers joined us.**
    
    After 2 months of work, we were able to add authentication in our app, some features of ZuAcademy, and some features of stock trading. Our full-time engineers: [Aman Bafna](https://www.linkedin.com/in/aman-bafna-7034b110b/) and [Divyam Joshi](https://www.linkedin.com/in/divyam-joshi-ba0056127/) joined us this month and they suggested some flaws in our folder structure which they very soon fixed.
    
    The month of January was the month when the whole team worked really hard. We did around 400+ commits added a lot of features, tested and retested the app to make sure the initial release was successful. In this month I learned a lot from the full-time engineers, especially the way Aman bhaiya patiently dealt with every single bug. I remember the day when we had a critical bug in the invitation flow when we sat till 2 am but finally we managed to solve it and how patiently he dealt with each line of code.
    
    
### Most Interesting tasks

 - **Implement an interceptor to put tokens in the headers and refresh it if it’s expired:** so this is among the first task I was given, I did a good amount of research on how to make our custom interceptor. I added a field in our token model which calculated when will the token expire and in the interceptor I read the tokens from shared-prefs and checked if it’s expired. If it was expired then I was calling the refresh token endpoint with relevant data.

 - **Migrating to get_it for dependency injection:** We were using riverpod as a dependency injection tool in our app but very soon we realized that it’s not scalable as we couldn’t access a dependency without `ref` and ref is only available in the `view layer`. So that’s when I proposed to use `get_it` just for that. `git_it` is a simple DI tool that makes it super easy to manage dependencies. It was a big migration for us, but an important one. I worked on that and migrated the whole app to use `get_it` within a day or two. This proved to be one of the best decisions we took till now.


### Major learnings at ZuPay

Whenever you work at a startup, a lot of responsibilities come up and you learn to do a lot of things at the same time. 

1. **Technology:** I got better at Flutter. Learn't riverpod, managing APIs, and a lot of other things.
2. **Fail fast:** While working at a startup it’s very critical that we implement things faster & fail fast while slowly winning the game in long term.
3. **Time management:** Working here gave me a fairly good taste of how real-life jobs are. I was managing work, college, leading a team at CrossKnot, and managing some personal issues at the same time and it taught me a lot of things.

