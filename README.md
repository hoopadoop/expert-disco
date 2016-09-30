# expert-disco
erlang-style mailbox/msg passing for js

i have many problems with concurrency in single threaded javascript

i was reading about [threads and messaging and inbox and selective retreival of incoming messages in erlang](http://ndpar.blogspot.co.uk/2010/11/erlang-explained-selective-receive.html) ie different priority messages and how it worked

processes are isolated, errors contained

i dont know much about erlang, but it looked similar to [fowler's statemachines](http://www.informit.com/articles/article.aspx?p=1592379) which i like

todo
from fowler's blog: 
example json statemachine

todo
how it could be in erlang style

it doesn't just look similar- it's much better!
no DSL, no StateMachineModel, StatemachineParser, StateMachineCommand, StateMachineEvent etc. this is plain-old-erlang.. objects send (oneway!) messages and objects (selectively!) receive messages. nothing else needed

even though in erlang it's purpose is to communicate between threads, could this help in single threaded concurrent javascript?

suggestions, comments, feddback, help welcome and appreciated

