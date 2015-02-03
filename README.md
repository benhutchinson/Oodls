[oodls : Waste Food Project](http://www.oodlsio.herokuapp.com)
==========================

[![Code Climate](https://codeclimate.com/github/Callisto13/Oodls/badges/gpa.svg)](https://codeclimate.com/github/Callisto13/Oodls) [![Test Coverage](https://codeclimate.com/github/Callisto13/Oodls/badges/coverage.svg)](https://codeclimate.com/github/Callisto13/Oodls)

This was our final two-week challenge at Makers Academy.  We sought to create a web application to connect individuals with surplus food to those local charities and organisations in need.  This was a [team challenge](#team) drawing on an initial idea from [Claudia Beresford](https://github.com/Callisto13) and [the original project is hosted here on Heroku.](http://www.oodlsio.herokuapp.com)

###Index Of Contents
- The Cause : Resources
- The Cause : Some Killer Stats
- Our Minimum Viable Product & Basic User Story
- Sites With Similar Functionality
- Key Design Considerations
- Stretch Goal Features & Ideas
- Why Would You Integrate Tesco Into A Charitable Platform?
- Team Policies
- Team Members
- Technologies

<p>
<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/presentationfront.png">


###The Cause : Resources
Here are some links that give further background on the topic.  I have summarised some of the key points from the House of Commons report in [a separate page here.](https://github.com/benhutchinson/Oodls/blob/master/NotesHouseOfCommons.md) but also extracted some statistics that caught my eye from the sources below.
* [FareShare](http://www.fareshare.org.uk/)
* [FareShare Food Guidelines](http://www.fareshare.org.uk/wp-content/uploads/2014/12/Food-offers-Guidelines-2014-15.pdf)
* [FoodCycle](http://foodcycle.org.uk/)
* [2015 House of Commons Environment, Food and Rural Affairs Committee Report: Food security: demand, consumption and waste](http://www.publications.parliament.uk/pa/cm201415/cmselect/cmenvfru/703/703.pdf)
* [2010-2012 Food Waste Bill](http://services.parliament.uk/bills/2010-12/foodwaste.html)
* [Love Food Hate Waste](http://england.lovefoodhatewaste.com/node/2472)
* [Tesco Food Collection](http://foodcollection.tesco.com/#donate-in-store)


###The Cause : Some Killer Stats
* Almost 50% of the total amount of food thrown away in the UK comes from our homes.  Each year a consumers, we throw away 7 million tonnes of food and drink from our homes in the UK.  More than half of this is food and drink we could have eaten.  We throw away more food from our homes than packaging in the UK every year and an area almost the size of Wales would be needed to grow all of the food we throw away each year. (Source: [Love Food Hate Waste](http://england.lovefoodhatewaste.com/node/2472))

* FareShare provided 13.2m meals last year and state that over 82,000 people benefit from FareShare food per day.  They believe the beneficiary charities that they serve saved costs of around £13k as a result.  Despite this, they believe that they are currently handling just 1.5% of surplus food available in the UK.  They believe that c800m meals could be provided having assessed food wasted and a proportion that is fit for consumption.

* Positive Trends: [According to Love Food Hate Waste](http://england.lovefoodhatewaste.com/node/2472)), between 2007 and 2012 avoidable food waste has been reduced by 21%, equivalent to over 1 million tonnes.  [Tesco's national collections](http://foodcollection.tesco.com) have grown in size.  November 2014 was their fifth collection and raised 4.7 million meals vs the first in December 2012 which raised 2.4 million meals.

* More.  Per the above, I have summarised some of the key points from the House of Commons report in [a separate page here.](https://github.com/benhutchinson/Oodls/blob/master/NotesHouseOfCommons.md) 


###Our Minimum Viable Product & Basic User Story
An individual consumer with spare food to donate should be able to visit our site, enter a post-code, and then be presented with a list of local charities that would accept their food.  The applicable charities' locations should be clearly presented and sorted according to their proximity, with some parallels to the likes of [Freecycle](https://www.freecycle.org/), [Freegle](https://ilovefreegle.org/), and [Gumtree.](http://www.gumtree.com)  [Full wireframe graphics illustrating our user story & graphical user interface design plans can be seen here](https://github.com/benhutchinson/Oodls/blob/master/ideas.md#gui--user-story) along with [Claudia's more extensive, original MVP here.](https://github.com/benhutchinson/Oodls/blob/master/mvp.md)  A scaled down version of our user story is shown below.

<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/smalluserstory.png">


###Name, Branding & Promotion Ideas
We were keen to almost gamify the topic and brand through an animal character to engage people of all ages.  Meercats have little to do with insurance but are memorable.  Oodles the Owl, Foodles, Share Bear, Town Mouse vs Country Mouse, seemed to be some of the key ideas that grabbed us, with oodles seeming the most catchy.  The name became Oodls following domain name considerations.  [Alan's initial draft logos can be viewed here.](https://github.com/benhutchinson/Oodls/blob/master/ideas.md#logo-iterations) 


###Screenshots : The Final Product
Our final product placed Google Maps at the centre of the user experience.  A user can enter any post-code or allow our site to access their current geolocation and upon submit, be presented with a full-size map illustrating local charities and Tesco stores (more to come) that would accept their produce.  Charities are denoted by "Oodls" owl pins, while Tesco stores are distinguished through the Tesco logo.  On clicking a charity pin, a user is presented with an info-window outlining opening hours, the key products that the charity is currently accepting, and links to a more detailed charity profile page.  The pin also links neatly to Google Maps externally should a user need directions and wish to take advantage of varied forms of transportation.  Tesco pins offer the very basics of Tesco's scheme and provide a link to Tesco's Food Donation literature.  The design of the app is responsive hence renders nicely on mobile devices and is integrated with both Twitter and Google Analytics.  


<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/charityscreen.png">


<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/tescoscreen.png">


<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/twitter.png">

<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/twittercard.png">



### Why Was Tesco Integrated Into A Charitable Platform?
Tesco actually hold over 350 permanent food collection points across many of their stores in the UK linked to FareShare and The Trussell Trust.  At these stores, consumers are welcome to donate food items of any brand (including competitors) from the pre-approved lists below with the produce ultimately distributed to the foodbanks.  Tesco also top up these consumer donations with money and state that their alliance with FareShare has helped provide the equivalent of seven million meals a year of surplus food.  Tesco themselves divert all surplus fresh food from their distribution centres and online grocery centres to FareShare, adding more fresh produce such as chicken, peppers, apples and other fresh fruit and vegetables.

<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/tesco_fare_share.png">
<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/tesco_trussell_trust.png">



### Why The Tesco Data & Scheme Is Important
As the precise data regarding those 350 Tesco collection points is a little scattered and/or non-existent, we contacted Tesco's customer service and investor relations teams to collect the store data.  To their credit, they supplied us with this and hence we were able to translate the post-codes into co-ordinates and pins on our map.  We saw this as important for the following reasons.  


Firstly, supermarket hours can be more consistent and extensive, the network of drop-off points is broad, the immediate beneficiaries are Fareshare and The Trussell Trust, and we have the data on-hand (!), this feature may be sensible to integrate.  It would be of use to those donors who have the will but are simply time poor.  The service could be considered a little analogus to Amazon's locker service and would ensure our platform is immediately populated with over 350 legitimate drop-off points that a donor could visit today.  Over time, there would be nothing stopping us from integrating other commercial entities that partner with foodbanks.  We could even provide a registration facility for this, recognising that many supermarkets determine their relations with local foodbanks at the regional store-level and hence the data-set is just more fragmented when compared with Tesco.  We could allow this facility to be turned on/off should a commercial provider have a change of policy or a donor have a preference to support different institutions.  We could also deploy customised marker icons so that users could clearly identify the type of drop-off points on the map.




###How We Could Extend & Take This Project Forward
- [Tesco have a Food Collection Programme](http://foodcollection.tesco.com/#donate-now) that is well-integrated with their nationwide store network.  Provided consumers offer items from those lists copied below, it is "really easy to donate in store" by leaving those products at Tesco's "permanent collection points" in their stores.  Tesco have confirmed to us that these items need not necessarily have been purchased in Tesco and hence a consumer is currently allowed to donate and deposit any produce or any brand that meets the conditions of the list.  Tesco does not publish an easily-accessible list of those stores that offer the foodbank collection point service on their web-site, but following contacts with Investor Relations and Customer Services, they did provide us with a CSV file populated with appropriate store post-codes.  Those stores aligned to [Trussell Trust are published on the Trussell Trust web-site](http://www.trusselltrust.org/resources/documents/Store-List-2014-November-National-Tesco-Collection.pdf) and Fareshare was also able to provide us with a list off-line.  We think we should be able to integrate this network so that consumers could find convenient locations near to their home or work, making it easier for them to donate spare food.
- We could offer our unique and evolving data-set in the form of a RESTful API. 
- We could allow users to perform more filtered searches, according to opening hours or the types of produce they hold for example.
- The site could be easily shared hence we could integrate with Twitter, Facebook, etc.
- We could integrate pages that quickly outline the cause to help raise greater awareness of both individual responsibility and the easy practical actions that individuals can take.
- We could develop admin functionality allowing admin users to more easily manage the site, quality-control listings, and monitor any abuse of the service.
- We could allow individual donors to register.  Our MVP system does not track actual donations and hence it is hard to proxy the effectiveness of our campaign, the incremental donations it engenders, and incremental foot-fall that Tesco would receive.  If we could track individual donations more tightly, potentially we could integrate merchandise, rewards, stickers, badges, etc.  This would facilitate individual charities to contact those that have donated to them in particular times of need or to simply market their cause.  We could also develop a 'live map' showing donations as and when they occur.
- Could our system be designed such that it is more closely integrated into a transportation service such as a Boris-Bike or Uber-type infrastructure?  Could we go further to integrate donors, their donations, the destinations and the prevailing transport network?
- [Crisis](http://www.crisis.org.uk/) on Commercial Street work with FairShare and maintain Daily rather than static menus, partly to reflect some of the diversity in the donations they receive.  This could offer inspiration for a cook-book since it requires them to be consistently inventive in using up whatever produce they have to hand.  [FoodCycle](http://foodcycle.org.uk/recipes/) have something a little like this on their web-site and even have recipes from celebrity chefs such as Ken Hom.
- Hotel & Corporate Waste could be another future donor-base to target.
- [Love Food Hate Waste have a mobile app](http://england.lovefoodhatewaste.com/content/download-new-love-food-hate-waste-free-app) that has some synnergies with our idea.  This also links to the API idea above.

We want charities to be able to engage with this platform.  We must consider the technology they may use to access our app and hence accessibility will be one of the central challenges of our design.  [Modernizr](http://modernizr.com/) may be useful in dynamically checking browser support and hence conditionally including CSS and Javascript features.





###Team Policies
We all got in for 9.30am and started the day with a 'stand-up' meeting and took lunch as a proper break around 12.30.  We aimed to follow test-driven-development philosophies where it was possible and sensible.


[](#team)<a name="team"></a>
###Team Members
- [Claudia Beresford](https://github.com/Callisto13)
- [Alan Bridger](https://github.com/abridger)
- [Izzy Markwick](https://github.com/imarkwick)
- [Ben Hutchinson](https://github.com/benhutchinson)

###Technologies
- [The basic Powerpoint slides illustrating the technologies are here](https://rawgit.com/benhutchinson/Oodls/master/public/v1presentation.pptx).  The key slide is copied below.  It clusters the design/front-end technologies, external platforms/APIs, and database-security technology as appropriate, with Rails acting as the conductor at the core.
- Rails, Ruby, Rspec
- Foundation
- Google Maps API & Gmaps.Js
- Adobe Illustrator

<p>
<img src="https://raw.githubusercontent.com/benhutchinson/Oodls/master/public/images/technologies.png">
