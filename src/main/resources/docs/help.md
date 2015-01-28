# GraphBrain Help

GraphBrain is a system that allows you to easily create, populate and explore knowledge graphs. Knowledge graphs are a way to record information in networks of relationships, in a very similar fashion to how we keep memories in our own brains.

Knowledge graphs can be collaborative: you can allow other users to collaborate in adding knowledge to your graphs.

In this document we will explain how to:

* Create a new knowledge graph
* Add knowledge to the graph in several ways
* Explore and navigate
* Switch to other graphs
* Add collaborators to your graphs

### The current graph

The top bar always includes an indicator of the current knowledge graph. It's right next to the input area. Every GraphBrain user has a personal graph, and this is the one you start with by default.

By clicking the graph indicator you can access a drop-down menu with commands related to the creation, management and navigation of graphs.


### Create new knowledge graph

Click the graph indicator to access the drop-down menu and choose "Create". You are displayed with a dialog asking for the name and description of the graph. Upon creation, you are sent to the new graph's home node.


### Add knowledge to a graph

Knowledge is added through the top bar input area. This is the are labelled with "Search or tell me something". Currently, there are two fundamental ways to add knowledge:

* By writing a simple sentence
* By pasting the URL of a web page

To illustrate, let's assume we are building a knowledge graph about movies.


#### Writing simple sentences to add facts

Simple sentences expressing facts can be typed to add knowledge. For example:

    Stanley Kubrick directed Eyes Wide Shut.

If the system already knows about the entities "Stanley Kubrick" and "Eyes Wide Shut" it will guess the correct connections. If these are new entities, you can define them:

    Eyes Wide Shut is a movie.

And so on. In one of the next sections we will see how to change the menings of entities and create new meanings.

#### Pasting URLs to bookmark and extract topics

If instead of a sentence you paste a URL into the input area, GraphBrain will attempt to read the contents of the web page pointed to by the URL and extract topics. This web page will be added to the knowledge graph and connected to other existing entities as appropriate.

    http://example.com/blog/eyes_wide_shut

If the above URL pointed to a blog post about the movie Eyes Wide Shut, GraphBrain would connect the web page to the movies and all other related entities.

This allows you to crete a knowledge graph that combines pure concepts with web resources.


### Explore and navigate

There are currently 3 main modes of exploration and navigation:

* Simple search
* Network of entity pages
* Intersections

We expect to keep adding more visualization modes to GraphBrain.

#### Search

Graphbrain offers a conventional search interface. If instead of a fact or a URL you just type a search term, for example:

    Stanley Kubrick

GraphBrain will understand that you are searching for this term and will display a dialog containing the possible meanings of "Stanley Kubrick". Maybe it will just know about Stanley Kubrick the film maker. Clicking on that meaning will send you to the appropriate entity page.

#### Network of entity pages

Entity pages show you how all the relevant relations between a certain entity (e.g. Stanley Kubrick) and all other connected entities.

Simply clicking through these entities allows to explore the network of relationships.

#### Intersections

It is possible to see what two entities have in common. This is a powerful exploration mode that can be accessed very easily, because it works in a very similar fashion to simple search.

Try doing a simple search for "violin" and select the musical instrument. Then, from the violin node page search for "piano". This time, on top of the Search Results dialog, switch from "Simple" to "Intersect". Now select piano the musical instrument. A graph will be generated showing how the copncepts of piano and violing are connected through the concepts of "Bowed Stringed Instrument" and "Stringed Instrument". 


### Change meanings

TBD...

If you inserted the previous fact, it will show Eyes Wise Shut as a movie directed by Stanley Kubrick.


### Switch to other graphs

TBD


### Add collaborators, manage permissions

TBD