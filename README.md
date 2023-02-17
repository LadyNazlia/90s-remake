# 90s-remake
Revamping a website design that I saw at work one day. Includes a slightly modified OG design and the new design.

# Intro

While working at an in-house IT Help Desk, I encountered countless apps and websites that are used by the company and clients of the company on a daily basis.
Some of those programs and websites were acceptable, but I eventually realized that there was a trend with many of them. 
More often times than not, even apps that were built in-house, simplicity was often placed ahead of user experience.

While there is nothing wrong with using a website that looks like it was built in the mid-90s if you're into that kind of thing, it really doesn't take much effort to make something not only look a little prettier, but also function a little better.

This project is my attempt at taking one of those website that was programmed in a single HTML (as far as I can tell), and making it look more up to date to provide a slightly better user experience.

# Background

I spent 2 hours on the computer with my supervisor working over my shoulder trying to help someone gain access to this website. The website itself typically uses Citrix Receiver version 4.7 to log in.

Now, to understand why that is already starting off bad, you have to understand this:

- They only recently updated for 4.7 and were originally using 4.3, but because it crashed due to tech we use at the company, they were forced to upgrade.
- EOL for version 4.9 was EXTENDED to September 2020 (meaning is actually was set to run out before then, also meaning that EOL for 2 versions higher than what they use was going on 3 years ago!)
- In fact, Citrix has done away with Citrix Receiver and it has been replaced with Citrix Workspace, which was released in late 2022.

Thing that make this really bad:

- No tech support from Citrix when the program won't work
- No security updates because it is well beyond the EOL and EOS, meaning there is a HUGE risk for security issues
- If we have one person working with multiple clients who all use Citrix, because this one client refused to upgrade, we have to use multiple versions of Citrix and select the correct on based on which client we are working with.

Not to mention that Citrix Receiver 4.7 is super slower and unreliable. 

# There Solution?

BUT, this company has a solution. If for some reason Citrix doesn't work, the website defaults to using Java to log in... something that has to be installed and tweaked to work as a "backup plan" if the first one fails. i.e. more work on the IT department because another company refuses to upgrade.

# Takeway

If you work as a developer, tech support, or call the shots on the type of tech/programs your company uses, keep things up to date as much as possible.
It will save a lot of people a lot of hassle and heartache on the job if you do. 