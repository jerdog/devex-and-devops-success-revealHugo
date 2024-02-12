+++
title = "Developer Experience is Central to DevOps Success"
outputs = ["Reveal"]

[reveal_hugo]
width = "80%"

+++
{{< slide background-image="/images/slides/1-devex-central-devops-success.jpg" background-opacity="0.5" >}}

## Developer Experience...
### Central to DevOps Success

---

>### "DevEx - that's just the frontend user experience, right?"


{{% note %}}
DevEx goes beyond just the frontend or user interface and extends to every aspect of a developer's interaction with your systems, including backend processes, APIs, deployment tools, and more. From the simplicity of the setup process to the complexity of solving production issues, DevEx directly impacts developer productivity, satisfaction, and ultimately, the quality of the products they build.  
{{% /note %}}

---

### DevEx is _more_ than your parent's software development lifecycle

{{% note %}}
DevEx encompasses the entire development lifecycle, as a direct result of the choice of development tools, technologies, and platforms. The ease of use, reliability, how accessible and understandable documentation, how efficient the build processes are, the effectiveness of testing frameworks, and the smoothness of deployment procedures all have an impact on the overall dev experience.
{{% /note %}}

---

{{< slide id="bio" transition="zoom" transition-speed="fast" >}}
<section>
    <div class="multiCol">
        <div class="col">
            <h4 style="color: rgb(111, 168, 220);">Jeremy Meiss</h4>
            <p style="font-size: .75em;">Co-Founder</p>
            <p style="font-size: .75em; font-style: italic;">DevEx Startup</p>
        </div>
        <div class="col"><img src="/images/profile-pic.jpg" width="60%"></div>
    </div>
</section>

{{% note %}}

{{% /note %}}

---

## So what is DevEx?

{{% fragment %}}
DevEx encompasses the journey of developers as they learn and deploy technology. When successful, it focuses on eliminating obstacles that hinder a developer or practitioner from achieving success in their endeavors.
{{% /fragment %}}

{{% note %}}
So we opened with an introduction on the topic of DevEx, but what really is it?
{{% /note %}}

---

### DevEx is about more than the traditional UI/UX focus

![alt text](/images/slides/ui-ux-qa.gif)

{{% note %}}
As mentioned earlier, DevEx goes beyond the traditional focus on front-end or user interface experiences. It encompasses so much more, including every interaction a developer has with systems, tools, and processes. Let's think about a couple examples.
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![USER FRIENDLY by Illiad, vi](/images/slides/httpatomoreillycomsourceoreillyimages2055076.png)
{.r-stretch}
REF: O'Reilly "Learning the vi and Vim Editors"


{{% note %}}
I think a great example is the evolution of Integrated Development Environments (IDEs). Prior to the 1990's, you had mostly text-based editors that were used to write code, like Vi, which evidently is supposed to be called "SIX". Who knew?
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![vim logo](/images/slides/vim-logo.png)  ![emacs logo](/images/slides/emacs-logo.png)  ![nano logo](/images/slides/gnu-nano-logo.png)


{{% note %}}
Vim, and Emacs, and my personal favorite, `nano`.
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![hp softbench manuals](/images/slides/hp-softbench-manuals.jpg)
{.r-stretch}

{{% note %}}
One of the first IDEs with a plug-in concept was Softbench. HP Softbench was one of the first plug-in Integrated Development Environment (IDE) tool based on the UNIX operating system, UNIX tools and the X Window System. 
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![hp softbench ieee article](/images/slides/hp-softbench-ieee-paper.jpg)
{.r-stretch}
REF: https://ieeexplore.ieee.org/document/182074

{{% note %}}
Paper written and submitted to IEEE in 1991 was about how "HP SoftBench-support for distributed working" https://ieeexplore.ieee.org/document/182074 In 1995 Computerwoche commented that the use of an IDE was not well received by developers since it would fence in their creativity. Apple Macintosh's had Macintosh Programmer's Workshop and Turbo Pascal for native IDEs. The early iterations of IDEs were more graphical and had a more modern look and feel. Who remembers the first HTML WYSIWYG editor? WebMagic on January 25, 1995 built by Silicon Graphics. FrontPage (https://softpanorama.org/Office/Frontpage/history.shtml) was soon to follow in October of the same year. Borland Delphi was released in 1995 and is still around (Embarcadero Delphi v12)
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

