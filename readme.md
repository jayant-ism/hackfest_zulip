Team Inquistors :-
Topic :- Schedular bot using zulip API
-------------------------------------------------------------------------
Command used 

The Schedular bot is used to schedule a  message for a particular timeframe.
This bot can help in colborating with the offshore team especially with a 
timezone gap.

For using this bot we will be required to register ourselves to the bot and the
request the bot to schedule our message for a perticular time.


For registering the bot the following syntax will be used.
/register_bot <--apikey of the user -->
We may find the api key from:-
Settings -> Your Account -> Show/Change Api key -> Get Api key 

Copy the api key along with the syntax and message it to the bot for registration.

We may schedule a private message or a stream:-

	Command for scheduling a private message 
		message_schedule dd-mm-yyyy-hh-mm private-message-address> <--message content -->
	eg:-
	message_schedule 02-05-2021-04-48 anandakash375@gmail.com> Hey buddy how are you!

	
	Command for scheduling a message to the stream
		message_schedule dd-mm-yyyy-hh-mm stream topic > <--message content -->
	
	eg:-
	message_schedule 02-05-2021-04-46 test_bot-bot Castle > Hey guys how is the project going on!
_____________________________________________________________________________________________________
The demo is shown https://drive.google.com/file/d/1toR8BsSXFG8u294q546PHPAMHshp1nXG/view?usp=sharing . (please download the video for preview in better quality) 
All the code required to run this bot can be found https://github.com/jayant-ism/hackfest_zulip/tree/master.
