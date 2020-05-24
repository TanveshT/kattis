Problem ID:  transitwoes
CPU Time limit:  1 second
Memory limit:  1024 MB
Difficulty:  1.3

Transit Woes

Everyday Yraglac relies on his city�s local transit system
    to get to and from campus. Since this is routine for him, he�s
    memorized exactly what time will let him leave his house and
    make it in time to his first morning class. Of course transit
    being transit, they decided to change around the schedules for
    some of the routes Yraglac takes.

Yraglac leaves his house everyday at time $s$ to make it to his first class
    which starts at time $t$.
    To get there, he takes $n$
    transit routes, one after the other. When transferring from one
    transit route to another, going from his house to the first
    transit stop, and going from the last transit stop to his
    class, he must walk for $d_
    i$ time. Yraglac rides the $i-th$ bus for $b_ i$ time before getting off and
    walking to the $i+1$-th
    bus stop. Last but not least, each bus only comes at an
    interval of every $c_ i$.
    The first one always leaving at time $0$.

$s$

$t$

$n$

$d_
    i$

$i-th$

$b_ i$

$i+1$

$c_ i$

$0$

Given the new schedules for the routes Yraglac takes, can
    you find out if he can make it to class on time?

Input

The first line contains $3$ space separated integers,
    $0 \leq s \leq t \leq 1\,
    000$, and $1 \leq n \leq
    20$.

$3$

$0 \leq s \leq t \leq 1\,
    000$

$1 \leq n \leq
    20$

The second line contains $n +
    1$ space separated integers $d_ i$ $(0 \leq d_ i \leq 1\, 000)$ denoting
    the time it takes to walk from the $i$-th bus� drop-off point to the
    $i+1$-th bus stop. Note
    that $d_0$ is the time it
    takes to walk from Yraglac�s house to the first bus stop, and
    $d_ n$ is the time it
    takes to walk from the last bus� drop-off point to his
    class.

$n +
    1$

$d_ i$

$(0 \leq d_ i \leq 1\, 000)$

$i$

$i+1$

$d_0$

$d_ n$

The third line contains $n$ space separated integers
    $b_ i$ $(1 \leq b_ i \leq 1\, 000)$ denoting
    the amount of time Yraglac rides the $i$-th bus.

$n$

$b_ i$

$(1 \leq b_ i \leq 1\, 000)$

$i$

The fourth line contains $n$ space separated integers
    $c_ i$ $(1 \leq c_ i \leq 1\, 000)$ denoting
    the intervals the $i$-th
    bus arrives.

$n$

$c_ i$

$(1 \leq c_ i \leq 1\, 000)$

$i$

Output

Output �yes� if Yraglac will be able to get to class in
    time, and �no� otherwise.