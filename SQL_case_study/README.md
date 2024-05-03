# Case Study: Data Scientist working for a wildlife contracting company, ML Wildlife

In this assignment we were tasked to collect data from [iNaturalist](https://www.inaturalist.org/), a social network and database that allows users to share and record observations of biodiversity. We were taked to collect the data using the sites API and then answer questions regarding our findings. Below is an explaination of the assingment.

### You are a data scientist for a wildlife contracting company, ML Wildlife. 

### ML Wildlife Mission Statement: To pioneer innovative approaches to wildlife management and policy-making through data collection, storage, and analysis. It is the company's goal to create sustainable connections between human activities and the natural world to preserve biodiversity.

In a New Jersey town (that will remain unnamed), there is a proposal to begin construction during the Summer of 2024 on a bike path that will run for 2.5 miles through the salt marsh. The bike path will be a raised (7ft) concrete pathway, or seawall, to accomodate for high and low tides to ensure that flooding is not an issue for the path. Water or wildlife (Turtles, fish, crabs, inverts, etc.) can not pass through or under the pathway. Birds can fly over the pathway. Construction is estimated to last four months. The goal of the pathway is to teach people about wildlife by walking through the man-made salt marsh trail. Railings will be placed on either side of the pathway to ensure human safety, but what about the safety of the wildlife?

Local environmentalists and biologists are concerned with the proposed bike path, especially for the state's Diamondback terrapin population. Will this bike path create an obstacle that will force more females to cross the roads to lay their eggs? What about the eggs that are laid along the bike bath already from the year before? Will the nests be ruined in the process? In addition to the Diamondback terrapin, additional species also utilize this area for nesting and feeding like the Ipswich Sparrow, which is a subspecies of the Savannah Sparrow that has a very limited range. The saltmarsh serves as an important nursery ground for Atlantic Menhaden, the Mid-Atlantic ecosystem's "Most Important Fish of the Sea."

Your job is to:<br>
--Collect citizen science observations from 2019-2024 in iNaturalist of the Northern Diamondback terrapin using the iNaturalist API with R package, spocc.<br>
--Upload that data into a database either locally or on your MySQL server. <br>
--Use SQL to: <br>
    ----Select for research grade observations only. We only want observations that have been accepted by expert naturalists or scientists that confirm the observation.<br>
    ----Determine the best time of year (Or months or weeks or time of day) for project construction.<br>
    ----Determine what subset of the population (Egg, Juvennile or Adult) you believe would be most impacted. <br>
    ----Determine the general observaiton population demographics, or range, for New Jersey terrrapins.<br>
    ----Explore two other species that inhabit and utilize the saltmarsh (Examples are the Ipswich sparrow, Seaside sparrow, Saltmarsh sparrow, Atlantic menhaden, or the Mud fiddler crab and Eastern Mud snail (What terrapins eat) and hypothesize how they would be impacted by this construction project after you have explored their data. Use the data from these other two species to support your decision below. If you would like to choose another species you can, just be mindful of iNaturalist API limits. I recommend looking at the iNaturalist website and explore the different species before collecting data that you do not need. <br>
    
--Provide your overall determination approving or disproving the project with three visualizations to go along with the queried SQL data. **Breifly state why and include three graphics** - but you do not have to go into too much biology detail and there is no right or wrong answer. <br>
--State two possible reasons for results for error in your visualizations.<br>
<br><br>
_Also note, this is a **mostly** "fictional" case study_ :). <br>

**Background information on the other species:**<br>
Ipswich Sparrow (_Passerculus sandwichensis princeps_) - A subspecies of the Savannah Sparrow. Subspecies can breed independently of the parent species. These birds feed directly in the dunes and saltmarshes. They are not as common as the parent species.<br>
Atlantic Menhaden (_Brevoortia tyrannus_) - A small schooling bait fish less than 10in in length. These fish begin their lives in the back bays and salt marshes. They are the primary food source for many species of marine mammals, birds, sharks, and larger fish. They are harvested commercially by us humans in the Mid-Atlantic to create fertilizer, fish oil, pet food, lip products and many other uses.<br>
Eastern Mud Snail (_Ilyanassa obsoleta_) - Food source to many species of birds and terrapins. The ocean clean up crew - feeds on detritis and other matter. <br>
Mud fiddler crab (_Minuca pugnax_) - Only found on the East Coast of the United States. Like many other animals, it is thought this species is expanding the Northern range due to climate change.
