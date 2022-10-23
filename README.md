# Dialogue system and Question answering system

In this project,  A dialogue system has been developed to perform 3 main functionalities: 
<li>Finding a nearby restaurant</li>
<li>Getting the weather forecast to a given city</li>
<li>Find the next tram/bus to a given destination</li>

The 3 functionalities above are done using NLP for text understanding and named entity recognition, afterwards, a google search query is sent to get an answer for the user's question, and its result is then web-scraped.

The diialogue system work-flow is the following:

    **Step 1**: AI greets.
    **Step 2**: User greets.
    **Step 3**: AI requests help.
    **Step 4**: User asks for information. 
    **Step 5**: If the AI understood the question, it grounds, else, it asks for question re-formalization.
    **Step 6**: AI gets and displays the requested information, and asks if the user has other requests.
    **Step 7**: If the user doesn't have other requests, the AI greets and ends the conversation, else the AI goes back to \textbf{Step 3}.

