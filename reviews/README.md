## Literature Review listings

1. 10->Elementary Data Structures, Introduction to algorithms third edition
    Presents a solid introduction to elementary concepts such as linked lists, trees and stacks. The images and psuedo code is most notable.
2. 27->Multithreaded Applications, Introduction to algorithms third edition
    Introductory text into multithreading algorithms, although simplifies it to just coroutines it is useful for atleast a quote.
3. Thread scheduling, Windows internals fifth edition
    Very indepth description of when and how threads are scheduled to execute
4. Assembly language programming, Graphics programming in C++
    Introductory information into x86 assembly for a 32bit cpu in the context of making a Win32 message loop faster during copying of an image.
5. Server-centric Web frameworks: an overview, Iwan Vosloo and Derrick G. Kourie, cpit/2014/BCIS381/reports/13/32160558.pdf
    This research paper provides a background into how to analyse web frameworks and its ilk. It gives a good categorisation for requirements of them and how to classify them.
6. AC: Composable Asynchronous IO for Native Languages, Tim Harris and Martin Abadi and Rebecca Isaacs and Ross McIlroy, cpit/2014/BCIS381/reports/17/barrelfish_oopsla11.pdf
    The research paper has shown an optimization technique that is capable of getting more performance out of operations by changing how the code is scheduled and then executed.
7. Fast request routing using regular expressions, Nikita Popov, https://nikic.github.io/2014/02/18/Fast-request-routing-using-regular-expressions.html
    Performance of routing is defined by the abstraction to which it is implemented within memory not by 
which the language it is used in.
8. Managing Routing Disruptions in Internet Service Provider Networks, Renata Teixeira and Jennifer Rexford, https://www.cs.princeton.edu/~jrex/papers/ieeecomm05.pdf
    Routing systems such as employed with ISPs use a vast network of configurable routers that communicate 
within and to other networks. The transmission of packets are done via weights to each of the routers.
9. Engineering a Simple, Efficient Code Generator Generator, CHRISTOPHER W. FRASER, DAVID R. HANSON and TODD 
A. PROEBSTING, https://drhanson.s3.amazonaws.com/storage/documents/iburg.pdf
    An introduction to code generator generators that focusses upon assembly being the end goal. Does not cover text parsing.
10. Fast networking with socket-outsourcing in hosted virtual machine environments,	Hideki Eiraku, Yasushi Shinjo, Calton Pu, Younggyun Koh and Kazuhiko Kato,  http://dl.acm.org/citation.cfm?id=1529350
    The norminal form that IP stacks take is very wasteful when it comes to processing of packets between a VM and its host. This paper proposes a way to limit copying and with it significantly cheaper socket IO.


* Exception-Less System Calls for Event-Driven Servers, Livio Soares and Michael Stumm, http://static.usenix.org/legacy/events/atc11/tech/final_files/Soares.pdf
* Web server support for tiered services, N. Bhatti, R. Friedrich and Hewlett-Packard Res. Labs., USA, http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=793694&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D793694
* Adaptive Overload Control for Busy Internet Servers, Matt Welsh and David Culler, http://static.usenix.org/events/usits03/tech/full_papers/welsh/welsh_html/
* Network algorithmics, George Varghese, http://dl.acm.org/citation.cfm?id=1882751
* Fastest connection first: A new scheduling policy for web servers, Cristina Duarte Murta and Tarcisio Paulo Corlassoli, http://www.sciencedirect.com/science/article/pii/S1388343703801634