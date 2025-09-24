# 🌟 My Personal Blog Website Adventure

## 🚀 Getting Started with Hugo
So, I decided to create my own personal blog website and went with **Hugo**. Honestly, at first, it felt a bit like stepping into a new world 🧭 — there were themes, commands, and folders everywhere. But soon, I got into the groove. I picked the **Blowfish theme**, which turned out to be super friendly for beginners. The website is live at [blog.singhops.net](https://blog.singhops.net)!

## 🛠 Setting Up My Hugo Blog
The journey began with picking a theme from the Hugo website. Each theme has a GitHub page, and with a little Git magic, I added Blowfish as a **submodule in the `themes` folder**. Running `hugo server` on my local machine felt like magic 🪄 — instantly, my blog was coming to life!

Blowfish also gave tons of documentation 📚. I went through it bit by bit, learning how to personalize my site. The example site files were a lifesaver, giving me ideas and code snippets I could copy directly. With a little help from AI friends like **Claude** and **Perplexity** 🤖, I brainstormed and tweaked the code until it felt just right.

I added headers, blog posts, and even uploaded cheatsheets that I personally use. Slowly but surely, I got the hang of Hugo and my site started looking like *me* 😎.

## ☁️ Hosting on AWS (Almost Free!)
Next step: getting my blog online. I tested everything locally using `hugo server -D`, and once I was happy, I built the site and uploaded all files from the `public` folder to **Amazon S3**. 

Then came **CloudFront** and my custom domain through **Route 53**. And voilà — the blog was live in under 15 minutes 🌐✨! Using just **S3, CloudFront, and Route 53**, my hosting costs are almost nothing, which is amazing for a personal project.

This whole process taught me a lot about **Hugo**, **AWS services**, and **GitHub workflows**. It was a fun mix of tech exploration and creative experimentation 🎨.

## 🌐 Building My Main Page
For my main website, I went full AI mode! I used an **AI website builder**, gave it a few prompts, made some tweaks, and boom — my main site was live within a few hours ⚡. It was even easier than Hugo!

Then, I built the app with **React** and uploaded the files from the `dist` folder to another **S3 bucket**, set up a separate **CloudFront distribution**, and linked it with my root domain **singhops.net**. 

The cool part? My main site and blog are separate but fully interlinked. You can jump between them smoothly, and each retains its own personality 🌈.

## 🎉 Lessons Learned & Fun Moments
- Hugo setup is easier than it looks, especially with good themes and docs.
- AI tools like Claude and Perplexity are great for brainstorming and coding support.
- AWS services like **S3, CloudFront, and Route 53** make hosting fast, reliable, and cost-effective.
- Playing with code, themes, and deployment workflows is actually fun (who knew?) 😁
- React + Hugo integration for multiple sites is totally doable and rewarding.

This project wasn’t just about making a website; it was a journey of learning, experimenting, and having fun along the way. And seeing my work live online? Pure satisfaction 🏆.

