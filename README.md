# EJB-Learning
A scratch repo of artifacts created during the learning of Java and EJB that leads to NO final destination.

# Philosophy
Before we begin, the following is a work in progress project philosophy to help guide our decision making.  First and for most, this project is to learn the new/latest technology stack to build **enterprise** class software guided by the presentation made by Paul Gibson during our RDO all-hands.  Here is the referenced [link](https://www.oreilly.com/ideas/a-young-ladys-illustrated-primer-to-technical-decision-making).  If you don't have the time to view the video, here is the general take away:

* Complexity is increasing.
* Lots of innovation and excitement but with increased complexity.  She refer it to the "**Cambrian explosion of technical complexity**".
* She provided 6 tips of making better technical decisions.

1. **Technology serves the mission**.  We do not build tech for the sake of tech.
  2. Software is the enemy.
    - Every piece of software adds fragility and points of failure
    - Everything you write will need to be maintained and debugged.
    - It is easy to add software, and hard to remove it
  2. Can we do more with less tech?
1. **Reuse solutions**. Resist software sprawl.
  2. Can you solve your problem with your existing tools?
  2. Optimize globally and not locally.
    - If you pick the perfect tool/solution for every local problem, you will have an unmanageable mess.
1. **Create friction for adding new stuff**.  Have a gating process for major new components.
   2. What is the relative gain?
   2. Manufacture friction if necessary
   2. Don't micro manage outside the critical path.  Need room to experiment.
1. **Choose boring technology**.  Boring software runs the world.
   2. Failure modes are well understood.
   2. Rich library support for languages
   2. For databases, extensive production hardening
   2. Tooling and support for observability and debugging.
1. **Spend your risk currency on key differentiators**.  Understand your appetite for risk.
   2. Early startup have massively greater tolerance for risk.
   2. Use that risk! But spend it on your core differentiators.
   2. Can you pay someone to do it better, or cheaper?  Value your team's time?
1. **The longer your survive, the more operational impact trumps all**.
   2. The more mature your company becomes, the more the your technical choices must be driven by operation.
      - Make as many ops problem as possible not your problem.
   2. Celebrate the engineer who remove code, deprecate, and refactor, as much as those who add features.

# Our values

# Technology of interest to us
1. Enterprise Java Bean 3.2 or latest.
2. Docker containers.
3. PostgreSQL relational database.
4. NoSQL for unstructured pile of data.


## Coding guide lines
These are just guide-lines and the first starting point.  They are not intended to be rigid and need to be adapted to the project.
http://geosoft.no/development/javastyle.html
