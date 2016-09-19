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
11. Adaptive Overload Control for Busy Internet Servers, Matt Welsh and David Culler, http://static.usenix.org/events/usits03/tech/full_papers/welsh/welsh_html/
    Introduces a new architecture in processing of socket connections that allows for degradation of service in a predictable form.
12. Modeling Request Routing in Web Applications, Minmin Han and Chrsitine Hofmeister, 
http://dx.doi.org/10.1109/WSE.2006.14
    Web applications are getting quite large and as such there needs to be a way to document the routing 
process that goes on inside of it.
13. Architecture of a Web server accelerator, Junehwa Song, Arun Iyengar, Eric Levy-Abegnoli1 and Daniel 
Dias, http://www.sciencedirect.com.ezproxy.lincoln.ac.nz/science/article/pii/S1389128601002419
    By using a web server accelerator paired with a TCP/IP stack that is designed for low memory movement a 
web page set of requests can be optimized to be significantly faster for both static and dynamic content.
14. Distributed cooperative Web servers, Scott M. Baker and Bongki Moon, http://www.sciencedirect.com.ezproxy.lincoln.ac.nz/science/article/pii/S1389128699000110
    Introduces rewriting of contents links to other content to isolate to specific servers. Allowing for 
movement within a server graph to increase ability to serve larger web sites.
15. Optimizing Web servers using Page rank prefetching for clustered accesses, Victor Safronov and Manish Parahsar, http://www.sciencedirect.com.ezproxy.lincoln.ac.nz/science/article/pii/S0020025502003754
    Based upon the usage of page rank algorithm for each request determines what content should be loaded 
ready for transfer to client and in doing so significantly improve performance of requests.

* FB+-tree for Big Data Management, Cui Yu and Josef Boyd, http://www.sciencedirect.com.ezproxy.lincoln.ac.nz/science/article/pii/S2214579615000635
* Cache Conscious Indexing for Decision-Support in Main Memory, Jun Rao and Kenneth A. Ross, http://www.vldb.org/conf/1999/P7.pdf
* Making B+- trees cache conscious in main memory, Jun Rao and Kenneth A. Ross, http://dl.acm.org/citation.cfm?id=335449
