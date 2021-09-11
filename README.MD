CHATBOT NAME: SABRA
Requirements of the chatbot:
A step by step guide and summary of what we need to implement into our chatbot to make it as life-like as possible (includes all 7 points needed to be implemented).
•	Welcome
•	How can I help you?
o	FAQ:
	How can I get badges?
•	Do you know what badges are
•	Explain badges 
•	Give link to the most popular courses
	What is D-NA?
o	Journey Guide
	Where should we take you
	Where should I start
o	Learning Path Advisor
	Courses 
	Explanation
o	Entrepreneurship Support
	Congrats!
	Redirect
o	Feedback
	Answer it
	Note it
	Send to Slack
	Voice recognition
o	Voice enabler
o	Tone Analyzer
	Happy
	Sad
	Angry
o	Translation into Arabic and French
o	Integration with Arabic and French






•	Intents and entities:
A list of all the intents and entities we are going to program the chatbot with, along with the entity value, synonyms of the entities, and the category.
Intents	Entity	Entity Value	Synonym	Category
#CanIskiptoq	Quiz	Quiz	Quiz, test, exam	
#ES	Platform	Specification	Website, browser, apps, programs	
#Esarethecoursesenough	DNA	DNA	D-NA, DNA, Digital Nation Africa	
#EsDoIneedtocomplete	Good	Positive	Great, amazing, good, love, awesome	
#EsIwanttobegin				
#Eswhatservicesdoyouprovide				
#EsWillIbeablecontact				
#faq_badges				
#faq_can_answer				
#faqCanIgetajob				
#faqCanIlinkmy				
#faq_cant_answer				
#faq_dna				
#faqhowcanIattach				
#faqHowmanydevices				
#faqwhatarebadges				
#faqWhatfeaturesare				
#fb	Bad	Negative Comment	Sucks, boring, stupid, doesn’t work	
#fbicantfind				
#fbIcantunderstand				
#fbIhavea				
#fbthiscourse				
#fbthiswebsite				
#fbthiswebsiteg				
#fbwhydoesittake				
#jg				
#jgWhatareDNa				
#jgwherecanI				
#jgWherecanIcheck				
#jgwherecanIstart				
#learningpath				
#lpCanIgetmore				
#lpcanIgoto				
#lpCanIskipto				
#lpCanIskiptol				
#lpCanyouexplain				
#lpCouldIhaveah				
#morehelp				
#welcome				



	Combining intents and entities
Intent	Alternates	Entities	Action
			
			


















FLOW DIAGRAM

This is the flow diagram that our chatbot follows. Although this is a much more simplistic version of how it will work, this is the basic concept it follows. With regards to mainly the queries and routes the user will go through when going through D-NA, this flow diagram helps establish what the chatbot is programmed to answer at a specific time.






