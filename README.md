# Polarscale

Polarscale is an Interconnected Smart Scales system that collects, organises, and analyses data on a restaurant's waste production patterns, presenting intuitive real-time analytics on their waste through a user-friendly application.

The target audience for these scales are small to medium restaurants, where it would be too costly to manually monitor waste production

## So how do these scales work?

A restaurant may use any number of smart scales depending on the types of waste they want to monitor. For example, a restaurant can order 3 scales, and use the web app to label each scale with the following categories:

* Kitchen waste
* Guest leftovers
* Bones

Once installed in the restaurant, the scales will automatically communicate data about each waste category to a cloud service. The service would then store the data, and deliver real-time analytics straight to the restaurant through the app's dashboard. The dashboard would communicate information such as:

* Hourly total waste for each category
* Cumulative waste production in longer term time brackets (weeks, months or years)
* Much more! It all depends on what the restaurants need to know.

## So how do these scales help restaurants?

Restaurant owners and chefs can open the app at any time, check the dashboard and get instant answers to questions like:

* How much kitchen scraps have we thrown out during today's service?
* Are we within the maximum waste limit during today's prep?
* Are we creating more or less waste compared to last year's peak season?
* Which kitchen staff could improve in reducing their waste production?
* Are guests enjoying the new menu, and finishing their plates?
* Has our new menu design successfully reduced kitchen waste?

It is important that these questions are answered quickly, cheaply and accurately, so that chefs can spend more time innovating creative solutions, and less time performing manual data work.

We genuinely felt that there was potential to make a difference with our smart scales system. These scales could empower every restaurant with the information they needed to cut wasteful costs, and help create more sustainable businesses.

In addition, an important benefit of delivering real-time feedback of current waste production levels, was to induce behavioural changes in kitchen staff when prepping for service. A key observation restaurant Nolla made while we were working with them, was that:

They achieved a 50% reduction in overall waste when waste production became a factor in staff performance reviews.
The cumulative impact of small incremental choices can make a big difference. So our smart scales system would help foster the necessary routine & habit changes that can cut down on waste.

Finally, we felt that in order for our scales to be competitive, they needed to be cheap, low-profile and easy to install. So we worked on making the interface as intuitive as possible, and used existing off-the-shelf components to build our scale prototypes. This would make it easy to seamlessly fit our system into any restaurant operation.

## Demo 

A video demo of the scale system can be found here: https://youtu.be/yfWBuD8OQEE 

In the demo, you'll see 2 scales collecting data about "cardboard & metal" and "plastic" respectively. It demonstrates data of these two waste categories in the following maner:
* Real-time live totals of each waste category from the last 1hr to 24hrs.
* Cumulative and daily totals for the last weeks, from 1 week to 4 weeks.

## Client

Built on top of a react framework, the project structure is fairly simple. Instructions for setting up the project can be found at this [README](https://github.com/Caruychen/polarscale-demo/blob/main/client/README.md)

## Server

Technically, the backend uses serverless functions deployed on Supabase. Supabase edge functions run on deno, so we avoid using npm package installs. 

A detailed guide on getting serverless functions running on Supabase can be found here: https://supabase.com/docs/guides/functions/quickstart
