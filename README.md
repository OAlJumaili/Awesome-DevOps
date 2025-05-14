# Awesome-DevOps

This is a repository where I document all the useful and cool DevOps-oriented tools and resources that I come across and utilize in my work. This repo works as part roadmap, part software discovery resource.  

I'll be updating this repository as I come across more tools and expand my repertoire of knowledge.


# First off, what are the conceptual goals of DevOps?

- #### Simply put, as a DevOps engineer, your aim is to ease the lives of everyone at the organization you work in/for.

- #### You do so by automating parts of the development, quality assurance, and production deployment processes, as well as implementing software and technologies that offer quality-of-life improvements to the members of your organization.

**Now, let's get into the basic knowledge you'll need to do so.**



# 🛠️ Linux

- To start off, if you spend any amount of time in DevOps circles, you'll quickly hear the same sentiment over and over: the first step in DevOps is Linux, followed by scripting, and that couldn't be any closer to the truth.

- No matter how well you think you know Docker or Terraform or any other buzzword-ish software, if you want to succeed in the DevOps field, Linux and scripting (Bash, Python, etc.) are going to be the base of your knowledge pyramid, so let's get started:

### First things first: Download & install a distro.

People will get dogmatic over which distro is supreme, but here's my two cents:

- **Ubuntu**: A great first distro, beginner friendly. My personal recommendation for first timers, but not a very optimized distro for production-level servers.

- **Alpine**: *The* distro for deploying production apps, a very lightweight OS with a small surface of attack. Most Docker images are built on some variation of an Alpine base image, and for good reasons. The only scenario that I would avoid Alpine is for installing and running Docker itself, as it can run into some issues with RC/process limits.

- **ZenOS**: My go-to distro for personal use when I want a Linux distro for personal use.

There are countless distros based on countless kernels, be it Arch, Fedora, GNOME etc. These are simply my personal suggestions.

### Getting started:

I have to shout out LearnLinuxTV and his incredible Linux guides. If you don't feel like reading my guides, I urge you to check him out, this isn't the last time I'll mention him.

To get started on your journey through Linux, take a look at my personal resources for a quick tour through the commands you'll be using 90% of the time:

- #### Basic navigation and file manipulation: Learn how to navigate folders, move, copy and edit them, as well as package managers and other basic facets of Linux.

- #### Networking: Learn the basics of networking as well as commands to test pings, ports and other functions, as well as managing your local firewall.

- #### User management: Learn to create and edit users, as well as managing permissions.

- #### Intermediate tools: Learn some more tools that can be handy when you need them.

- #### Advanced concepts: Learn some advanced (if disparate) concepts, such as environment variables, services etc.

---

# 👷 Proxmox

- Proxmox is, in my opinion, the final frontier for Linux, and something that is not just worth learning, but something that will rocket your Linux (and arguably, general IT) knowledge into the atmosphere, for one simple reason: it is the ultimate sandbox, and we'll get into that in the guides.

Here I have to mention LearnLinuxTV once again and his Proxmox guides, please check them out if you don't feel like looking through my written guides.

### First, if you are able, get an old PC or laptop and install Proxmox.

#### Here are my guides for Proxmox:

- #### Proxmox basics: Learn the basics of virtualization and containerization, and set up your first CTs and VMs.

- #### Proxmox networking: Learn about networking in your local Proxmox machine, and set up VLANs for your containers and VMs.

- #### Clusters: Learn about Proxmox clusters and quorum.

- #### Advanced concepts: Learn about some advanced concepts such as GPU passthrough, mount point binding and user mapping.

---

# 📝 Scripting

- The reason I mentioned Linux and Proxmox first is that your Bash scripts are only as good as your Linux knowledge, and Proxmox provides the sandbox you need to test those scripts in a safe, isolated environment.

- Here I will direct you to some Bash scripting guides, where you can continue polishing your scripting skills.

- Honorable mention to Python, as some people use it as a scripting language, but we'll talk about Python in the next section.

---

# 💾 Programming

- This may be a point of pain for some, but half of being a good DevOps engineer is being a good developer, which means you can't escape the requirement of learning some programming languages. So here are my personal recommendations:

- #### Python: The #1 most used language in the world, and arguably the most flexible language as well. It has almost reached the point of being downright mandatory in the IT field.

- #### Go: A very fast language, and one that is in high demand in 2025. Highly recommended.

- #### Rust: Much like Go, Rust is also a blazing fast language that is in high demand. I recommend learning both, but learning one can be okay too.

**The previous sections form the basis of DevOps. Now we delve into the various facets of DevOps, the different aspects of work you can automate, and the ways you can ease the lives of you and your co-workers, along with some cool software that will help you along the way.**

---

# Source Control

- We'll dedicate the next few sections to the "Dev" part of DevOps, where we'll go through what you can implement to streamline the development and QA testing cycle, and for that we need to discuss a fundamental concept: source control.

- Feel free to check out my source control guide to discuss the fundamental concepts, branch protection, and the feature-based branch mentality.
