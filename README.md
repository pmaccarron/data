# data

Some social network datasets from  epic narratives.

Data is in a tab separated file with the following headers: <br />
Character \t Friendly edges \t Hostile edges

Some datasets are broken into chapters, look for lines beginning with one of:<br />
%Scene or %Chapter or %Book<br />
Some other lines with some random information will also begin with a "%" so ignore those lines when creating the network.

Nodes can have multiple edges based on appearances in different scenes/chapters (no weight data for the Sagas of the Icelanders unfortunately though). <br />
A vertex can also have both hostile and friendly edges to the same vertex. <br/>

Hostile links are generally defined as when two characters fight in the narrative. I started with "the Táin" and the protagonist Cúchulainn kills many characters but has no other interaction with them. I wanted some way to represent this as it is an interaction but it's very different from a standard social interaction. So in general if two characters hate each other and argue all the time they will still get a "friendly edge" and will only get a "hostile edge" if they physically fight or one kills the other. (So the word friendly here is a bit of a misnomer.)


**Citations**<br />
Please note that my last name is "MacCarron" (or Mac Carron) and not "Carron"!<br />
For the data for "Tain.tsv", "Beowulf.tsv" and "Iliad.tsv" please cite:<br />
MacCarron & Kenna (2012) EPL (Europhysics Letters) 99.2: 28002<br />
For the data in the "icelanders" folder please cite:<br />
MacCarron & Kenna (2013) Eur. Phys. J. B, 86.10: 407<br />


Note, the three datasets "Tain.tsv", "Beowulf.tsv" and "Iliad.tsv" have need updates slightly since the EPL (and I don't seem to have the earlier versions :/ ) so the network properties might not always match exactly. Any value reported in my PhD thesis will be the value used from the final (and most correct) dataset. The thesis can be accessed here:<br />
https://curve.coventry.ac.uk/open/file/9bfc043d-497e-4217-82ab-e19963b53290/1/maccarroncomb.pdf


If you require any of these datasets and I haven't added them to this repository yet please email me at:<br />
padraig.maccarron at wolfson.ox.ac.uk
