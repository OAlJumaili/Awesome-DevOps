# Awesome-DevOps
This is a Repository Where I Document All The Useful and Cool DevOps Oriented Tools and Resources That I Came Across and Utilize in my Work. This Repo Works As Part RoadMap, Part Software Discorvery Resource.  

I'll Be Updating This Repository As I Come Across More Tools And Expand my Repertoire of Knowledge.

# First Off, What is The Are The Conceptual Goals Of DevOps?

- #### Simply Put, As DevOps Engineer, Your Aim is To Ease The Lives Of Everyone At The Organization You Work In / For.

- #### You Do So By Automating Parts Of The Development, Quality Assurance And Production Deployment Processes, As Well As Implementing Software And Technologies That Offer Quality of Life Improvements to The Members of Your Organization.

**Now, Let's Get Into The Basic Knowledge You'll Need To Do So.**

# 🛠️ Linux

- To Start off, If You Spend Any Amount of Time in DevOps Circles, You'll Quickly Hear The Same Sentiment Over and Over: The First Step In DevOps is Linux, Followed By Scripting, And That Couldn't be Any Closer To The Truth.

- No Matter How Well You think you know Docker or Terraform or Any Other Buzzword-ish Software, If You Want to Succeed in the DevOps Field, Linux And Scripting (Bash, Python, etc.) Are Gonna The Base Of your Knowledge Pyramid, So Let's Get Started:

### First Things First: Download & Install A Distro.
people Will Get Dogmatic Over Which Distro Is Supreme, But Here's My Two Cents:

- **Ubuntu**: A Great First Distro, Beginner Friendly. My Personal Reccommendation For First Timers, But Not a Very Optimized Distro For Production Level Servers.

- **Alpine**: THE Distro For Deploying Production Apps, A Very Lightweight OS With A Small Surface of Attack. Most Docker Images Are Built on Some Variation of an Alpine Base Image, and for Good Reasons. The Only Scenario That I Would Avoid Alpine Is For Installing And Running Docker Itself, As It Can Run Into Some Issues With RC / Process Limits.

- **ZenOS**: My Go-To Distro For Personal Use When I Want a Linux Distro For Personal Use.

There Are Countless Distros Based On Countless Kernels, Be it Arch, Fedorea, Gnome etc. These are simply My Personal Suggestions.

### Getting Started:

I Have to Shout out LearnLinuxTV and His Incredible Linux Guides. If you Don't Feel like Reading My Guides, I Urge You To Check Him Out, This Isn't The Last Time I'll Mention Him.

To Get Started On Your Journey Through Linux, Take a look at my Personal Resources For A Quick Tour Through The Commands You'll Be Using 90% Of The Time:

- #### Basic Navigation and File Manipulation: Learn How to Navigate Folders, Move, Copy and Edit Them, As Well As Package Managers And Other Basic Facets of Linux.

- #### Networking: Learn The Basics of Networking As Well As Commands To Test Pings, Ports and Other Functionds, As Well As managing Your Local Firewall.

- #### User Management: Learn To Create and Edit Users, as well as Managing Permissions.

- #### Intermediate Tools: Learn Some More Tools That Can Be Handy When You need Them.

- #### Advanced Concepts: Learn Some Advanced (If Disparate) Conecepts, Such As Environment Variables, Services etc.

# 👷 Proxmox

- Proxmox Is, In My Opinion, The Final Frontier For Linux, And Something That Is Not Just Worth Learning, But Something That Will Rocket Your Linux (And Arguably, General IT) Knowledge Into The Atmosphere, For One Simple Reason: It Is The Ultimate Sandbox, And We'll Get Into That In The Guides.

Here I Have To Mention LearnLinuxTV Once Again and His Proxmox Guides, Please Check Them Out If You Don't Feel Like Looking Through My Written Guides.

### First, If you Are Able, Get an old PC or Laptop and Install Proxmox.

#### Here Are My Guides For Proxmox:

- #### Proxmox Basics: Learn The Basics Of Virtualization And Containerization, And Setup Your First CTs and VMs.

- #### Proxmox Networking: Learn About Networking In Your Local Proxmox Machine, And Setup VLANs For Your Containers and VMs.

- #### Clusters: Learn About Proxmox Clusters And Quorum.

- #### Advanced Concepts: Learn About Some Advanced Concepts Such As GPU Passthrough, Mount Point Binding And User Mapping.

# 📝 Scripting

- The Reason I Mentioned Linux And Proxmox First, Is That Your Bash Scripts Are Only As Good As Your Linux Knowledge, And Proxmox Provides The Sandbox You Need To Test Those Scripts In A Safe, Isolated Environment.

- Here I Will Direct You To Some Bash Scripting Guides, Where you can Continue Polishing your Scripting Skills.

- Honorable Mention To Python As Some Poeple Use it As a Scripting Language, But We'll Talk About Python In The Next Section.

# 👾 Programming

- This My Be A point of Pain For Some, But Half of being A Good DevOps Engineer Is Being a Good Developer, Which means you Can't Escape The Requirement Of Learning Some Programming Languages, So Here Are My Personal Recommendations:

- #### Python: The #1 Most Used Language In The World, And Arguably The Most Flexible Language as well. It Has Almost Reached the Point of Being Downright Mandatory in The IT Field.

- #### Go: A Very Fast Language, And One That is In High Demand in 2025. Highly Recommended.

- #### Rust: Much Like Go, Rust Is Also A Blazing Fast Language That Is In High Demand. I Recommend Learning Both, But Learning One Can be Okay Too.

**The Previous Sections Form The Basis Of DevOps, Now We Delve Into The Various Facets Of DevOps, The Different Aspects of Work You can Automate and The Ways you can Ease The Lives of You and Your Co-Wrokers, And Some Cool Software That Will Help You Along The Way.**