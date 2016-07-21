.. yhatch documentation master file, created by
   sphinx-quickstart on Tue May 24 17:09:23 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. toctree::
   :maxdepth: 6
   
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
   
INTRODUCTION
==================================



.. toctree::
   :maxdepth: 6
   
Thank you for using **Y-Hatch** as an engagement solution for your business. ::

 Y-Hatch is a simple SaaS product that gets embedded in your website (coming soon
 to mobile apps as well) and allows your visitors to concurrently chat with each 
 other and help each other out with the queries they have.

The possibilities are endless. Users trust fellow users the most when it comes to a recommendation. You can have your brand ambassadors representing you , providing expertise, and you can even have customer support reps assisting with specifics.  The whole idea is engage your visitors better , faster , provide them with valuable advice from brand ambassadors (Y-ACES ) , and grow your community.

In this section, you will learn how to get started with Y-Hatch.  There are 3 crucial segments :

Client Dashboard
--------------------
The Y-Hatch ``Client Dashboard`` is your home-base. This is your Admin Dashboard section where , upon logging in, you will be seeing the analytics activity of all that has happened on your chat window on your site. You will be able to copy/download the various tables to spreadsheets for your own analysis. You can also control your chat visual settings from here. 


Chat 
--------------------
The ``Chat Window`` is the soul of our product. Once the code is embedded on your website (we will tell you how), the chat window will appear on the bottom right of your website. You website visitors can potentially start chatting with others right from this window. 


Y-ACES Dashboard
--------------------
NOTE: This is a feature that will be shortly introduced.

The ``Y-ACES dashboard`` is a dashboard created exclusively for your high engaging visitors. Once your visitors or users begin asking questions, answering questions, upvoting  and much more, they are awarded points. Once they cross 100 points, they have exclusive access to their ``Y-ACES dashboard`` with their regular login .The Dashboard gives a single point of access to the engaged users. ::

	A mobile app for Y-ACES Dashboard is coming soon.

The ACES can access the dashboard directly from a ACES mobile app, get notifications on it and also respond to questions they are interested in. Notifications are sent based on user interests that are being followed.

CONFIGURATION
==================
We will show you how you can implement Y-Hatch in a matter of 5 minutes on your business website.

.. toctree::
   :maxdepth: 6

Sign Up
-------------------
The first step for installing Y-Hatch in your business website is to sign up. Visit `Y-Hatch <http://yhatch.com>`_ and sign up. It is imperative that you put in the correct information here. Here is what you will see:

.. image:: _static/signup.png
   :width: 500px
   :alt: yhatch sign up
   :target: http://yhatch.com

1. Business Name : Enter the name of your website
#. Website : Enter the website address (Eg. www.yhatch.com) . Ensure that this is accurage.
#. Domain : Drop down and select the domain that your business falls under.
#. First name : Enter your first name.
#. Last Name : Enter your last name.
#. Email :  Enter your email address. Ensure this is accurate. This is where you will be sent an email for ``password confirmation`` and ``login details`` for your account.
#. Phone : Enter your accurate telephone number.  Preface it with your ``country code``.

Upon clicking on the ``SUBMIT`` button,  an email will be triggered to your registered email account. Do keep a look out in the bulk and junk folders as well as sometimes emails tend to land up there.  

Check your email and follow the instructions from there. You will be directed to the ``Y-Hatch Client Dashboard`` . Set a secure password and then proceed to log in.
You now have access to the client dashboard.
   
Client Dashboard 
-------------------

Chat Window on your website
-------------------
Implementing the Y-Hatch chat window on your website is very simple.  The chat window is extremely light-weight and simple, and it will not add any noticeable loading time to your website.

Prior to the embedding the following code, please work with a your tech team and ensure you have backed up all your crucial files.  Now, proceed to your main index file (eg. index.php) and in the scripts section at the top, simply copy and paste the following and save.

.. code-block:: js
    
	   
	<script type="text/javascript">
	(function(){
	var head= document.getElementsByTagName('head')[0];
      var script= document.createElement('script');
      script.type= 'text/javascript';
      script.src= 'http://www.eldew.com:3000/js/yhatch_loader.js';
      head.appendChild(script);
	})();
	</script>
	

