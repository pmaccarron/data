# data

Some social network datasets from  epic narratives.

Data is in a tab separated file with the following headers: <br />
Character \t Friendly edges \t Hostile edges

Some datasets are broken into chapters, look for lines beginning with one of:<br />
%Scene or %Chapter or %Book<br />
Some lines will also begin with a % so ignore those lines!

Can have multiple edges based on appearances in different scenes/chapters. <br />
Can also have both hostile and friendly edges. <br/>
Hostile links are generally defined as when two characters fight in the narrative. I started with "the Táin" and the protagonist Cúchulainn kills many characters but has no other interaction with them. I wanted some way to represent this as it is an interaction but it's very different from a standard social interaction. So in general if two characters hate each other and argue all the time they will still get a "friendly edge" and will only get a "hostile edge" if they physically fight or one kills the other. (So the word friendly here is a bit of a misnomer!)


Note, the three datasets "Tain.tsv", "Beowulf.tsv" and "Iliad.tsv" contain the social network data for the three epics used in Mac Carron & Kenna (2012) EPL (Europhysics Letters) 99.2: 28002.<br />
However, since then some of the datasets were updated (and I don't seem to have the earlier versions :/ ). 
Any value reported in my PhD thesis will be the value used from the final (and most correct) dataset. The thesis can be accessed here:<br />
https://curve.coventry.ac.uk/open/file/9bfc043d-497e-4217-82ab-e19963b53290/1/maccarroncomb.pdf


If you require any of these datasets and I haven't added them to this repository yet please email me at:<br />
padraig.maccarron@wolfson.ox.ac.uk
