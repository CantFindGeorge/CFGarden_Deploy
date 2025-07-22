---
{"dg-publish":true,"permalink":"/projects/obsidian-digital-garden/","tags":["Projects"],"created":"2025-07-16","updated":"2025-07-17T13:13:38.629-04:00"}
---

# About This Project
I really wanted to make a public place where I could detail all the useful shit I know. So many times people ask me "Hey do you know XYZ" and I do but I just cant recall where the hell I saw it or what the info was. Hence the idea to make a [[Second Brain\|Second Brain]] of information I can review or refer someone else to.

The overall setup process was really smooth and super easy. But there was a ton of research and failed attempts before I landed on using the final tech stack.

> [!summary] Tech Stack
> - [Obsdian](https://obsidian.md/)
> 	- [Digital Garden Plugin](https://dg-docs.ole.dev/)
> - [Github](https://github.com/)
> - [[Projects/Obsidian Digital Garden#Netlify\|#Netlify]]
> - [[Projects/Obsidian Digital Garden#Vault Repository\|#Vault Repository]]

---
# How-To
The Obsidian Digital Garden site has a [comprehensive install guide](https://dg-docs.ole.dev/getting-started/01-getting-started/). I followed along with this for pretty much the entire thing with two minor deviations.
## Vault Repository
**Before doing anything** I created a [[Tech/Vault Repository\|Vault Repository]] for this project. 
## Netlify
The [Hobby Plan](https://vercel.com/docs/plans/hobby) of Vercel (free tier) was dog water so I went with [Netlify](https://www.netlify.com/) as listed in the [Hosting Alternatives](https://dg-docs.ole.dev/advanced/hosting-alternatives/) section of the documentation. 

> [!warning]
>Because we also had made a [[Projects/Obsidian Digital Garden#Vault Repository\|#Vault Repository]] i decided to name the repo created during the Netlify setup the same name and add `-deploy` as a suffix. 
>
> - `mydigitalgarden` for the [[Projects/Obsidian Digital Garden#Vault Repository\|#Vault Repository]] 
> - `mydigitalgarden-deploy` for the Netlify repo.

---
# Troubleshooting

## Permissions
I've only had issues when I changed my repository name which wasn't to hard to fix. But if you followed the callout in the [[Projects/Obsidian Digital Garden#Netlify\|#Netlify]] section then you shouldn't need to change this. If you do update the following:
- Netlify
	- Project Conguartion/Build & deploy/Repository/Manage Respository
- Github
	- I used the [fine grained access token](https://dg-docs.ole.dev/advanced/fine-grained-access-token/) so you'll also need to regenerate [[Resources/The Last List\|The Last List]]
