.. image:: https://github.com/SchoolOfFreelancing/Voice-Broadcasting/blob/develop/img/logo.jpg

Overview
--------

Voice-Broadcasting is a voice broadcast application, which can fulfil a variety 
of roles for a range of industries and organisations who wish to contact 
large numbers of people by phone in a short space of time.

Voice-Broadcasting aplication has been built using a messaging system so that
it can support distributed processing on cloud servers. The platform is
focused on real-time operations and task call distributions to clustered
brokers and workers meaning that many millions of calls can be processed daily.

Voice-Broadcasting can be installed on a standalone server for smaller deployments.
It currently utilises the Freeswitch Telephony engine
(http://www.freeswitch.org) to process the the outbound calls. However support
for other telephony engines, such as Asterisk may be added in the future.

Voice-Broadcasting is written in Lua & Python using the Django Framework, and 
operates with message brokers such as RabbitMQ.
