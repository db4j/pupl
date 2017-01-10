# PUPL - Payed Use Permissive License - FAQ

### are you a lawyer ?
no

### how do i apply this license ?
choose a strike price.
this is the maximum that anyone will ever need to pay you to use your software on 1 core for 1 year.
add a header to your software stating the license and strike price, eg "this software is licensed under the terms of the nqzero PUPL, with a per-annum strike price of $100".
you should be prepared to meet the assurances, eg to publish full prices and issue licenses


### is this license an open source or Free Software (FOSS) license ?
no.
please don't refer to this license, or to software licensed under it, as either.
it's possible that with a strike price of zero it would be, but in this case it would be better to use an established FOSS license instead


### has a lawyer signed off on this license ?
no.
when i get the general idea hashed out i may pay a lawyer to look at it.
i guess my inspiration is the json license - it's plain english
("The Software shall be used for Good, not Evil")
[was good enough to get IBM to "negotiate"](http://dev.hasenj.org/post/3272592502/ibm-and-its-minions)


### why not free or open source software ?
i wrote a database engine and i'm hoping to use this license for it

i invested and continue to invest a fair amount of time and money in creating the database, in the hope of making money. for some products, open source can be a profitable path, eg by charging for support or hosting the software or as marketing for consulting services. however, for some useful products, these paths don't seem to work well even though the software product is widely used. this license is an assurance that if my software is widely used, i'll make some money

further, it enables me to develop the software to maximize usefulness, as opposed to maximize the need for support services or some other indirect path to profit

i don't know that this license is the right one, but i feel there exists potential for a license in this space
that balances creator profits with user freedom and would be mutually beneficial


### why not a (traditional) proprietary license ?
this topic has been discussed at length in the FOSS literature so i won't rehash it all here.
but personally, i avoid software under such terms because of the danger of lockin and the lack of source code.
in spite of these risks, i did purchase and use jetbrain's Webstorm, and wasn't happy when they changed their terms.
part of my inspiration for this license was shaped by trying to prevent the sort of thing that happened with jetbrains


# licensing for derivative works

### can i make a derivative work with the new portion licensed under the MIT license
- yes, and this is also true for similar (GPL-compatible) licenses such as the Apache License
- tell the recipient about the copyright and license terms

### can i make a derivative work with the new portion licensed under this license
- yes
- tell the recipient about the copyright and license terms
- if you charge a user for a use-license, you need to verify they have one from the original work
- users may use any non-zero-cost use-license to satisfy this requirement
- you can buy use-licenses for the original and transfer them to a user

if you wish to hedge against price increases, you may wish to purchase a number of full price use-licenses, which you can then resell. either way, you and your customers are protected by the strike price

you can also contact the developer and negotiate other terms for your specific case

### can i make a derivative work that's closed source
- yes
- tell the recipient about the copyright and license terms
- you'll need to verify the user has a use license or buy one for them
- see above



# Risks and protections for users that adopt software licensed under these terms



### if my business adopts software under this license, can the price increase later (if my usage stays the same) ?
- if you pay the full price, then each year you use the product you'll pay that same price (even with lapses)
- if you pay the lifetime price, then you don't have to pay again
- if the vendor offered a sale price, then the sale price may increase



### if my usage of software licensed under these terms increases, will additional use-licenses cost more than i paid initially ?
in general, the price may increase. however, a few rules exist to protect you if you scale
- you'll never pay more than the strike price for a per-annum use-license, or 10 times that for a lifetime
- if you paid full price for a per-annum (without lapses) or a lifetime use-license, you're entitled to purchase 4 additional use-licenses at that same price
- price changes must be announced a month in advance
- full price licenses are transferable, so you could buy existing use-licenses from someone that is no longer using it
- 3rd parties can make derivative works that are more efficient, allowing your current licenses to process more data


### should my company (an end user) pay full price or the sale price
if you think that you're likely to use the software long term, then you may want to pay full price. your investment in learning the software and building tools upon it is probably higher than the full price, and paying full price means your price won't increase and hedges against future scale. it will also help pay for future development, which you may want to encourage



### if i buy a version today, how does this license protect against price increases of future versions ?
a full price license entitles you to use any version released in the next year, so short term this offers some protection
also, much like FOSS, 3rd parties can develop similar functionality as those future versions based on the current version and compete with the upstream. this competition should help limit the price increases to real value added in future versions

a full price lifetime use-license can be upgraded to a later version. the greater of the price you paid and the current price of your version will be credited towards the full price for the new version


### doesn't this license encourage you to make your software inefficient so it uses more cores ?
again, much like FOSS, 3rd parties can develop (and profit from) more efficient implementations and compete with the upstream. this competition should result in efficient implementations

you can apply an existing use-license from the developer to your use-license requirements for a derivative work if any of the following are true:
- your use-license was purchased at non-zero cost
- the derivative is open source
- the derivative is your own work
- the derivative is licensed under this license at no per-use cost to you


note: in some cases, the 3rd party may charge for their version



### can you give an example of an upgrade scenario
in 2016 you pay $10 each for full price per-annum use-licenses. in 2018, that price increases to $50 and a new version is released with a full price of $80. you upgrade to the new version and pay $40 each - $10 for your lock-in price, plus $30 for the difference between the old and new version


### can you give an example of scaling my usage
in 2016 the (sale/full/lifetime/strike) prices are $0/$10/$100/$100 and you pay $10 each for 100 cores, locking in that price. in 2017 you pay $1000 to renew those licenses. in 2018 your company grows and you need 200 cores, but the prices have increased to $50/$50/$200/$100. you've had no lapses, so you're able to purchase the additional cores at $10 (your lock-in price) per-annum. if you'd used the sale price (paying $0 in 2016 and 2017), you'd have to pay $50 per core in 2018

note: this is an extreme example and i don't expect to increase prices this quickly


### why not just use a fixed price ?
initially, the ecosystem for this software is limited and early adopters are taking risk. the non-fixed price allows me to offer the software at a price that reflects the current utility and risk without limiting my ability to charge a higher price (more reflective of the total investment and true utility) later as the utility increases and the risk decreases. it also rewards early adopters


### why are non-production usages free ?
it's an arbitrary line, but:
- using the software to prototype new projects, learn how to use it, teach it to others, benchmark it, and test it helps adoption
- non-production uses don't necessarily indicate utility
- an organization using the software in production, and wishing to stop using it, might need to run extra instances of it to develop or test compatible systems. being able to reverse engineer the software is an important freedom and limits the negative effects of lockin

there's no perfect answer on where to draw the line, but this is a decent compromise

### what counts as production use of the Software ?
The central idea is that the software is used for the sake of the data that it produces, manipulates or stores. examples include a web server accessed on the internet, an internal app employees use to record timesheets, and a GUI that helps visualize data from a database

some examples of non-production uses:
- prototyping a new system, where the output data is not used directly
- learning to use, or teaching others to use, the Software
- benchmarking or testing the Software or systems built with it
- reverse engineering the Software so that a compatible system can be built


### are there any known flaws with this license
note: this refers to flaws in the license, not flaws in software that has been licensed with it
- IANAL
- i'd like to offer current users stronger protection, eg unlimited scale,
but can't figure out how to do that without being effectively fixed-price
- the license is too long


what are the goals of this license ?
 - provide end users and ISVs with predictable future costs
 - provide the developer with income if the software is widely used
 - encourage development of useable software, vs tools that will drive support-based income



copyright nqzero 2016
