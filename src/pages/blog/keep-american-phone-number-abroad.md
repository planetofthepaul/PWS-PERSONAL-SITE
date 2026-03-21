---
layout: ../../layouts/BlogPost.astro
title: "How to Keep Your American Phone Number When You Move to Spain"
description: "If you're moving abroad and need your US number for two-factor authentication, here's the exact setup that's working for me right now in Spain."
date: 2026-03-21
---

**TLDR:** If you're worried about Google Voice not delivering 2FA codes from your bank, the solution is [Tello Mobile](https://www.tello.com). Port your US number to Tello, turn on Wi-Fi Calling, and pair it with a local carrier for data. It costs $8/month and it works. Full details below.

---

Packing your life into suitcases for a move to Spain is stressful enough without worrying about your digital life collapsing the moment you land.

If you're reading this, you're probably in the same boat I was in a few weeks ago. I was about to make the move, and frankly, I was freaking out.

Sure, I was excited for tapas and a new life, but practical reality was kicking in. My inbox was filling up with questions from friends and family: "How will we call you?" "Are you going to have a weird number?" "Does it cost money for us to text you?"

But the real panic set in when I thought about security. How was I supposed to log into my bank or access my investment accounts without getting those required 2 factor authentication (2FA) text codes? In 2026, if you lose access to your US text messages, you are essentially locked out of your financial life.

I spent weeks spiraling down Reddit threads and scouring expat forums.

## My first failed attempt: Google Voice

I originally thought I had found the perfect free solution: Google Voice. You port your number to Google, and you can get calls and texts through an app. Perfect, right?

Wrong.

While Google Voice is great for talking to your mom, I quickly learned it has a fatal flaw for expats: many US banks and financial institutions will not send 2FA text codes to VoIP numbers. Google Voice is a VoIP (Voice over Internet Protocol) number, not a true wireless number.

If you rely on Google Voice, you might find yourself in Spain, trying to pay a bill, and unable to get the code to log in. This was a risk I wasn't willing to take.

## The strategy: two lines, one phone

You can run two eSIMs on the same phone. One is your US number. One is a local Spanish carrier for data. The Spanish data connection powers Wi-Fi Calling on your US line, so your American number works for calls, texts, and 2FA as if you were still in the States. The total cost is about $8/month for the US line plus whatever you pay for a local Spanish plan.

## The solution: Tello Mobile + a local Spanish carrier

After endless research, I found the setup that actually works. Both lines run as eSIMs on my iPhone. No physical SIM cards involved. Here is exactly how I did it.

## Phase 1: Preparation (1 to 2 weeks before the trip)

You need to set up your "anchor" while you are still standing on American soil. This is non negotiable for success.

### Check your phone

You must have an unlocked phone that supports dual eSIM. Most recent iPhones don't even have a physical SIM slot anymore. They run two eSIMs natively. If your phone is still on a payment plan with your current carrier, call them and confirm it is unlocked for international use.

### Sign up for Tello Mobile

Tello is a budget US carrier that runs on the T Mobile network. Their plans are highly customizable, which makes them perfect for expats.

1. Go to the [Tello website](https://www.tello.com)
2. Choose their custom plan. I selected no data and unlimited minutes. This costs me $8 a month. You don't need any data on this line. Your local Spanish SIM handles all your data.
3. Choose the eSIM option
4. Initiate the porting process to move your existing US number to Tello. This usually takes a few hours.

### Crucial settings while still in the US

Do not skip this. Once your Tello eSIM is activated on your phone:

**Activate Wi-Fi Calling:** Go to Settings > Cellular/Mobile Data > Tello > Turn on Wi-Fi Calling.

**Confirm 2FA works:** Try to log into your bank. The code should now arrive via your Tello number on your phone.

## Phase 2: Landing in Spain (arrival day)

You don't want to be wandering around the airport trying to figure out connectivity while fighting jetlag. For the first couple of weeks, I'm using [Airalo](https://www.airalo.com). It's a travel eSIM app that gives you instant data the moment you land. Buy a Spain specific data package before you leave (maybe 10GB for 30 days). It's a stopgap, not the long term solution.

### Phone settings upon arrival

As soon as the plane wheels touch the ground:

1. Turn off Airplane Mode
2. Go to Settings > Cellular
3. Set Tello as your **Default Voice Line** (but ensure Data Roaming on Tello is **OFF**)
4. Set your data eSIM (Airalo for now) as your **Cellular Data** line. Tap "Cellular Data" at the top of the Cellular settings screen and select the Airalo line.
5. Make sure **Allow Cellular Data Switching** is turned **OFF**. This is important. If you leave it on, your phone might try to use the Tello line for data, which you don't want since Tello has no data plan. Turning it off forces all data through your Airalo (or later, Spanish carrier) line only.

**The magic:** Because your phone has a Spanish data connection and Tello Wi-Fi Calling activated, your Tello line will treat the data connection like Wi-Fi. Your US number stays fully active for texts and calls.

Your phone will show two distinct signals at the top. You will be walking through Spain, using local data, but you will receive texts from American friends and 2FA bank codes instantly and for free.

## Phase 3: Getting a local Spanish carrier

I've been here a few days and Airalo is doing the job for now, but it's expensive for long term use. The next step is getting a local Spanish prepaid plan. I've heard Digi Mobile has solid prepago deals for around 10 to 15 euros a month with a ton of data. I'll update this post once I've set that up.

The final phone configuration should look like this:

- **Tello eSIM:** For US calls and texts. Data Roaming OFF, Wi-Fi Calling ON.
- **Spanish carrier eSIM:** For all your data. Set as the Cellular Data line. Allow Cellular Data Switching OFF.

## What I can confirm so far

I've only been here a few days, but the Tello setup is working exactly as promised. My family texts my American number like I never left. I call them from Spain on the same number. When my bank sends a 2FA code, I get it within seconds. My WhatsApp still runs on my US number.

For $8/month, it's the best peace of mind I've bought for this entire move. If you're moving to Spain, or anywhere abroad, you can take your chances with Google Voice or spend like $8 a month on Tello.

I'll update this once I've sorted the local carrier situation.
