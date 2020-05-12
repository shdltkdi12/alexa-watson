# Cloud-Computing-Homework-2 #
Members: Isaiah, Kyle, Cameron, Jake, Emma
## Integrating Watson Assistant with Alexa ##
We used IBM Cloud’s equivalent of lambda functions, called Cloud Functions, which is based on open source software. 
Since we are now calling out to an external service, we configured everything from connecting endpoints, creating the IBM API, creating Alexa Skill Intents.  
Instead of programming utterances into the Alexa Skill, we will let have Alexa pass the utterance to Watson Assistant, and let Watson Assistant handle understanding what has been said and how to respond.
We provide the ability for Watson Assistant to answer these questions over the phone, integrating Watson Assistant with Twilio (a communications provider) to enable phone calls.
It should be able to ask your Alexa Skill:
1.    Who your team members are
2.    Another question related to class or your group
3.    Another question related to class or your groupAnd