>#### "...the use of an IDE was not well received by developers since it would fence in their creativity."
REF: Computerwoche, 1995.

{{% note %}}
Paper written and submitted to IEEE in 1991 was about how "HP SoftBench-support for distributed working" https://ieeexplore.ieee.org/document/182074 In 1995 Computerwoche commented that the use of an IDE was not well received by developers since it would fence in their creativity. 
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![apple-MPW](/images/slides/apple-mpw.png)  ![apple-MPW](/images/slides/turbo-pascal-window.png)  

{{% note %}}
Apple Macintosh's had Macintosh Programmer's Workshop and Turbo Pascal for native IDEs. 
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![WebMagic](/images/slides/webmagic-screen.jpg)  


{{% note %}}
The early iterations of IDEs were more graphical and had a more modern look and feel. Who remembers the first HTML WYSIWYG editor? WebMagic on January 25, 1995 built by Silicon Graphics. 
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![Frontpage](/images/slides/frontpage.png)
{.r-stretch}

{{% note %}}
FrontPage (https://softpanorama.org/Office/Frontpage/history.shtml) was soon to follow in October of the same year. 
{{% /note %}}

---

#### The evolution of the IDE
##### Before the 1990s

![Borland Delphi](/images/slides/borland-delphi.png)
{.r-stretch}

{{% note %}}
Borland Delphi was released in 1995 and is still around (Embarcadero Delphi v12)
{{% /note %}}

---

#### The evolution of the IDE
##### Early iterations
###### (Late 1990s to Early 2000s) 

- Macromedia Dreamweaver in late 1997 (what was it called before?)</p>
- Visual Studio in late 1997
- FrontPage 2000 in 1999
- Netbeans in 2000
- Eclipse in 2001 (IBM kickstarted)

{{% note %}}
Macromedia's Dreamweaver first came out in 1997 (after Macromedia acquisition of Backstage in 1996) and was awesome because of all of the scripts and integrations and controls you could add. Microsoft FrontPage 2000 saw the first inclusion of plugins and integrations in early 1999 to make web management easier (FrontPage Server Extensions). NetBeans was released in 2000 for Java, and Eclipse was kickstarted and released in 2001 by IBM.
{{% /note %}}

---

#### The evolution of the IDE
##### Feature & Usability Advancements
###### Mid-2000s to 2010s

- IntelliJ IDEA
- Eclipse
- Visual Studio

{{% note %}}
**Enhanced Functionality:** IDEs like IntelliJ IDEA and later versions of Eclipse and Visual Studio began to offer more sophisticated features like intelligent code completion, refactoring tools, and improved version control integration.
**Language Support and Framework Integration:** There was a noticeable increase in support for multiple programming languages and frameworks, making these IDEs more versatile.
{{% /note %}}

---

#### The evolution of the IDE
##### Lightweight and Cloud-Based
###### 2010s to Now

- Sublime Text, Atom, VSCode (lightweight)
- AWS Cloud9, GitHub Codespaces, Gitpod (cloud-based)

{{% note %}}
**Lightweight IDEs:** Tools like Sublime Text and later Visual Studio Code (VSCode) emerged, focusing on speed, user-friendly interfaces, and extensive plugin ecosystems. They catered to a broader range of developers by being less resource-intensive and more customizable.
**Cloud-Based IDEs:** The introduction of cloud-based IDEs like AWS Cloud9 and GitHub Codespaces revolutionized DevEx by offering fully configured development environments in the cloud, accessible from anywhere, reducing the need for complex local setup.
{{% /note %}}

---

##### IDEs are a result of DevEx
###### Things we never knew we needed...

- Code completion
- Syntax highlighting
- Debugging
- VCS integration (no more FTPing files around)
- Multi-language support
- Framework integration
- Pair programming

{{% note %}}
One aim of the IDE is to reduce the configuration necessary to piece together multiple development utilities. Instead, it provides the same set of capabilities as one cohesive unit. Reducing setup time can increase developer productivity, especially in cases where learning to use the IDE is faster than manually integrating and learning all of the individual tools. Tighter integration of all development tasks has the potential to improve overall productivity beyond just helping with setup tasks. For example, code can be continuously parsed while it is being edited, providing instant feedback when syntax errors are introduced, thus allowing developers to debug code much faster and more easily with an IDE.
{{% /note %}}

---

{{< slide background-image="/images/slides/23-improve-dev-experience.jpg" background-opacity="1" >}}


{{% note %}}
### Improving the Developer Experience
These examples illustrate the significant strides made in improving the developer experience through the evolution of IDEs and the setup of development environments. From basic, manually-configured environments to sophisticated, cloud-based, and automated setups, the journey reflects a relentless pursuit of efficiency, usability, and developer productivity.
{{% /note %}}

---

{{< slide background-image="/images/slides/24-modern-dev-practices.jpg" background-opacity="1" >}}


{{% note %}}
### Modern Development
DevEx strategies have evolved to meet contemporary development challenges and opportunities.
{{% /note %}}

---

#### DevEx as a Key Differentiator


{{% note %}}
In the highly competitive landscape of modern software development, DevEx has emerged as a critical differentiator for attracting and retaining top talent, as well as ensuring high levels of team performance and product quality. A positive DevEx translates into a more engaged and productive development team, capable of delivering innovative features and services at a faster pace. Companies that prioritize DevEx demonstrate a commitment to developer well-being and efficiency, which not only enhances their brand reputation among potential hires but also contributes to higher satisfaction and retention rates among existing staff. Furthermore, by streamlining development processes and fostering a culture of innovation, a strong DevEx strategy directly impacts the bottom line by enabling quicker time-to-market and more reliable products.
{{% /note %}}

---

#### Dev Environment Setup
##### Manual configuration
###### Late 1990s to Early 2000s

![cfengine-earlyLogo](/images/slides/cfengine-earlylogo.png)  
![cfengine-Logo](/images/slides/cfengine-logo.png)

{{% note %}}
Another quick example is the setup of development environments. In the early days, setting up a development environment involved manually configuring each tool, library, and dependency, which was time-consuming and error-prone. Developers often struggled with version conflicts and compatibility issues between different tools and libraries. In the mid- to late-90s systems like CFEngine v1 and CFEngine v2 emerged to automate this process.
{{% /note %}}

---

#### Dev Environment Setup
##### Config Mgmt & Containerization
###### Mid-2000s to 2010s

![Puppet Logo](/images/slides/puppet-logo.png)  ![Chef Logo](/images/slides/chef-logo.png)  ![Saltstack Logo](/images/slides/saltstack-logo-white.png)  
![Ansible Logo](/images/slides/ansible-logo.png)  ![Docker Logo](/images/slides/docker-logo.png)  

{{% note %}}
**Configuration Management Tools:** The advent of tools like Puppet, Chef, Saltstack, and Ansible allowed for automated setup and configuration of development environments, reducing manual effort.
**Containerization:** Docker’s introduction in 2013 marked a significant shift, allowing developers to package applications with all their dependencies into containers, ensuring consistency across environments.
{{% /note %}}

---

#### Dev Environment Setup
##### IaC and DevOps Integration
###### 2010s to Present

![Terraform Logo](/images/slides/terraform-logo.png)  ![AWS CloudFormation Logo](/images/slides/aws-cloudformation-logo.png)  
![Jenkins Logo](/images/slides/jenkins-logo.png)  ![GitHub Actions Logo](/images/slides/github-actions-logo.png)  

{{% note %}}
**Infrastructure as Code (IaC):** Tools like Terraform and AWS CloudFormation enabled developers to define infrastructure through code, making setup reproducible and scalable.
**DevOps and Continuous Integration/Continuous Deployment (CI/CD):** The integration of development environments with CI/CD pipelines and DevOps practices streamlined the development process, allowing for faster and more reliable builds and deployments.
{{% /note %}}

---

### Broader Impact of DevEx

- Deployment Pipelines
- Infrastructure as Code (IaC) Practices
- Developer Efficiencies
- UI/UX for Developers (User-centric Design)

{{% note %}}

{{% /note %}}

---

### A good DevEx is good DevOps

{{% note %}}
A good DevEx facilitates smoother transitions between development and operations, minimizing bottlenecks and enhancing collaboration. With proper feedback loops in place, a positive DevEx ensures these loops are efficient and productive, enabling, or enhancing, DevOps principles to take hold within an organization.
{{% /note %}}


---

## What is DevOps?

the combination of practices and tools designed to increase an organization's ability to deliver applications and services faster than traditional software development processes

{{% note %}}
When we look at DevEx through this lens, it aligns perfectly with what DevOps is....
{{% /note %}}

---

### Core DevOps Principles

- Collaboration
- Communication
- Shared Responsibility

{{% note %}}
...along with some of the core DevOps practices.
**Collaboration:** Collaboration in DevOps transcends traditional team boundaries, fostering a culture where developers, operations, and other stakeholders work closely together throughout the entire software development lifecycle. This unified approach encourages the sharing of knowledge, skills, and efforts to achieve common goals, leading to faster problem-solving, innovation, and a more cohesive product development process. It is about creating an environment where silos are broken down, and cross-functional teams are empowered to work as a single unit.
**Communication:** Effective communication is the backbone of DevOps, ensuring that all members of the development, operations, and broader organizational team are on the same page. This principle emphasizes open, continuous dialogue and feedback loops between teams, which helps in identifying and addressing issues early, aligning on project goals, and facilitating seamless handoffs between stages of development. Tools and practices that enhance transparency, such as daily stand-ups, chat applications, and collaborative platforms, are crucial for maintaining high levels of communication.
**Shared Responsibility:** Shared responsibility in DevOps means that all team members are collectively accountable for the software's quality and reliability, blurring the lines between roles traditionally separated by development and operations. This principle encourages everyone to take part in tasks such as testing, deployment, monitoring, and troubleshooting, promoting a sense of ownership and a proactive approach to problem-solving across the lifecycle. It's about moving away from a "not my job" mentality to a "we're in this together" mindset, where success and failures are shared equally.
{{% /note %}}

---

### DevEx & DevOps Alignment




{{% note %}}
**Enhancing Collaboration through DevEx:** DevEx improves collaboration by providing tools and processes that make it easier for developers, operations, and other stakeholders to work together. This includes integrated development environments (IDEs), version control systems, and collaborative platforms that support real-time co-editing and issue tracking. By reducing friction and barriers in the development process, DevEx enables teams to focus more on solving business problems together, leading to innovative solutions and a more harmonious working environment.
**Improving Communication via DevEx:** Effective DevEx facilitates better communication by offering platforms and tools that streamline information sharing and feedback across teams. Tools such as continuous integration/continuous deployment (CI/CD) pipelines, shared dashboards, and automated alerting systems ensure that all team members have visibility into the development process, can easily share updates, and quickly address issues. This transparency and ease of communication help maintain alignment on project goals and accelerate decision-making processes.
**Shared Responsibility Supported by DevEx:** A well-designed DevEx environment supports the principle of shared responsibility by empowering all team members with access to the tools and information they need to contribute across the entire software lifecycle. This includes giving developers access to deployment and monitoring tools, enabling operations to participate in early stages of design and planning, and ensuring that everyone has the skills and knowledge to contribute to quality assurance, security, and performance optimization. By democratizing access to tools and information, DevEx encourages a culture where everyone feels ownership of the product and is motivated to contribute to its success.
{{% /note %}}

---



{{% note %}}
By integrating DevEx with these core DevOps principles, organizations can build more cohesive, agile, and effective teams that are better equipped to meet the demands of modern software development. This synergy not only improves the workflow and productivity but also enhances the overall quality of the software delivered, ultimately benefiting the end-users.
{{% /note %}}

---

## DevEx and DevOps are One

{{% note %}}
a robust Developer Experience (DevEx) fosters a more integrated and efficient collaboration between development (Dev) and operations (Ops) teams, and highlights best practices for achieving this unity and efficiency. There's no better example than what we've seen with Platform Engineering the last few years.
{{% /note %}}

---

{{< slide background-image="/images/slides/32-platform-engineering.jpg" background-opacity=".6" >}}

#### The rise of Platform Engineering



{{% note %}}
The rise of platform engineering represents a paradigm shift towards creating comprehensive, integrated environments that cater specifically to the needs of developers. This movement focuses on abstracting away the complexities of infrastructure and backend services, allowing developers to concentrate on writing code and creating value. Platform engineering embodies the principles of DevEx by ensuring that developers have access to robust, scalable, and easy-to-use platforms. These platforms streamline development processes, reduce setup time, and allow for a focus on innovation rather than maintenance.
{{% /note %}}

---

##### Self-Service Platforms

{{% note %}}
Self-service platforms epitomize the evolution of DevEx by empowering developers to independently provision resources, deploy applications, and manage their lifecycles without waiting for operational support. These platforms leverage automation, templates, and predefined policies to ensure compliance and governance, while offering the agility needed for rapid development cycles. By providing developers with the tools to perform tasks that were traditionally in the domain of IT operations, self-service platforms accelerate development, enhance productivity, and foster a culture of autonomy and innovation.
{{% /note %}}



---

### Bringing Dev and Ops Together

{{% note %}}
The convergence of DevEx and DevOps represents a strategic alignment that breaks down traditional silos between developers and operations teams, fostering a culture of collaboration and mutual understanding. By prioritizing DevEx, organizations ensure that developers have access to tools and processes that not only streamline their workflow but also facilitate a smoother transition of code from development to production. This alignment encourages both teams to work closely from the outset of projects, sharing insights, feedback, and responsibilities, which enhances the efficiency of the development lifecycle and leads to higher quality outcomes. Key to this synergy is the adoption of practices such as continuous integration and continuous deployment (CI/CD), which rely on automation to reduce manual toil and speed up delivery, while maintaining high standards of reliability and security.
{{% /note %}}

---

### Better Practices

{{% note %}}
**Empower with the Right Tools:** Equip teams with integrated, user-friendly tools that support automation, collaboration, and real-time communication. This includes choosing IDEs, version control systems, CI/CD pipelines, and monitoring tools that align with both Dev and Ops needs.
**Encourage Cross-functional Teams:** Promote the formation of cross-functional teams that include roles with diverse expertise (e.g., development, operations, quality assurance) to foster a shared understanding and responsibility from project inception through to deployment and maintenance.
**Implement Feedback Loops:** Establish robust feedback mechanisms that allow for continuous learning and improvement. This can be achieved through regular retrospectives, incorporating user feedback into development cycles, and using monitoring tools to gather insights on performance and user experience.
**Focus on Automation:** Automate repetitive and manual tasks wherever possible to reduce toil and free up team members to focus on more strategic activities. This includes automating testing, deployments, and infrastructure provisioning.
**Invest in Training and Development:** Ensure that team members have opportunities to learn and grow their skills in both development and operations domains. This helps in building empathy between teams and equips individuals with the knowledge to understand and contribute to different stages of the development lifecycle.
{{% /note %}}

---

## DevEx Impact
### Productivity



{{% note %}}
**Streamlined Development Environments:** By providing developers with well-configured, easy-to-use development environments, organizations can significantly reduce setup times and minimize configuration-related delays. For instance, containerization technologies like Docker allow developers to spin up consistent development environments quickly, leading to faster start times on new projects and less time spent on environment-related issues.
**Integrated and Automated Toolchains:** The use of integrated development environments (IDEs) and automation tools (for testing, building, and deployment) enhances productivity by automating repetitive tasks. Tools like Visual Studio Code, Jenkins, and GitLab CI/CD automate code analysis, builds, tests, and deployments, allowing developers to focus on coding and problem-solving rather than manual processes.
**Efficient Collaboration Platforms:** Platforms that facilitate easy collaboration and communication, such as Slack, JIRA, and GitHub, help streamline the development process. These tools support real-time communication, issue tracking, and code reviews, enabling developers to collaborate effectively, regardless of their physical location.

There is a direct correlation with productivity: When developers spend less time grappling with cumbersome processes and more on actual coding, innovation thrives. And then there are the psychological aspects. A good DevEx means less frustration and burnout, leading to higher job satisfaction and retention rates. Developers feel empowered and valued, which in turn boosts their motivation and engagement.  
{{% /note %}}

---

## DevEx Impact
### Morale



{{% note %}}
**Autonomy and Empowerment:** Providing developers with self-service platforms and tools that allow them to make decisions and manage their workflows can significantly boost their sense of autonomy and empowerment. For example, self-service portals for provisioning infrastructure or deploying applications enable developers to execute tasks without waiting for operations or IT support, fostering a sense of ownership and independence.
**Recognition and Achievement:** Tools that facilitate continuous integration and delivery (CI/CD) not only improve productivity but also allow for quicker feedback on developers' work. This immediate feedback loop, where developers can see their contributions go live and make an impact promptly, can be incredibly satisfying and motivating, leading to a positive feedback cycle of achievement and recognition.
**Reduced Frustration and Burnout:** By minimizing the friction in the development process—through better tooling, clearer processes, and supportive team dynamics—organizations can significantly reduce developer frustration and the risk of burnout. When developers spend less time on tedious, repetitive tasks or waiting for dependencies, they have more energy and enthusiasm for creative and challenging work, leading to higher job satisfaction.
**Learning and Growth Opportunities:** A positive DevEx often includes access to resources, training, and opportunities to explore new technologies and practices. This fosters a culture of continuous learning and professional growth, which can greatly enhance morale. Developers feel valued and supported in their career paths, contributing to a more engaged and motivated team.

There is a direct correlation with productivity: When developers spend less time grappling with cumbersome processes and more on actual coding, innovation thrives. And then there are the psychological aspects. A good DevEx means less frustration and burnout, leading to higher job satisfaction and retention rates. Developers feel empowered and valued, which in turn boosts their motivation and engagement.  

a thoughtful focus on DevEx can lead to tangible improvements in productivity and morale, which are crucial for the success and sustainability of development teams in the fast-paced and ever-evolving landscape of software development.

{{% /note %}}

---

### DevEx reflects an organizations values

{{% tweet user="IAmJerdog" id="1750563607266410692" %}}

{{% note %}}
The level of investment that a company invests in DevEx can be a reflection of a company's values towards its employees, especially its developers. A strong focus on DevEx shows a commitment to employee well-being and efficiency. And prioritizing DevEx helps foster a culture of excellence and innovation. When developers are provided with the right tools, support, and environment, they are more likely to produce high-quality work and push the boundaries of what's possible.
{{% /note %}}

---

## Final Thoughts
### Future is bright

{{% note %}}

{{% /note %}}

---

### Things to think about
#### Integration of AI and ML


{{% note %}}
**Automated Code Generation and Review:** The integration of AI and machine learning into development tools can significantly enhance DevEx by automating more aspects of coding, such as code generation and review. Tools like GitHub Copilot suggest code snippets and entire functions, improving developer productivity and potentially reducing bugs.
**Predictive Analytics in DevOps:** AI can analyze patterns from past incidents to predict potential future failures, enabling proactive measures in DevOps practices. This could lead to more resilient systems and smoother operations.
{{% /note %}}

---

### Things to think about
#### Focus on Developer Well-Being

{{% note %}}
Recognizing the impact of developer satisfaction on productivity and creativity, organizations will increasingly prioritize measures that enhance well-being. This includes flexible working arrangements, tools that reduce frustration and burnout, and a culture that values learning and growth.
{{% /note %}}

---

### Things to think about
#### Continuous Learning & Skill Development

{{% note %}}
The rapid pace of technological change will necessitate a greater emphasis on continuous learning and skill development. Organizations will invest in training and development programs to help their teams keep up with new tools, practices, and technologies, enhancing both DevOps and DevEx.
{{% /note %}}

---

# DevEx is...

>### "ruthlessly eliminating barriers (and blockers) that keep your developers from being successful"

{{% note %}}
ruthlessly eliminating barriers (and blockers) that keep your developers from being successful.
{{% /note %}}

---

{{< slide id="end" >}}
<section>
    <div class="multiCol">
        <div class="col">
            <h2 style="color: #04aa51; text-shadow: none;">Thank You.</h2>
            <img src="/images/slides/generic-DevEx-talk-qrcode.png" alt="DevEx Talk QR Code" style="width: 100%; max-width: 200px; margin: 0 auto;">
            <a href="https://bit.ly/DevExTalk/">https://bit.ly/DevExTalk</a>
        </div>
        <div class="col" align="center"></div>
        <div class="col" align="left" style="font-size: .5em;">
            <img src="/images/linkedin.png" height="50px" style="vertical-align: middle; margin: 10px;">/in/jeremymeiss<br />
            <img src="/images/twitter.png" height="50px" style="vertical-align: middle; margin: 10px;">@IAmJerdog<br />
            <img src="/images/devto.png" height="50px" style="vertical-align: middle; margin: 10px;">@jerdog<br />
            <img src="/images/mastodon.png" height="50px" style="vertical-align: middle; margin: 10px;">@jerdog@hachyderm.io
        </div>
    </div>
</section>

{{% note %}}

{{% /note %}}