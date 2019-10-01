==========================================
Recruiting talent via the PyBites CodeChallenges Platform
==========================================

PyBites CodeChallenges allows you to run your own Python based coding interviews using your own custom Bites (exercises) or from our library of Bites.

Starting with why
-----------------

For some background on this technology / tier, read our article: `Why whiteboard interviews suck and what we’re doing about it <https://pybit.es/whiteboard-interviews.html>`_.

Pre-requisite
-------------
You have to be signed up to our platform with a username/email, or with a Github Account: `<http://codechalleng.es/signup>`_. Make sure you confirm your email as this is required to register a license key.

In this helper doc we have 3 users: Tim is a recruiter and Sara and Ramit are interviewees. We will show you how to set up an interview Bite as the recruiter; send out private interview links (tokens) to the interviewees and watch their submissions.

Register your license key
-------------------------

After buying a license key from our `Enterprise pricing page <https://codechalleng.es/bites/pricing/enterprise>`_ register it under `Settings <https://codechalleng.es/settings/>`_ or with the direct purchase link provided in the purchase email (e.g. `<https://codechalleng.es/purchase/access_code/PB-U8N435EH-PG65PW87-IXPWQG5T-898XSZI4>`_).

.. image:: https://user-images.githubusercontent.com/387927/58949336-79ca8f00-878c-11e9-9ede-ce5d9377720d.png

You'll then receive a confirmation/welcome message in the Messages section of the platform:

.. image:: https://user-images.githubusercontent.com/387927/58949488-e2b20700-878c-11e9-8a90-ff133a8a6f13.png
   :width: 600

Click the settings link in the message and you'll be presented with the following screen showing your license keys and the amount of interview tokens purchased:

.. image:: https://user-images.githubusercontent.com/387927/58949647-391f4580-878d-11e9-9e35-a19786b9c464.png
   :width: 600

Your own space on PyBites
-------------------------

At this point you need to set a *company slug* for your Interview Bites. Consider it your private corner in the PyBites universe. As we're movie fans let's call our slug *nolan*:

.. image:: https://user-images.githubusercontent.com/387927/58949996-06c21800-878e-11e9-9818-6d5edead7b39.png
   :width: 600

At this point you'll see your private *Interview Bites* link in the sidebar. Click on it or on the *Manage your interview bites* button while still in Settings:

.. image:: https://user-images.githubusercontent.com/387927/58950152-5bfe2980-878e-11e9-8036-7b9338617fdf.png

You can see the amount of Interview Bites available on your account (currently 1 for each 50 purchased tokens).

Add Interview Bites
-------------------

You can add a new Interview Bite by clicking the *Add new Bite* button:

.. image:: https://user-images.githubusercontent.com/387927/58950208-80f29c80-878e-11e9-9d3b-46b58345e042.png

.. image:: https://user-images.githubusercontent.com/387927/58950222-89e36e00-878e-11e9-86bc-e85cc1a9416d.png

As you can see we support quite a few external libraries for you to use. You can also hide the tests to potentially make it more difficult and (exciting!) you can set a deadline in minutes to make it even more tough!

Copy our Bites
--------------

If you don't want to write your own Bites you're able to use our existing Bites for interviewing purposes.

After the previous setup you should see a *Copy this Bite* button on individual Bite pages.  (Note: Intro Bites are not included)

.. image:: https://user-images.githubusercontent.com/387927/58950357-e2b30680-878e-11e9-81a1-01f73e5bf810.png

Here we've navigated to Bite 2 which has some kick-ass regex problems for the candidate to solve. Notice the "Copy this Bite" button. Click it.

The Bite is now copied to your private Interview Bites!

.. image:: https://user-images.githubusercontent.com/387927/58950417-070ee300-878f-11e9-929d-77514c73f530.png

Click on "Edit / Publish" to make any changes. Here we update the title and toggle "Published" to on:

.. image:: https://user-images.githubusercontent.com/387927/58950485-332a6400-878f-11e9-8db0-9bc34f4ee0de.png

2 new links now appear on the Interview Bites page: *Submissions* and *Manage interview tokens*:

.. image:: https://user-images.githubusercontent.com/387927/58950589-6cfb6a80-878f-11e9-87d8-e234cb03d073.png

Interviewee links
-----------------

Click on *Manage interview tokens* to generate private interviewee links (tokens):

.. image:: https://user-images.githubusercontent.com/387927/58950642-8e5c5680-878f-11e9-8b4d-eebbc1c7acce.png

Let's generate 20 interview links for this one:

.. image:: https://user-images.githubusercontent.com/387927/58950657-961bfb00-878f-11e9-9dac-14c9acce4cbc.png

.. image:: https://user-images.githubusercontent.com/387927/58951306-11ca7780-8791-11e9-8c16-fe1f27575e9d.png

The balance goes down by 20. Token spots can be recovered by deleting them. **Tokens are only consumed when interviewees  redeem the links**.

For example, here we delete 3 tokens, recovering some of the balance:

.. image:: https://user-images.githubusercontent.com/387927/58951340-260e7480-8791-11e9-91a7-047462aecf9d.png

Interviewing people
-------------------

Let's send Ramit and Sara an interview link. Click the copy button on the first two token rows.

Sara enters the interview token in her browser and is presented with our typical Bite interface: 

.. image:: https://user-images.githubusercontent.com/387927/58951377-40485280-8791-11e9-9090-0bc265024b8d.png

To show you that each token is unique to an interviewee here is what happens when Ramit redeems the same link:

.. image:: https://user-images.githubusercontent.com/387927/58951555-b51b8c80-8791-11e9-96cd-ea4850cf1864.png

Let's compare this with the timer view. Tim has set 60 minutes on the Bite. Now, let's get Ramit to open the Bite:

.. image:: https://user-images.githubusercontent.com/387927/58951697-14799c80-8792-11e9-8037-e31e436a0f7e.png

He now has a timer!

Refresh the page as Tim (the Recruiter) and you can see the tokens being redeemed:

.. image:: https://user-images.githubusercontent.com/387927/58951762-3c690000-8792-11e9-9587-e5f917c7be4a.png

Interview submissions
---------------------

Fast forward a bit, this is what the Interview Bites page looks like after Sara and Ramit submit some code:

.. image:: https://user-images.githubusercontent.com/387927/58952334-afbf4180-8793-11e9-9705-da9f71e3598e.png

You can see their final code and last submits. Interview Bites are not scored at this point but you see some emojis if a timer was set and the deadline was hit or missed.

Download interview data
-----------------------

There's also a download feature to ensure you don't lose any data upon deleting Interview Bites. This will be necessary to free up Bite slots on your license (currently you get 1 for each 50 purchased interview tokens).

To download a zip file with all the interviewee's submissions just click the button on the Bite:

.. image:: https://user-images.githubusercontent.com/387927/58952399-e39a6700-8793-11e9-92fc-73e80b79ed86.png

Feedback
--------

We hope this new way of interviewing (pre-screening) makes the hiring process more agile and will save you a lot of time. As always we're very open to your feedback to make the platform better, just ping us `on the platform <https://codechalleng.es/inbox/new>`_.
