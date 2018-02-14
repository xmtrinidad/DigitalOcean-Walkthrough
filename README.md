# DigitalOcean-Walkthrough

A tutorial for turning a local PHP/MySQL application to a live site on DigitalOcean 

**Get Started Here**:  [Uploading a PHP Website](https://github.com/xmtrinidad/DigitalOcean-Walkthrough/blob/master/uploadphpsite.md)

---

## About this repo and who it's for

The main target for this repo is people looking to turn their local PHP website into a live site, with a domain name, that anybody on the Internet can view.  As I learn new stacks and technologies, I will update (and better organize) this repo.

While there are several free alternatives available for hosting static websites (such as GitHub pages), there are not many options available for hosting full-stack websites.  There are some shared hosting options, but based on the research I did, DigitalOcean was the option that came up the most.

The entire concept of a Virtual Private Server was daunting to me.  Even with the number of resources available, I still ran into problems.  It took me some time picking at various resources to finally get the functionality I was looking for, which was to take my local PHP application and deploy it live.

My intent for wanting to deploy my site wasn't to sell a product, but instead to sell myself.  I wanted a way to prove to potential employers that I am learning PHP and that I can deploy an application using the LAMP stack.  If you're like me and want to show others what you can do, hopefully the guides in this repo will help you.

## About Security

As of 2/14, I have updated this repo so that any static site or PHP site can be uploaded, but there are still many things I haven't covered.  One of them being, how to use HTTPs with DigitalOcean for better site security.  As I get more experience implementing more security measures, I will update this repo to demonstrate how to implement it for your own site.

This repo does not cover best practices for securing your PHP code.  Before deploying your site, you should ensure that database queries are properly prepared and any insertions made are properly escaped. 