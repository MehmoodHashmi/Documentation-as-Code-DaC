In the past we built really monoliths we cannot name variables properly, we cannot name functions properly; I mean think of the word NoSQL. What does that even mean NoSQL? Is the stupidest name you could think of, and it's NoSQL
actually has SQL. So why call it NoSQL? What I really don't like is the word **microservices** because it's neither **micro** nor a **service,**
and yet we call it microservices.

But when it comes to using these kinds of **systems** these are widely classified as **distributed architecture** which in itself
is a terrible name. Because if I tell you microservices are distributed, then it makes you believe by mistake that **monoliths** are not
**distributed**. As it turns out, monoliths are distributed. When was the last time you created a monolith that was just one Big Blob that
happened about 45 years ago. Since that time I've never seen anyone build a monolith which is just one piece that is never distributed
you got a database server in a monolith you got application service in a monolith you got different service in monolith so every monolith
is distributed as well, and yet we want to call distributed architecture versus monolith.;

So a huge amount of confusion in things we name but in general though when we talk about a **distributor architecture** here
we are talking about **systems and subsystems** that can be **deployed independent of each other**.
So the **distribution** here is **not** in the **execution model** but it is in the **deployment model**.
So you can **deploy** each of the parts independent of each other whereas in a monolith the different parts are distributed together

* Monoliths need a single or synchronized unit of deployment
* Distributed architecture facilitated multiple units of deployment

So you can think about this as a **synchronized deployment** versus a **distributed deployment**.
So when it comes to <b>distributed architectures</b> there are several of them: such as
microservices, service-based architecture, service-oriented architectures, event driven architecture and so on.