Reload your website and you should now see the y-hatch Chat window at the bottom left. In case, you do not see it, please contact us immediately.


Y-Hatch CLIENT DASHBOARD
=================================

Here , you will learn more about your client dashboard and  how to navigate it.

Access and login
-----------------------
Once you have signed up  for an account from our website , you will receive a Welcome email with the details on how to log in.  Please proceed to  ``clients.yhatch.com`` to log in. You will see the screen below.

.. image:: _static/client-login.png
   :width: 500px
   :alt: yhatch client dashboard
   :target: http://clients.yhatch.com


The ``username`` will be the email that you had used to sign up for a y-hatch account. The ``password will`` be one which you had set.

In case you've forgotten your password, simply click on the Forgot Password link and you will receive an email. Just follow the instructions on the email to reset your password.

Client Dashboard Basics
-------------------------------
Once you sign in to your dashboard, you will see a view that looks like this.

.. image:: _static/client-dashboard.png
   :width: 500px
   :alt: yhatch client dashboard
   :target: http://clients.yhatch.com

There are 3 key elements:

1. The left Side Navigation Panel
2. The central Panel
3. The top Menu bar

The central Panel is where all the key information is displayed. Let's go through the default analytics.

Overview
--------------------

Time Frame:  the ``Time Frame`` basically sets the time window for all the data you want to see below. Drop down the field , select  from the last 30, 15, 7 or 1 day and click on ``SUBMIT``	.

Total # messages :  This shows you the total number of chat messages for the time period. It gives an idea about the number of queries/questions or comments coming in.

Total # Comments : This shows the total number of comments or replies that have been provided by users within a question on the public chat room.

Average Comments per message : This gives the average number of comments per message posted on the public chat .  This gives you an understanding of how many responses are there on average to a question or query posted- the engagement level. 

Total # Product shares:  When a person chatting copy and pastes a URL of a link from your website on the chat window, it is considered a product share. This gives the total count of the product shares during the time frame. It is a good way to understand how many of your products/services your visitors/users are talking about and which are the popular ones.

Total #Users : This number tells you the new sign-ups that have happened in the time frame on y.Hatch for your website. It gives a good understanding of engagement patterns.

Average Messages per Chat: This feature is coming soon.  We are also introducing the ability for signed up users to talk in private with other users within the y.Hatch network . This number would be the average number of messages that have been exchanged over the ``total number of private chats``. It gives an  idea of if and how users may be collaborating on your products and services within their network of friends and family.

Upvoted Messages: This tells you the number of ``upvotes`` that have taken place .

Upvoted Replies : this tells you the number of ``upvotes`` that have been given to replies over the time period.

Coming soon
-----------------

There are some new features that are coming very shortly to your yhatch chat interface. 
 
WishList Adds:  This feature will be introduced soon. When a product share happens , or a poll takes place, we are planning to introduce a feature (UI button) by which a user can add that product to their wishlist. We will then share the ``wishlist`` details with you so that you can work on customized promotions.

Polls and Questions : Polls and questions will allow a user to create a poll that can be viewed and voted by everyone else. Imagine a situation where the user wants a crowd-sourced decision to select from 4 products or services.  Questions work similarly, where a user can ask a question and request for answers. The interesting thing about polls and questions is that it gives a structure to the questions, a user needs to categorize the poll or questions.

Manage Flags
-------------------
This is a very important part of your dashboard. This is where you will need to take action against comments/replies that have been flagged by users for moderation. 

.. image:: _static/flag-moderation.png
   :width: 500px
   :alt: yhatch client dashboard
   :target: http://clients.yhatch.com

You can see the User who has flagged it, the User who has posted the comment, the Comment itself, and the reason why it has been flagged. You will need to take action on the flagged comment by pressing 1 of the 2 buttons. If you would like to remove the comment from being seen in the front end by users, click ``ACCEPT``. If you think the flag was not justified and want to continue letting users see the comment, click on ``REJECT``. Once moderated, you will not see the comment on the dashboard.

