<a id="top"></a>
# DevFest Product Track

*This curriculum introduces the fundamental steps of the product development process from brainstorming to growing your user base.*

Written and developed by [Kimberly Hou](http://kimberlyhou.com), [George Liu](), and [Joshua Zweig]().

<a href="#top" class="top" id="getting-started">Top</a>
# About This Document

## Methodology
For the first three levels of the curriculum, we will finish each day with deliverables for everyone’s individual project ideas. Since we will also cover parts of the process after the prototype has been built, we’ve included a sample project to use for activities on the fourth day. 

<a href="#top" class="top" id="table-of-contents">Top</a>
# Table of Contents
-	[Level 1: Planning](#planning)
	-	[1.1 Product Life Cycle](#product-life-cycle)
	-	[1.2 Market Validation](#market-validation)
		-	[1.2.1 Defining Market Validation](#defining-market-validation)
		-	[1.2.2 Snapchat Case Study Part I](#snapchat-case-study-part-i)
	-	[1.3 User Feedback](#user-feedback)
		-	[1.3.1 User Tests](#user-tests)
		-	[1.3.2 Screeners](#screeners)
	-	[1.4 Business Models](#business-models)
		-	[1.4.1 What's in a Business Model?](#whats-in-a-business-model)
		-	[1.4.2 Examples of Business Models](#examples-of-business-models)
		-	[1.4.3 Lean Canvas](#lean-canvas)
-	[2.0 Design I](#design-i)
	-	[2.1 Specs](#specs)
		-	[2.1.1 What Are Specs?](#what-are-specs)
		-	[2.1.2 User Stories](#user-stories)
	-	[2.2 Personas](#personas)
	-	[2.3 User Flows](#user-flows)
		-	[2.3.1 What User Flows Entail](#what-user-flows-entail)
		-	[2.3.2 Snapchat Case Study Part II](#snapchat-case-study-part-ii)
-	[3.0 Design II](#design-ii)
	-	[3.1 Specs](#wireframe)
	-	[3.2 Mockup](#mockup)
	-	[3.3 Bonus](#bonus)
-	[4.0 Analytics](#analytics)
	-	[4.1 How Do These Tools Work?](#how-do-these-tools-work)
	-	[4.2 Google Tag Manager](#google-tag-manager)
		-	[4.2.1 Setting up GTM](#setting-up-gtm)
		-	[4.2.2 Add Event Handlers](#add-event-handlers)
		-	[4.2.3 Add a Trigger in GTM](#add-a-trigger-in-gtm)
		-	[4.2.4 Add a Tag in GTM](#add-a-tag-in-gtm)
		-	[4.2.5 GTM Bonus and Wrapups](#gtm-bonus-and-wrapups)
	-	[4.3 Mixpanel](#mixpanel)
		-	[4.3.1 Creating a Mixpanel account](#creating-a-mixpanel-account)
		-	[4.3.2 Preview Site in GTM](#preview-site-in-gtm)
		-	[4.3.3 Live View in Mixpanel](#live-view-in-mixpanel)
		-	[4.3.4 Mixpanel Wrapups](#mixpanel-wrapups)
-	[5.0 Growth](#growth)
	-	[5.1 Before / During MVP Creation](#before-during-mvp-creation)
	-	[5.2 After MVP Creation](#after-mvp-creation)
	-	[5.3 The Growth Funnel](#the-growth-funnel)

------------------------------
<a href="#top" class="top" id="planning">Top</a>
# Level 1: Planning
A lot of discussion, sticky notes, and Googling go into building a product long before the product is actually built. Below we’ll introduce a few separate ideas that come together when researching the problem and the space in which we’re building a product. 

After today, we’ll each have a product idea with a rough business model sketched out using the Lean Canvas. In the next level, we’ll then design the features and corresponding methods of implementation based on the business model. 

<a href="#top" class="top" id="product-life-cycle">Top</a>
## 1.1 Product Life Cycle
While software companies might define their product development cycles differently, there are generally three main steps involved:

Planning -- Based on the company’s missions and values, market research, competitor landscape, and user needs, let’s identify the specific problem and how to solve it
Design -- Drawing from current user pain points for other competing products, let’s create a refreshing and enriching user experience that matches with our product’s value proposition
Implementation -- We build out the product according to our plans and re-prioritize adjustments as a larger scale of user feedback rolls in 

In today’s part of the curriculum, we’ll take a look at various ways research is conducted as part of the planning stage. Afterwards, we’ll apply what we’ve learned to a case study of Snapchat, one of today’s hot consumer apps out there. 

<a href="#top" class="top" id="market-validation">Top</a>
## 1.2 Market Validation

<a id="defining-market-validation"></a>
### 1.2.1 Defining Market Validation
Market validation is the process of gauging your target market’s interest in your product. 
If you can hypothetically sell it before you build it, you will have saved yourself a lot of time from spending hours on a product only to find out users are not interested in it.

Before building a product, it’s important to define who your users/customers are to make sure what you create would be relevant to your audience. A few questions to consider:
-	What is the problem we’re trying to solve?
-	Who are the users and customers? Customers won’t always be the same as your users.
-	What would the target market be willing to pay / how can the product be profitable?
-	Who would our competitors be, and what are their strengths / weaknesses?

<a id="snapchat-case-study-part-i"></a>
### 1.2.2 Snapchat Case Study Part I
What problem does Snapchat design a solution for?
-	"Snapchat isn't about capturing the traditional Kodak moment. It's about communicating with the full range of human emotion — not just what appears to be pretty or perfect."
-	"Emergency detagging of Facebook photos before job interviews and photoshopping blemishes out of candid shots before they hit the internet" [source]

<a href="#top" class="top" id="design-i">Top</a>
# Level 2: Design I

Hooray! We now have our proposed business model. Before we lay out any plans for our product’s visuals, let’s take a look at a few techniques that product managers use to convey the specifics of the implementation to designers, engineers, and other involved team members. 

<a href="#top" class="top" id="specs"><Top></a>
## 2.1 Specs
<a id="what-are-specs"></a>
### 2.1.1 What are specs?

When talking with product managers, you might hear them talk about specs, which they’re often in charge of writing. Specs -- short for specifications -- refer to the document that describes the the high-level purpose and vision of the product all the way down to the nitty gritty details of the features and how those features are implemented. 

There is no standardized way across companies to write specs, but they generally have the same fundamental elements:
Version of the product 
Purpose and vision of the product
How users can interact with the product (as organized by user stories or just the different features themselves, e.g. Search Box)

Note that for bigger companies, specs can also be written for individual features of a much larger product. 

<a id="user-stories"></a>
### 2.1.2 User stories

Often, specs are built by starting out with user stories. A user story describes a specific use case of a specific feature. It usually goes by the following template: 

As a <type of user>, I can <do something> so that <something>.

A few examples of what user stories might look like:
TI-84 Calculator -- As a high school student, I can draw graphs using the calculator so that I can make data visualizations in math classes. 
GroupMe -- As a user, I can ‘favorite’ a message in a conversation in order to increase the opportunities for social interactions.
FaceTime -- As an iPhone 6S user, I can view my FaceTime call history.

From these general user stories, further and more specific user stories are created to implement a solution for every possibility of every feature’s use case. 

<a id="sample-specs"></a>
### 2.1.3 Sample Specs

For reference, below is a sample spec for ideas. 

Mozilla - https://docs.google.com/document/d/1VzNPatym-iyd2aJNsWlvsNGjb3MZEacEvKpfouV3VGw/edit

<a href="#top" class="top" id="personas"><Top></a>
## 2.2 Personas

As part of optimizing user experience for a product, some designers emphasize the use of developing personas. Personas are different user types based on research and feedback to separate and define the kinds of users who may be interacting with your product. Not all designers like to create personas, preferring to rely strictly on iterative techniques like A/B testing to gather all user preferences and design decisions. If you choose to develop personas for your product, keep in mind the characteristics of each must be rooted in data to prevent them from becoming mere stereotypes.

Personas may also be used for branding and marketing purposes in addition to user-centered design. For instance, CityMapper capitalizes on the stereotypes of its users as part of marketing - 

[Citymapper photo] 

<a href="#top" class="top" id="user-flows"><Top></a>
## 2.3 User Flows

<a id="what-user-flow-entails"></a>
### 2.3.1 What User Flows Entail

User flows visualize the user’s path from start to finish, documenting how the user interacts with your product and completes the funnel. The funnel in this case refers to a multi-step task (whether filling out a registration form or answering a survey, etc.) that your user would ideally complete. Obviously, most people would start the process but many exit out of the process for various reasons (thus creating a decreasing funnel shape). Those who do complete the entire process are referred to as conversions. 

Before creating user flows, it’s important to clearly define your product’s goals (e.g. getting a visitor to sign up) and your user’s goals (what the user would desire or need). Think about how you can create each step of the way as something a user would want to do. 

Also, remember that the users may come upon your site / product through various sources; examples include through a paid ad, organic search, or simply through a direct link to your site. Will they be directed to a landing page based on where they came from and the wording of your ads? The user flow isn’t always the same.

<a href="#top" class="top" id="snapchat-case-study-part-ii"><Top></a>
### 2.3.2 Snapchat Case Study

The key workflow to sending a snap is just 3 steps. The most common flow (sending a snap) is abstracted to take a minimal number of input/keystrokes from the user (read down the right hand column of the figure).
Going back to the mission statement: the workflow is optimized for people to take and share photos that capture their unabridged emotion and state. This is why the home screen on first launch of the app is the camera. The camera is the center of the UI. 

The way to think about your metrics is by thinking about what questions you want to ask yourself about how your users are using your product. Snapchat might be interested in the following questions about how their users are using the app:
-	Is there a drop off point/bottleneck where users are stopping in the flow of sending a snap?
-	Putting counts in about how many users are at each point in the flow could give insight into this
-	This could help snapchat identify if there is a painpoint/bottleneck in the app flow
-	How many friends does the average user have?
-	Gives insight into the userbase
-	Could be an interesting KPI for engagement and possible investors
-	How many daily active users does snapchat have?
-	KPI common in the industry 
-	How many snaps do users send?
-	Could be important in properly allocating servers
-	Where is Snapchat being used?
-	Again important in where to place data centers
-	What demographic of people is using our app?
-	It is crucial to KNOW WHO YOUR USERS ARE
-	When building and revising a product, you must know who you are building it for
-	Are people returning to the app?
-	Another interesting KPI
-	Could identify other possible bottlenecks 

Deliverable: Create a spec for your product. Tomorrow you’ll be using it to design your mocks!

<a href="#top" class="top" id="growth">Top</a>
# Level 5: Growth

Growth needs to be prioritized at every stage of your product for it to succeed. The assumption that “good products sell themselves” has never been more false. Conceptually and in a vacuum, this statement seems logical. However, in the cutthroat reality of a world saturated with countless products competing for every consumer/organization’s attention span each day, it is difficult for good products to even get thought of by their consumers, much less get used.

In fact, even if a product is good and has huge factors in its favor, such as a large existing user base, significant funding, or first-mover advantage, it’ll still probably fail. Just look at products such as Rdio, Sidecar, Secret, Google+, Everpix, Slingshot, and countless other products now in the graveyard. Now more than ever, growth principles need to be instilled in the product for it to even have a chance of survival.

<a href="#top" class="top" id="before-during-mvp-creation">Top</a>
## 5.1 Before / During MVP Creation
The Hook Model -- When creating your product, your ultimate goal should be to turn your product into a habit. Use Nir Eyal’s Hook Model to dissect a user’s flow throughout your product and determine which areas to improve. The hook model is a cycle comprised of four parts: trigger, action, variable reward, and investment.

[Photo Here]

What’s your product’s trigger? -- A trigger sparks the beginning of a user’s behavior in your app. There are two types of triggers, external and internal. An external trigger is something that the user sees and one that alerts users to come to the product; examples include an email, link, or the app icon. An Internal trigger is something the user thinks or feels and attaches itself to a user’s existing behaviors. This attachment done through the user cycling through the Hook Model multiple times. When a product becomes tightly coupled with a thought, an emotion, or a preexisting routine, it leverages an internal trigger. Probably the best example of an internal trigger is your itch to check your Facebook newsfeed every day if you’re bored.

What’s your product’s action? -- An action is the minimum interaction the user needs to do to get a reward (next step). It follows the trigger. In deciding what action the user should take, use the Fogg Behavior Model as a reference. The Fogg Behavior Model states that there are three core motivators required to initiate any and all behaviors:
- Seek pleasure and avoid pain
- Seek hope and avoid fear
- Seek social acceptance and avoid rejection

In addition to this model, take into account various mental heuristics all humans have. The most relevant ones include:
The scarcity effect: the appearance of scarcity affects perception of value
The framing effect: context also shapes perception and the mind takes shortcuts informed by our surroundings to make quick and sometimes erroneous judgment
Anchoring effect: people often anchor to one piece of info when making a decision
Endowed progress effect: a phenomenon that increases motivation as people believe they are nearing a goal

Finally, the user should also have the ability to complete the desired action with the greatest amount of ease possible. Any tech/product that significantly reduces steps to complete a task will enjoy high adoption rates by people it assists.

What’s your product’s variable reward? -- Levels of dopamine surge when the brain is expecting a reward and there is very little diminishing marginal effectiveness when the reward has different content every time. Moreover, introducing variability multiplies the effect, creating a focused state, which suppresses the areas of the brain associated with judgment and reason while activating parts associated with desire.

Variable rewards come in three types: the reward of the tribe, the reward of the hunt, and the reward of the self. 
- The tribe: the need to feel accepted and important
- The hunt: the need to acquire a prize
- The self: the need to better oneself 

What investment does your product ask from the user? 
Investment is the last phase of the Hook Model and it focuses on increasing the odds the user will make another pass through the Hook Model. Remember, the more cycles a user makes through your product, the stickier it becomes and the more it becomes associated with an internal trigger.

An investment occurs when the user puts something into the product such as time, data, effort, social capital, or money. Moreover, an investment needs to imply an action that improves the service for the next go-around. Examples include inviting friends, stating preferences, building virtual assets, and learning to use new features are also investments.

Okay great. Now you have a conceptual framework to build growth into your product. Now how do you measure its effectiveness and iterate on this MVP?

<a href="#top" class="top" id="after-mvp-creation">Top</a>
## 5.2 After MVP Creation

The hooked model is a great conceptual framework to keep in mind throughout all stages of a product’s lifecycle, but after the minimum viable product is created and pushed out to your target audience, you also need a framework to digest usage data and create experiments.

Experimentation process -- Here is the process used by the HubSpot growth team. This framework is a sustainable growth process that is scalable, repeatable, and somewhat predictable in trying out and optimizing user growth channels. 

The first step is to know where you’re going and set goals with an OKR framework (Objective and Key Results). 
OBJECTIVE: Qualitative statement. Take a step back and ask what is the one area you can work on that drives the biggest impact on your growth curve right now?
TIMEFRAME: 30 - 90 Days 
- KR1: Measurable Goal 1 (Hit 90% Of Time) 
- KR2: Measurable Goal 2 (Hit 50% Of Time)
- KR3: Measurable Goal 3 (Hit 10% Of Time)
One of the biggest mistakes almost all startups do is trying everything at once instead of prioritizing; this OKR helps prevent this. There’s tremendous risk to diversifying growth channels too early: you stretch thin already limited resources and end up doing so many things at once the results come back extremely slow and you get nowhere for a long time. Instead, it’s much better to prioritize and choose one or two channels at a time to test out. If they don’t work, take the learnings, which give you a much better sense of the next one or two channels to move on to, and move on to these channels. Even in the longterm, a lot of successful companies scale off the back of one major acquisition channel (can account for 80% of a company’s growth).

The second step is to hit the road as fast as possible after setting OKRs. This process is comprised of brainstorming, testing, implementing, analyzing, and systemizing.

Brainstorm -- There are four ways to generate growth ideas: observing, questioning, associating, and networking
Observe: how are others doing it? Look outside of your immediate product space. Walk through together.
Question: Why? What is... What if... What about... How do we do more of... 
Associate: connect the dots between unrelated things. 
Network: growth mastermind groups.

Prioritize -- Prioritize based on three main factors: probability of success, impact, resources. Do the low-resource things first because you should try to get as many experiments in as possible.

Test -- Create a minimum viable test and an experiment document detailing the test. A minimum viable test is the minimum thing you can do to test hypothesis. Afterwards, implement the test as fast as possible; remember that you want to get as many experiments in as possible. 

Analyze -- This is the most important step of the process. Important areas of analysis include the impact of the test, the accuracy of the hypothesis, and why you believe the results of the experiment happened. As you extract as many learnings as you can, turn them into new action items, and adjust priorities and predictions accordingly

Systemize -- After analyzing, systemize your learnings by taking the successful learnings and feeding them back into the process. Integrate learnings as much as you can into the product itself and for the things you can’t productize, build into step by step playbooks to make them repeatable.

Throughout this process, you should have created five key documents.
- OKR
- Backlog: the backlog of experiment ideas. 
- Pipeline Experiments: a ledger of experiments that were ran or are currently running and the highlights of their results. 
- Experiment Doc: Include the Objective, Hypothesis, Experiment Design, Results, Analysis, and Learnings
- Playbooks: Step by step guides for successful experiments that should be repeated.

Take a step back -- Have review every quarter and look at your operations from a macro perspective. Consider issues such as
- What’s your batting average? How many successes to failures? 
- Is it improving over time? Are your hypotheses getting more accurate?
- How many experiments are you running in a given time period? How do you do more?
- Afterwards, optimize accordingly by improving the team, the process, or the tools.

<a href="#top" class="top" id="the-growth-funnel">Top</a>
## 5.3 The Growth Funnel
Since brainstorming is the hardest and most abstract component of this process, I’m going to expand on this. You can find and run ideas through the aforementioned Hook Model but now’s also a good time to introduce the AARRR framework (the growth funnel) popularized by 500 Startups, which helps you find ideas for which growth channels and metrics to focus on.

Acquisition -- People come to your site after they’ve heard about you through press, blogs, word of mouth, and other acquisition channels. There are two types of acquisition channels: inbound and outbound. Inbound acquisition channels focus on creating quality content that pulls people in. Example inbound channels include blogging, podcasting, ebooks, guides, whitepapers, infographics, webinars, conferences, videos, slide decks, SEO, and an organic social media presence. Outbound acquisition channels focus on pushing information to people in often disruptive ways. Examples of outbound marketing include billboards, television ads, social media ads, promotional swaps, and affiliate marketing.

Activation -- If people like what they see on your homepage or other landing page, they’ll become users by either creating an account, signing up for a newsletter, or some other form of activation. Activation methods include landing pages, copywriting, calls to action, onboarding, gamification, social proof. 

Retention -- Users come back to the site through reminders and stay active through product features they encounter while they’re back on the site. Retention is the most important part of the funnel; it provides the foundation of growth and every improvement to retention also improves virality, the lifetime value of a customer, and payback period.
To improve week one retention, get users to experience the core value of the product as quickly as possible using better onboarding, clearer messaging, and segmented NUX targeted at different users. Improving Week 1 retention is particularly important because it shifts the whole retention curve up.
To improve mid-term retention, get users to create habits around the core value of the product (ie through the Hook Model).
To improve long-term retention, get users to experience the core value as much as possible (ie through the Hook Model)

Referral -- Active users refer others through viral product features and other incentives. Social media sharing buttons, social logins, referral competition, referral rewards, pre-written emails, etc. are all ways to get people to recommend your product. 

Revenue -- Eventually you’ll have to monetize active users through advertising, lead generation offers, subscription, or business development.

Deliverable: Brainstorm some of the mechanisms you’ll use to get people through each stage of the growth funnel. 
___________
<a href="#top" class="top" id="additionalresources">Top</a>
## Additional Resources

Along with this tutorial, there is a wealth of information available on Python all across the web. Below are some good places to start:

- [ADI Resources][learn]
- [Codecademy][codecademy]



[github]: 
[learn]: http://adicu.com/learn
[codecademy]: http://www.codecademy.com
[adi]: http://adicu.com

[source]: http://blog.snapchat.com/post/22756675666/lets-chat
 
