### Update 3.11.2017
1. Using POS and IOB tagging, we were able to invoke pop-ups / alert for named entities like names in the sentence and hence tell the user1 to share his contact details if user2 needs it.
2. For Locations, we can ask user1 if he'd like to share/give directions to user2

### Understanding the Problem: Communication gap over textual conversations
1. User1 assumes that user2 knows this
2. User1 does not re-read his message

### Problems
1. Usage of names based on context of the names

 - Ex1: You should go meet kevin
  
    - User1 gets pop-up to share kevin's contact details
    
 - Ex2: Kevin and Abhinav are good students.
  
    - User1 gets pop-up to share kevin's and abhinav's contact details

### Alternatives
1. Predictive text based on Who, What, When, Where and How questions of the context which is chat conversations 

  Ex1: User1 types "I sent you a picture."
  
  - Knowing 'what' had to sent based on the chat between the users. "A picture of my new haircut"
  - Knowing 'how'/'where'. Which medium was used. Whatsapp or email
  - Knowing 'when'. Need it be asked? Yes. Maybe.
  
  If User1 told User2 that he got a haircut and user2 requested a picture over whatsapp. So the chat history answers 'what' of the context but not 'how'/'where'. Hence user1 can get text prediction: 'on whatsapp', 'on email'. 

# Suggestive-Pop-Ups
Assistive Information for textual conversations using Pop-Ups

**Abstract**

Often, we can miss out on crucial information supposing that the
other person is aware of it, while using instant messaging or
sharing emails.
Crucial Information may include contact details of person
mentioned in the thread of messages or location of a place or
timings of the event, that hampers the flow of the information.

**Following is a regular conversation between a student and the
dean.**

30.08.2015 1:00PM

**Student:** Sir, I lost my phone. What can I do about it?

**Dean:** Look for it in the SWP office.

**Student:** Where is the SWP office?

---- No response from Dean and the student now has another
problem of looking of the SWP office ----

**Following is same conversation *with* the Suggestive Pop-Ups
between the student and the dean.**

30.08.2015 1:00PM

**Student:** Sir, I lost my phone. What can I do about it?

**Dean:** Look for it in the SWP office.
**Gets pop-up over SWP Office, 'Where is the SWP Office'? **

>---- Dean now edits the message before sending it ----

**Dean:** Look for it in the SWP office, which is near the main gate.

**Student:** Thank you, sir.

**References:**

>[1] Frank Bentley, Nediyana Daskalova, Nazanin Andalibi “If a person is emailing you, it just doesn't make sense”: Exploring Changing Consumer Behaviors in Email [2017]
