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
 
