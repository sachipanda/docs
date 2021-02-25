# 6 Steps to a Successful DevOps Adoption
Figuring out the most optimal way to enable agility and rapidly deliver services to customers—without compromising quality—continues to be one of our industry’s biggest challenges. Many IT leaders agree that implementing DevOps practices can significantly accelerate software releases while still assuring our applications meet quality objectives.

If you’re considering a move to a DevOps delivery model, here are six approaches I’ve found to be critical for ensuring a successful DevOps adoption within an organization.

### 1. Embrace a DevOps Mindset
DevOps doesn’t begin by just stating, “Let’s do DevOps,” and jumping in with tools. Your entire organization needs to have a clear understanding of what DevOps is and what specific business needs it can address, and, most importantly, everyone needs to be willing to change the way things have always been done.

One way to begin this process is to identify your current application value streams—the series of activities necessary for moving your products from development all the way into production. Understanding where in this delivery process there are constraints, bottlenecks, and wait queues will allow you to which activities you should concentrate on improving.

Identifying areas where your current delivery process is inefficient and must be improved is your opportunity to truly make change in your organization. But in order to do so, you must be willing to experiment. Short-term failure is acceptable, as long as you’re learning from it and improving. Instead of accepting inefficient ways of doing business because that’s the way it’s always been done, you will need to encourage your organization to ask questions like: “Why do we do this [process]? What’s its business value? How can we make it more efficient?”

Organizations often equate DevOps with automation. While automation can help accelerate manual processes, DevOps is fundamentally about collaboration and communication. If you don’t embrace strong communication and collaborative practices among everyone in the software development, testing, delivery, and operational process, automating your processes will not yield the business benefits you desire.

### 2. Make the Most of Metrics
One of the most overlooked initiatives in DevOps adoption is selecting the right metrics to record and track progress. Establishing the right baseline DevOps metrics early on and not being afraid to measure things that might initially not make you look very good is the key to being able to show demonstrative progress over time and real business benefits to senior leadership.

From my experience, these are some of most useful DevOps metrics:

Production failure rate: how often the software fails in production during a fixed period of time
Mean time to recover: how long it takes an application in production to recover from a failure
Average lead time: how long it takes for a new requirement to be built, tested, delivered, and deployed into production
Deployment speed: how fast you can deploy a new version of an application to a particular environment (integration, test, staging, preproduction, or production environments)
Deployment frequency: how often you deploy new release candidates to test, staging, preproduction, and production environments
Mean time to production: how long it takes when new code is committed into a code repository for it to be deployed to production
There are many other metrics you can collect too, but avoid collecting vanity metrics that look impressive but don’t tie to business benefit, as well as metrics that are easily gamed—meaning they make your team look good but don’t actually contribute to business improvements, such as the number of commits your team makes.

Once you’ve determined the metrics you wish to collect and have a baseline of where you currently stand, set goals for each metric so the team knows what to strive for.

Most importantly, constantly share your DevOps goals, metrics, and progress with everyone involved. Set up metrics dashboards that display current metrics and progress toward your goals. Providing complete transparency is sometimes a difficult thing for teams to do, but it will foster more effective communication and collaboration, breaking down barriers between the dev and ops teams in the process.

### 3. Understand and Address Your Unique Needs
Contrary to what those selling DevOps products will tell you, there is no “one size fits all” solution for DevOps. You cannot just drop in an automated tool or hire a self-proclaimed “DevOps engineer” and expect success. Every organization will have a unique DevOps journey tied to its specific business and culture, and that journey will be far more about changing people’s habits and communication patterns than what tools help you enable automation.

DevOps is a way of accelerating the creation and delivery of quality software, but it only succeeds if you focus on what makes business sense for your organization. For instance, if your customers can’t consume ten to twenty updates to your product a day, don’t make doing so your goal! Instead, focus on improving the usability, security, or some other key attribute your customer cares more about.

### 4. Adopt Iteratively
When getting started, don’t try to boil the ocean with a complete, enterprisewide DevOps initiative. Identify a pilot application, form a cross-functional DevOps team that includes dev, test, and operations, examine your value stream to determine constraints and bottlenecks, and create an initial deployment pipeline that addresses some of your process constraints. Measure progress and success, wash, rinse, and repeat.

Generally, you should look at tackling your biggest value stream constraints first, as doing so will have the largest business impact. Some of these constraints will be easy to resolve, while others will take a significant amount of time to correct—and often a whole lot of convincing others to change.

You’ll want to go through a few iterations to build confidence in the framework and the pilot before you start expanding to other projects. Ensure you’re making progress against your metrics before moving on and applying those lessons to other teams. Most importantly, make sure those involved are influencers who can take the principles back to their respective teams; keeping all your expertise locked up on your pilot won't help you expand to the enterprise effectively.

If you’re beginning your DevOps journey from inside a software development organization, consider starting from the beginning of your delivery process and moving toward production. Properly implementing branch management strategies and build automation is key to fast feedback that will enable efficient downstream processes in the future.

Once sound build automation is in place, a more comprehensive continuous integration capability that includes continuous testing is in order. Getting your continuous integration process working effectively will allow you to begin shifting left your assurance activities over time and speeding up delivery.

### 5. Emphasize Quality Assurance Early
Based on my observations in most organizations, testers get the least amount of time to do quality assurance, and eventually, the quality of the product suffers. Organizations that struggle with DevOps often focus their efforts on automating deployments, overlooking the needs of QA.

While it is impossible to automate all your testing in DevOps, it is critical to automate all tests run as part of your continuous integration process (unit tests, static code analysis, etc.), as well as regression testing and smoke testing performed on each environment within your delivery process. Automating at least some functional testing and nonfunctional tests associated with security, performance, and other quality characteristics can often be achieved to speed up these activities.

Run lengthy, long-running tests that may require large, production-like environments late in your DevOps process so as to not slow down earlier feedback cycles that must be quick.

### 6. Take a Smart Approach to Automation
Automation is the cornerstone of accelerating your delivery processes, and everything—infrastructure, environment, configuration, platform, build, test, process, etc.—should be defined and written in code. If something is time-intensive, broken, or prone to error, start automating there first. This will quickly benefit your team by reducing delivery times, increasing repeatability, and eliminating configuration drift.

Standardize your approach to automation in order to ensure dev, ops, QA, and everyone in between has a common frame of reference and a common language. It’s important that you use software engineering best practices when building DevOps automation. Infrastructure as code should be designed and implemented with coding standards, effectively tested, under configuration control, and well documented. The quality of your automation should be just as important as the quality of your application.
