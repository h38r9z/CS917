java c
Department   of   Computer   Science   CS917 
Foundations   of Computing -   Maths   and   Stats 
Assignment 
This assignment is due at noon on Thursday    19th December, 2024.   The   submission is on Tabula, and should comprise scanned copies   of written work.
The   work   that   you   submit   should   be your own work and   please   show full working where   appropriate, as   this   is   necessary   to   gain   full   marks.
Marks for each question are indicated.   The total marks you   can   get   is   100.
If   you   have   any   questions   then   do   please   email   meat   [email   protected].
1          Discrete Mathematics 
1.   For each of the following   formulae,   ﬁnd   a   logically   equivalent   formula   in   which   Λ   ,    =→       and      ←→       do   not   occur:    (i) :(p       =→       q)    [5 marks];   (ii)   ((p Λ q) _r)   [5 marks];   (iii) :((p Λ q)    ←→    r)   [5 marks].   Use   the   truth table   to   show   that   the   proposed   solution   is   indeed   equivalent   with   the   original one.   [total   15 marks]
2.   Write   out   paraphrases   of   the   following, using   8,   9   and   =    (i) Frodo   has   a ring [2 marks]; (ii) Sauron does not have any rings [2 marks]; (iii) The One   Ring   rules   all   the   other   rings   [2 marks]; (iv) The   ring   that   Frodo   has   is   the One Ring [2 marks]; (v) whoever wears the ring, becomes invisible (i.e., no   other   ordinary   human   can   see   that   person)   [3 marks]; (vi) Bombadil   Tom can see the ring-wearer, hence he is no ordinary   human   (use   the   previous   statement   from   (v)   to   formulate   this   one)   [3   marks].    Auxiliary   clauses:   has(x,   y): x   has/is   in   possession   of   y; rules(x,   y): x   rules   y; wears(x,   y): x   wears   y; sees(x,   y): x   can   see   y; and   ordinary(x): x   is   an   ordinary   human.   [total   14 marks]
3.   Write   predicate   logic   formulae   which   state   that   the   relation   expressed   by Rx,y      has   the   following   properties:   (i) Rx,y      is   irreflexive   [3 marks]; (ii) Rx,y   is   intransitive   [3 marks];   (iii)   Rx,y      is   not   a   partial   order   [3   marks].    Note that this formulation is a bit diferent from the one in the slides.   To make this   consistent, think   about   Rx,y         as   Rp      with   relation   p   between   x   and   y (you   can   assume   that   both   x   andy   are   from   the   same   set   A).   So   you   can use   Rx,y      as   p   in   your   formulations.    Therefore,   in   your   answer,   you   can use both notations, just be consistent   (i.e., if you choose 1 notation, then   use the same for all your   answers).    [total 9 marks]
4.   Determine   which   of the   following   functions   are   injective   and   which   are   surjective   (please   provide   explanations   as   well):
(i) f : Z ! N, where   8n   ∈ Z:   f(n) = n2024   + 1   [3 marks];(ii) g : N   x   N   ! N, where   8(n,   k) ∈ N   x   N:   g(n,   k) = 2n3k5n+k      [3 marks];(iii) h : P(N) ! P(N), where   8A ∈ P(N):   h(A) = N  代 写CS917 Foundations of Computing - Maths and Stats AssignmentStatistics
代做程序编程语言 \A   (recall   what P(N)   means)   [3 marks];
(iv) k : N ! Z, where   8n ∈ N:   k(n)   =   (-1)n       [3 marks].   [total   12 marks].
2 Statistical Analysis 
Question   1 has two parts, each is   marked   out   of   5.   Both   Question   2   and   3   are   marked out of 10.   Question 4   is   marked out   of   20.
1.   A   large   database   is   compiled   from   ﬁles   contributed   by   three   sources:   Source   A,   Source   B,   and   Source   C,   which   account   for   20%,   50%,   and   30%   of the   total   ﬁles,   respectively.    The   percentage   of empty   ﬁles   from   each source is 4%   for   Source   A,   2.5%   for   Source   B,   and   1.5%   for   Source   C.   If   a   ﬁle   is   selected   at   random   and   found   to   be   empty,   what   is   the   probability   that   it   originated   from   Source   A?
2.   A survey was conducted on a   large   number   of individuals to   record   their   dates   of   birth.    Assume   that   the   sample   size   is   sufflciently   large   to   treat the   dates   of   birth   as   uniformly   distributed   across   all   possible   days.
(i)   What   is   the   smallest   number   of   randomly   selected   individuals   re-   quired   such   that   the   probability   of   at   least   two   of   them   sharing   the same birthday exceeds 50%?   Assume there are 365 days in   each   year.
(ii)   Two   individuals   are   selected   at   random   from   those   born   between   January   1st   , 1961, and   December   31th   , 2000.   Given   that   at   least   one of   these   individuals   was   born   in   a   leap   year, what   is   the   probability that   both   individuals   were   born   in   a   leap   year?
3.   A   directory   contains   6   high-priority   records   and   4   low-priority   records.   These   records   need   to   be   analysed   by   employees,   and   the   workload   is   divided   among   them.    Four   records   are   randomly   assigned   to   Sam,   but   the priority of each record   is   not   identiﬁable   from   the   ﬁle   names.    Given   that   the ﬁrst   record   Sam   analyses   is   low-priority,   what   is   the   probability that all the remaining records assigned to him are of   the same priority (all   remaining   either   low-priority   or   high-priority)?
4.   A small company operates two 72-core computers, Computer A and Com-   puter B.
(i)   On   Computer   A, it   is   known   that   each   core   is   busy   50%   of   the   time on   average.    At   any   given   time,   what   is   the   probability   that   36   or more cores are busy   simultaneously?
(ii)   On   Computer   B,   a   random   sample   of   8   observations   is   taken.    The average   number of busy   cores   in this   sample   is   40.5,   with   a   sample   standard   deviation   of   3.2 cores.   One   individual   claims   that   the   true mean number of busy cores is 36.   Based on the sample data, is there   sufflcient evidence to reject this claim at the   5% signiﬁcance   level?






         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
