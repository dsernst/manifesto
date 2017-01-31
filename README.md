# Manifesto for Facebook Democracy

The idea behind this manifesto is to create an open organization with the intent of providing, maintaning and auditing a democratic platform built on top of the Facebook social network. Where pages would act as organizations providing users the capability of voting on proposals that matter to them. Like universities, non-profit organizations, political parties and any type of organization which wants users to engage more on a decision making process in a way that is already familiar to them.

To achieve this goal we would make the Facebook the center of the democratic experience, using all features and services provided by them. However, all votes, delegations and auditing process would be externaly, so we can control the process over letting them do the calculations. Also, because the UI affects a lot how users think and vote, we would display the proposals and their disussions on a separated light interface, accessible via links shared on Facebook.

I expect that with that we may be able to spread the idea of Liquid Democracy and make it a part of the general public's everyday life. Introducing people to a new platform is always difficult, so why not make use of the existing ones? And because of its spread and influence, I believe that Facebook is the perfect one for this.

## Inspirations

The idea was inspired by the current destabilization of the democratic order that is happening on many western nations, where is becoming aparently that we must rethink the way we think and act about social issues. Another factor that motivates the creation of this project is the impact that Facebook had on the 2016 elections and the speculation about Mark Zuckenberg's political ambitions. This made me belive that is time to introduce the idea of Liquid Democracy to the general public and that making it a part of the Facebook engagement experience would be the first and the most important step.

## Draft

I would like to present a draft on how to make this proposal a reality. The project is on its embrionary stage, so don't expect that all solutions would be presented here, on the contrary, I am proposing a discussion so we can figure out the problems before starting writing any software.

### Main Components

In order to start talking about the implementation of such system, first I will list and explain the main components that I indentified so far.

#### The Facebook User

The user would be basically the Facebook profile and its ID, which will serve as a traceable way to indentify its voting record. In order to restrain and validate who will vote on a certain issue, the user would be verified by a passcode provided by the Facebook page. The passcode generation would be done on the platform as the page wishes.

#### The Facebook Page

The page will act as an organization, deciding how the democratic will took place. It can opt for a open discussion, where users can define their issues and have more control over the process, or controlling which issues are being voted upon. This options may vary from subject to subject, or be a default option.

#### The Facebook Post

The post will serve as an subject area being voted, where the page will decide the configurations of it. Such as the issues being voted, how long the voting process will take. The post will be dynamic using webviews, where the users will be able to see a summary of the voting process and being able to click on a call-to-action button which will redirect him to a page with all the arguments behind the proposal.

#### The Issue

Issues are the initiatives competing for votes. Besides the summary displayed on Facebook, the issues are controlled and inputed by the platform.

#### The Vote

Votes are a relation between the facebook ID, the page, the post and the issue. Which should be traceable by the one who cast it, and the audinting organization. 

#### The Delegation

Delegations are made by users of the same page and the delegation will hold for that one post only. The delegation will occur when a user clicks on a call-to-action button linked to the plaftorm, which will identify the user delegating and the one being delegated.

### User Interface and Experience

As mentioned previously, the Facebook will be the main point of experience, all actions and notifications will derive and be presented on it. Where the page will act as the organization, the users as the voters and delegators and the Facebook as the voting system. In order to achieve that, I have thinked about this requirements:

#### Requirements

- Users should be allowed to use their own Facebook's profile
- Users should be able to see their voting record from their Facebook's profile
- Users should be able to see other voting records (on Facebook, if possible)
- Users should be able to delegate their vote to other users (on Facebook, if possible) 
- Users should be notificated about the effects any decision made by them of by their delegated on Facebook
- Users should be able to change their vote at any time before the closing of that issue
- Facebook pages should be able to decide which users should be able to vote
- Facebook pages shoud be able to decide whether users can open issues or not

### Facebook Integration

In order to integrate with Facebook and still providing all functionalities needed to run a liquid democracy system, I think that the steps needed to be taken are the following:

#### Requirements

- The Facebook ID would be used to identify the users vote and if they could or not vote on topics discussed on a specific page.
- The policy should be associated with a post from the Facebook
- The should be dynamic in a way that the user could see a summary of the policy being voted
- The user should click on call-to-action button and then vote on the policy page
- The user should receive a message on his Facebok inbox showing his delegator has cast a vote
- When someone cast a vote directly, we should be able to post it on Facebook

### Security and Privacy

Security and privary are the main issue when dealing with digital voting, and they are more aggravated when you're dealing with a Social Network that is runned by a corporation with its on agenda. So, in order to build the best democratic system, I think that the steps needed to be taken are the following:

#### Requirements

- All votes will visible only by the one who casted it, unless he don't want it so
- All delegated votes should be seen by the one who delegated it
- The delegates voting records on that page should be visible to their delegators

### Auditing

### Open-Source and Organization Goals

## Members
Diego Rodrigues, Founder - diego.mrodrigues@outlook.com
David Ernst – david@liquid.vote
