# Realistic Rifts

This is some work to make Palladium Books' Rifts™ environment more realistic. While Kevin Siembieda has created an interesting world full of adventure possibilities, it has its flaws, many of them based on decades-old understandings of how things do or could work, with an unhealthy dose of sci-fi movies thrown in. The following provides some optional concepts based on real-world physics and economics that could help your players better understand their world.

# Physics

## Fusion reactors

The books all say that various things are powered by fusion reactors, so their range is unlimited! (I stole the exclamation mark from Kevin Siembieda's overuse of them. I don't think he'll miss it as there are about 12 billion more in the pile I found that one.)

This is, however, unrealistic. While fusion reactors offer almost unbelievable energy density, they still require fuel. What's more, at the time that Kevin wrote Rifts, the types of fuel were largely exotic: deuterium, tritium, and Helium-3. Deuterium is easy enough to get, given enough water. But we're talking about processing 41 million liters of water to get one liter of heavy water, which yields only 1.1 kg of heavy water. Of that, only 220 grams is deuterium. While that 220 g can produce a lot of energy, sourcing the deuterium is unrealistic for how many people need it. Tritium and helium-3 are even worse. Tritium is highly radioactive with a half-life of only 12 years, meaning it's hard to store for any length of time and still have it be pure. Helium-3 is exceptionally rare, virtually unknown on Earth except in specific kinds of fission-based nuclear reactors which rely on highly-processed uranium or plutonium, which require enormous mining resources in dangerous places (within the Rifts world), so it's unrealistic that they would exist in any number. (Helium-3 is available on the moon in vast quantities, provided you can process several billion tons of lunar regolith, but very few people on Rifts Earth have any chance of getting into space, let alone to the moon.) None of this gets into the magnetic fields required to confine plasmas proposed for most of these and how they would fare in combat.

So what's left? [Aneutronic fusion](https://en.wikipedia.org/wiki/Aneutronic_fusion) using common materials and laser confinement. In this case: proton-boron fusion. It has a relatively low radioactivity level, uses common materials, and with laser confinement can reasonably be useful in a combat scenario. For comparison, 12 grams of fuel (one gram of hydrogen and 11 grams of boron) would produce about the same amount of energy one could get from a very efficient turbine burning about 10,000 liters of jet fuel.

-   Fuel: Hydrogen that can be sourced from water and boron is available naturally in the form of borax in borax mines around the world, with lots of industrial uses. We can figure that purification issues through chemistry for boron are solved at an industrial scale.

-   Energy production: The reactor vessel captures the light from [bremsstrahlung](https://en.wikipedia.org/wiki/Bremsstrahlung) and also uses an electromagnetic field to capture ions and directly convert their energy to electricity. Some X-ray radiation (see next section) is also converted to electricity by hitting conductive plates and energizing them.

-   Radiation: P-B fusion, as we'll call it, does have some issues with low levels of neutron production and some X-ray production. The X-rays are handled by conductive layers around the reaction chamber that capture much of their energy with a final layer of lead that captures any that don't interact. The neutrons are handled (admittedly with a bit of hand-waving) first by reducing them by having an extraordinarily efficient process that ensures that only atoms of protium (hydrogen composed of just single protons and no neutrons, as opposed to deuterium--one proton and one neutron--or tritium--one proton and two neutrons) make it into that side of the chamber; second a magnetic isolator redirects any available alpha particles (helium-4 nuclei) from the reaction; and finally that there are some [modified polymers containing boron compounds](https://www.hindawi.com/journals/stni/2021/5541047/) and carbon nanotubes that help absorb residual radiation.

-   Ignition: As mentioned above, laser confinement works for this. A set of high-powered lasers accurately aimed at the fuel dumps a relatively small amount of energy but at an extremely high rate. A picosecond (one trillionth of a second) laser pulse generates an electron beam that strips electrons from the boron to prevent them blocking protons, a second pulse turns the protons to beam of plasma that races toward the boron, igniting the fusion reaction, which lasts for about one nanosecond. Repeated pulses can continue the reactions at high rates, enough to power sensors, flight, weapons, etc.

-   Operation: There are 5 major components for a Rifts nuclear reactor:

    -   The reactor vessel: The heaviest component where the fusion reaction takes places. Has several subassemblies including the laser assembly and the alpha diverter electromagnet.

    -   Power block: This takes in the electricity from the reactor vessel and adjusts the power to suit systems. In ground reactors, it is more generic as such reactors are usually the cores of power grids and other equipment handles transforming the power.

    -   Boron capsule: Component containing the replaceable boron fuel assembly. Boron fuel assemblies come in standard sizes based on the number of blocks contained in them. Assemblies can be rebuilt in the field with new boron blocks by experienced engineers with the proper equipment, but should really be returned to the factory for rebuilding.

    -   Water capsule/proton filter: Holds the water from which hydrogen is extracted using energy from the reactor or from batteries as well as the filters that prevent non-protium atoms from reaching the reaction chamber. One *should* only put distilled water in it (every vehicle and mech has a distilling kit, but they're not hard to cobble together if necessary), but any reasonably clean water should work in a pinch. The filter will need maintenance as soon as possible afterward, and the reactor vessel may need cleaning, something that can *only* be done at a special facility.

    -   Ultracapacitor: Highly-efficient [graphene capacitor](https://pubs.acs.org/doi/10.1021/nl102661q) that can charge in seconds (with a strong enough power source, such as another charged capacitor or another fusion reactor). This provides energy for the proton filtering and to power the lasers. (Something similar powers some robots that lack fusion reactors.)

## Weapon Sounds and Effects

### Lasers

Lasers create a cracking double-crack sound due to the laser heating the air, creating a channel of plasma that causes an outbound shockwave (think of the thunder that comes off a lightning bolt, though at a smaller scale). After the laser stops, that channel gets refilled as air rushes back in to fill the low-/zero-pressure zone. It will very often create *another* crack at the target as the surface reacts to the sudden influx of energy. If it explodes outward (which it will with enough damage), this can create a small explosion that pushes on the target. Because of the physics involved, none of this can be silenced. Be cautious when trying to use one sneakily.

[Source](https://worldbuilding.stackexchange.com/questions/33112/pew-pew-lasers-what-would-directed-energy-weapons-actually-sound-like)

### Railguns

Railguns involve accelerating a slug to supersonic or hypersonic speeds in a split second. These involve significant recoil for the size of the round, and the shockwave produced by the movement through the air creates a *very* loud crack. Because of the physics involved, this sound cannot be silenced.

# Demographics

## General Population

By the middle of the 21st century, the world's population peaked at just under 10 billion people. Of those, about 600 million were in North America. Those numbers were mostly stable throughout the following decades. But global catastrophes tend to have harsh impacts on population.

Rifts North America is, compared to 21st century North America, empty. What was once the State of Texas with more than 50 million people now has fewer than two million, and more than a quarter of that is in CS Lone Star, with most of the rest in the various minor powers that make up the Pecos Empire. Towns, such as they are, rarely have more than a few thousand people, are tens to hundreds of kilometers from each other, and are mostly self-sufficient. They grow at a decent rate, averaging about 5% per year, with differences based on trade, resources, and luck (good or bad). But that still means that a 2000-person town only picks up about 100 people per year, and simple resource shortages cause groups to move to new locations to start something new. Catastrophes such as severe weather, attacks, or rift events make things even worse. Settlements of up to a few hundred people are somewhat more common but much more fragile. What this means is that a small group of people can go a long time without contacting anyone else.

This also has the effect of reducing the average danger level. Contrary to the books, the fraction of most populations that are MD-armed/armored or have prior military service is relatively small. Nowhere has a 50% active/veteran rate, other than perhaps some conscription that doesn't go much beyond knowing how to follow orders for small-unit tactics and some basic weapons handling, and that can all be taught in a few days. The economics just don't support massive armies. Either there's more work to do or the equipment is too expensive, and for most populations, it's both. For comparison, look at the early 21st century North Korea. With a population of 28 million and 30% of its people (almost 8 million, most of it paramilitary) serving in the military, it was an economic hellhole with soldiers frequently assigned to work in factories, mines, fields, and anything else that needed warm bodies because of a lack of civilian population to perform the work. Because of this, much of the population could not achieve industrial expertise nor could it achieve military expertise.

Yes, there are bandit groups and various powers vying over resources, including land. Yes, there are abominations that come through the rifts and have to be fought off. Yes, there are Splugorth Slavers that come in (mostly in the southeast), scooping up everything that they can and killing much of the rest. But in reality, most encounters with outsiders are wary but peaceful. The danger is between towns, and that is very real. Bands of Simvan or, worse, Brodkil can lay waste to even relatively well-protected caravans. Travelers are advised to keep their heads down and their barrels out.

## Specific Populations

### Coalition States

-   Total population: about 14 million

-   State of Chi-Town: 6 million

    -   Fortress City of Chi-Town: 1.4 million

-   State of Missouri: 1 million

-   State of Lone Star: 0.5 million

-   State of Iron Heart: 2.7 million

-   State of Free Quebec: 4 million

### Others

-   Ishpeming/Northern Gun: 150,000

-   Manistique Imperium: about 720,000

    -   Manistique: 400,000

    -   Escanoba: 220,000

    -   Surrounding areas: 100,000

-   Upper Michigan (various small city-states): 100,000

-   Lower Michigan

    -   Lazlo: 1.4 million

-   Federation of Magic: ???

    -   Dunscon (City of Brass): 20,000

    -   Dweomer: 50,000

    -   Magestar: 2,000

    -   Stormspire: : 20,000

-   Tolkeen: 900,000

-   Pecos Empire: 1.4 million

    -   El Paso: 50,000 (about 20% transient)

-   Ciudad Juarez: 110,000 (about 20% transient) + 14,000 slaves

-   Iron Heart: ???

# Ecology

Much of eastern North America has been covered over again with American chestnut trees. Before [chestnut blight](https://en.wikipedia.org/wiki/Chestnut_blight) arrived in North America in the early 1900s, chestnut trees covered *vast* swaths of the eastern half of the United States. Up to 25 meters tall and sometimes up to 60 cm in diameter, with prodigious production of their fruit, they were a major economic resource, providing good lumber and delicious snacks. By the mid-1940s, they were virtually gone, the blight having annihilated 8.8 million acres (13,750 square miles) of chestnut forest. Just after the turn of the 21st century, only one full stand of original American chestnut trees remained mostly untouched, a 60-acre forest in Wisconsin that was hypervigilantly guarded to preserve it for reintroducing the species when the blight could be eliminated. Other approaches involving genetic engineering were tried, too.

Eventually, in the late 2080s, a treatment method was found that could attack just the blight and leave the trees alone, allowing propagation of the original lines. It took much effort, but within a decade, blight was finally wiped from North America, Europe, and parts of its original sources in Asia. Over the intervening centuries--and especially with human impacts greatly reduced and almost zero trade with other continents to give blight a chance to reinfect the trees--the tree has again flourished, becoming the economic resource it once was to many towns, a source of wild game for hunters, a home for wildlife (and more than a few bandits), and sometimes just a nice canopy to rest under.

# Economics

## Money

Money in most of North America is handled in universal credits.

How? Decentralized cryptocurrency. An advanced algorithm that few understand (and even fewer can implement) allows anyone to send or receive Credits. This means that the CS, Ishpeming, Manistique Imperium, and many others can work on the same economic system.

Connection to the universal mesh network is required at least weekly, preferably daily. Transmissions can be a problem as they can be traced, but individual interception is unlikely because of proxies and go-betweens. The Coalition has reason to not attack everything so as to gain intelligence through analysis. In part because of this, many individuals and even city-states and empires believe that the transactions are untraceable.

Multiple mesh networks and cryptocurrencies exist throughout the world. For example, Triax and CS have different nets but arrange transfers of each others’ cryptocurrency through sophisticated exchanges.

Many smaller communities rely on local currency exchanges or even barter. Be prepared to exchange coins for food, or even a bag of rice for an E-clip.

## Jobs

Employment is an odd mix of medieval, Renaissance, and modern. Mining, woodworking, and farming are more popular than they used to be, but there are also scholars, standing armies, and professional politicians. There are also doctors, scientists, librarians, computer technicians, roboticists, and a range of other professions that require specialized knowledge. How they gain it varies: while some cities have full-fledged universities, a lot of people picked it up along the way. If your friend needs an appendectomy, you might get someone who graduated from the university in Quebec, or you may have to watch the "town surgeon" (who is also the tailor, the optician, and the electronics repair expert) reading from a book as they perform the work--basically, they do it because they have the steadiest hands, not because they actually were trained to do it.

## Trade

Most towns have some basic, common trade items (agricultural products, livestock, and some common textiles and manufactured goods) and a few things they specialize in. Some of these specializations include jewelry, vehicles, weapons, and electronics, as well as location-specific resources such as key minerals or plants or crops that are difficult to grow or need very specialized knowledge. Some towns also offer services including religious, medical, research, magic, and even financial. A great deal of trade is handled by barter, and all new forms of accounting have come up to help balance the books.

## Common Materials

Many people, particularly in poorer areas, have come to rely on older textiles such as linen, leather, fur, and wool. In some areas, cotton is available for clothing, and in large cities, synthetic fabrics such as polyester are available. Clothing tends to last *much* longer outside major cities because fewer people make it so it's more expensive. Boots are much more common than shoes, but shoes aren't that uncommon.

For construction, wood is by far the most common and wooden fasteners are pretty common because they can be made locally.  Concrete is relatively common but expensive.

Iron is available but not usually from large foundries, so steel is a bit less common. Most cities have an iron furnace using a modern process so good steel can be made, but with limited volumes. Aluminum is common in major cities, uncommon elsewhere because of the amount of electricity needed to purify it. Copper is uncommon in general but not too hard to get.

Gemstones are pretty rare, and people largely don't care about them unless they're rich. They're valuable enough for poor people to sell, become targets for theft from the middle classes, and for either group, the fear that they are enchanted or cursed is widespread. The wealthy can afford to buy (and secure) them and to determine if they have any magic cast upon them, so they feel fairly safe doing so.

## Manufacturing

Complex manufacturing like vehicles, power armor, and computers is still done almost entirely by high-precision, automated factories located in the Coalition States, Northern Gun, etc. Basically, all the places that you'd think would have them have them, and if you can't think of them having them, they probably don't. Those factories located outside current main cities have been largely stripped of anything valuable, if they're still standing at all.

One of the most profitable industries is the reverse of manufacturing: recycling. These don't take the big factories with complicated equipment, so they don't require such large populations to support, but they do require some skill, especially since chemical recovery is often needed to get at trace elements. Some just do general recovery and sales of raw materials, essentially advanced scrapyards, while others perform bespoke recovery services, ensuring that key materials go back to the provider of the original source material.