If a comment is has been flagged by multiple users, you will see multiple entries on the dashboard. However, you will need to moderate only 1 of the comments on the dashboard, and it will effect the other same entries as well.


FAQ
==================
.. toctree::
   :maxdepth: 6
   
   
What is the y.Hatch Chat window?
----------------------------------
The y.Hatch chat window is a window that can be embedded on your website (and soon, integrated with your mobile app) where visitors to your website can concurrently chat with each other (and any of your representatives who may be online at the moment!). This allow visitors to quickly gain feedback about a product or service query that they may have. 

How do I implement it?
----------------------------------
The implementation steps are super simple and takes less than 5 minutes. These are explained in the earlier section. Check it out!

How do my website visitors see it?
-----------------------------------
Once the y.Hatch code is successfully implemented on your website, it will typically appear on the bottom right of your website as a chat bubble that says "Chat with other visitors/ See what others are saying". Once the visitor clicks on it, it opens up on the right side and displays the public chat room.

Can all my visitors chat from it?
-----------------------------------
Yes! All visitors who are present on your website at that moment in time can chat  on it!

Do visitors need to sign up before chatting?
-----------------------------------------------
Not really!  They can simply ask a question and get started by entering a Nickname!

What kind of questions can a user ask?
-----------------------------------
Any kind of question really! It might be do to with a product that they like and want to get opinions from fellow visitors about. Or it could be about a service. They might even have a support related question, in which case it is a great idea to always have a support representative as part of the chat room at all times :-).

What is a poll? How can a poll be set-up?
----------------------------------
Imagine a visitor who is trying to make up her mind between 2 tops , and wants a group opinion! All she has to do is ``create a poll`` which gets posted instantly on the room, and allows people to ``upvote`` their choices!  This way, she can get a crowdsourced decision made!

Setting up  a poll is simple. There's a button called ``POLL`` in the chat box . A user has to simply click on it, ask the question (eg. " Which top do you guys think rocks?" )  , paste the 2 product option URLs on each of the option fields, and submit!   As simple as that, and the poll gets published for others to view and vote.

How do people vote on a poll?
-------------------------------
Once the poll is published, the voting is simple. A user simply has to click on the ``upvote`` button  (denoted by a "HEART" icon) to cast in their vote. 1 user is limited to 1 vote.  Voting is currently restricted to only signed in users.

Do the options on a poll necessarily have to be a product page URL?
-----------------------
Not at all. A user can also put in free text . For example, a user on a travel portal may have a question " Which is a better destination for September?" And the options could be free text fields and he could enter " Bali" and "Maldives" as the 2 options.

How many options can a user enter for a poll?
----------------------------
Currently, a user can enter upto ``4 options`` for a poll.

How do you upvote a someone's comment or reply?
----------------------------
A user can ``upvote`` another question or comment by simply clicking the upvote button (denoted by a "HEART" symbol).  The upvote is currently restricted to signed in users only . 1 user is limited to 1 upvote per comment/question.

How can one reply to a question posted on the main chat room?
--------------------------------------
To reply to a question /poll posted , a user simply has to click on the ``COMMENT`` bubble on the right  and respond directly to it. All responses get threaded within.

Are users allowed to report a comment they find offensive or inappropriate?
--------------------------
Yes they can.  For every comment posted on the main chat room or in the reply section, there is a Flag button (depicted with an "Exclamation" image) that a user can click. Upon clicking, he or she can choose the reason as to why it is inappropriate .

Once reported, you will see this comment on your Client Dashboard.  All you need to do is ``ACCEPT`` the Flag (if you want to remove the respective Flagged comment from the Chat window) or ``REJECT`` it (if you want to allow the comment). If you ACCEPT the flag, it will automatically disappear from the Chat Window.  This ensures that moderation is managed.  




Contact
===================
.. toctree::
   :maxdepth: 6

The best way to get in touch with us is by email! Just shoot us one at ``hello@yhatch.com`` and we promise to get back to you within 24 business hours.  You can also call us at ``+91 9900 354400`` for any queries (M-F, 9am to 6pm).


ADMIN LOGIN
**************



