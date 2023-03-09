# Commmand 1 - "grep -r -w"
This command prints out the files that contains the given pattern.
This command is useful because a user is able to see the file and its contents a 
certain word. This may be used when a user wants to see files and print them
with a certain word or pattern of their choice.

**Example 1** 
`grep -r -w "spaghetti" written_2`

**Output:**
```
written_2/non-fiction/OUP/Berk/ch2.txt:“When our parents split up, we moved with our 
mom from Arkansas to Seattle. Mom worked all week, weekends, and most evenings. She 
had to get a career going so there’d be money to live on and to send us to college. 
Sarah hung out with another family in the neighborhood. A couple of times a week, she
had dinner and went to church with them. Looking back, I’d say they were her substitute
family; she ‘adopted’ them, and they ‘adopted’ her. I was too young to go o on my own that
way. When I didn’t have after-school activities, Mom insisted that I come home and do chores
and homework. Sometimes I got to go to a friend’s house to play, but many nights I’d 
open a can of spaghetti and have dinner by myself. I spent hours daydreaming and looking
at old pictures of Mom, Dad, Sarah, and me.”
written_2/non-fiction/OUP/Kauffman/ch8.txt:Already this is worth the excited attention
I gave it so long ago. For the results show that a network with randomly chosen logic
nevertheless behaves with exquisite order. Say, a network of , genes is constructed at random, 
with the simple limitation that each model gene have K = inputs but that the wiring diagram be
chosen at random, and the Boolean function assigned to each gene among the possible Boolean
functions of K = inputs is also chosen, once and for all, at random, this spaghetti mess of a
network with its tangle of , wires connecting the genes in some mad scramble will straighten itself out.
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:Inland from Almería lies one of the most un-European 
landscapes on the European continent. The Sierra de Alhamilla is a desert of barren mountains, 
rocky ravines, and dry gravel riverbeds; spiky agave plants and prickly pears are the only vegetation.
The region’s uncanny resemblance to the American West made it a popular film location for spaghetti 
westerns, including such classics as A Fistful of Dollars and The Good, the Bad, and the Ugly, 
which set a young Clint Eastwood on the road to stardom in Hollywood. Near the village of Tabernas
is an area known as Mini-Hollywood, where two spaghetti-western film sets have been preserved as tourist attractions,
complete with horses, cowboys, and barroom brawls.
```

**Example 2** 
`grep -r -w "saffron`

**Output:**
```
written_2/travel_guides/berlitz1/WhatToIbiza.txt:       
packets of colourful azafrán (saffron) and any other dried herbs you
written_2/travel_guides/berlitz1/WhatToIbiza.txt:       
the sea from Ibiza. It’s named after the iron pan in which the saffron
written_2/travel_guides/berlitz1/WhatToIbiza.txt:       
with saffron, garlic, sweet pepper, cinnamon, and cloves.
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:        
zerde (a saffron-flavoured rice pudding), and tavuk gö‘sü (a
written_2/travel_guides/berlitz1/WhereToIndia.txt:       
local cricket-bat industry, and fields of saffron. If you’ve ever
written_2/travel_guides/berlitz1/WhereToIndia.txt:       
wondered why saffron is so expensive, it’s because 150,000 of these
written_2/travel_guides/berlitz1/WhereToIndia.txt:       
make up a single kilogram (2 pounds) of saffron proper, the stuff that
written_2/travel_guides/berlitz1/WhereToIndia.txt:        
saffron is grown extensively. )
written_2/travel_guides/berlitz1/WhereToIndia.txt:        
and saffron-colored veils. A platform marks Buddha’s seat and a set of
written_2/travel_guides/berlitz1/WhereToMallorca.txt:      
with saffron and cinnamon) and hierbas dulces, a bright green liquid
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:Excellent rice 
(arroz) has grown on the Costa Blanca’s doorstep since Moorish times; hence
the many rice dishes and, king of them all, world-famous paella. Paella is 
named after the large, shallow iron pan in which it is cooked and served. 
The basis is rice, soaked in stock coloured yellow with locally grown saffron,
and fried. Paella valenciana adds meat, usually crisply fried chicken and pork,
and a seasonal variety of peas, green beans, peppers, and other vegetables.
Paella alicantina is the same, plus generous portions of whole prawns, mussels,
small whole crabs, octopus, and slices of lemon. A good one is a gastronomic thrill!
```

# Commmand 1 - "grep -r -w"
**Example 1**
`grep -r -B 1 "émigrée" written_2`

**Output**
```
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt-Baracoa, though, has so much going
for it that any associations with Columbus are a bonus. A good place to get your bearings 
is the hilltop Hotel El Castillo, a former castle looking out over old red-tiled roofs,
the town’s oyster-shaped bay, and the landmark mountain known as “El Yunque” (“The Anvil”), 
so named on account of its singular shape.
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:On Calle Antonio Maceo, you’ll find 
people queuing for hot chocolate drinks in the baking tropical sun at Casa del Chocolate. 
Opposite is a charming Casa de la Trova, with rooftop performances. In the main square is 
a striking bust of Hatuey, the brave Indian leader who resisted early conquistadores until
he was caught by the Spanish and burned at the stake. Also wander along the Malecón, the 
seaside avenue, from the snug Fuerte Matachín (an early 19th-century fort that has a small
municipal museum attached) to the Hotel La Rusa, named after a legendary and glamorous Russian
émigrée who over the years hosted celebrities from Che and Fidel to Errol Flynn.
```

**Example 2**
`grep -r -B 1 "Lucayans" written_2`

**Output**
```
written_2/travel_guides/berlitz2/Bahamas-History.txt-A Brief History
written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before 
the arrival of Columbus, a peaceful Amerindian people who called themselves
the Luccucairi had settled in the Bahamas. Originally from South America, they 
had traveled up through the Caribbean islands, surviving by cultivating modest 
crops and from what they caught from sea and shore. Nothing in the experience
of these gentle people could have prepared them for the arrival of the Pinta,
the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed
that he had reached the East Indies and mistakenly called these people Indians. We
know them today as the Lucayans. Columbus claimed the island and others in the Bahamas
for his royal Spanish patrons, but not finding the 
gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle
in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed 
through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports.
On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which
was used to replenish the supplies of water on their ships before they began the long journey back
to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of
them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish 
gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```

