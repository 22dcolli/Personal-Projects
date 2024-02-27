# Personal-Projects
# This is a portfolio of the projects I take most Pride in.
# Currently script.js is a file in which I was tasked to create an algorith that would simmulate the breeding of rats

=> 3<sup>log₃(n)</sup> * T(n/3<sup>log₃(n)</sup>)

Start with
T(n)=1 for n<1 and T(n)=3*T(n/3)

=>T(n/3)=3*T(n/3/3)

=>T(n)=3(3T(n/9))

=>9T(n/9)

=>(3^i)*T(n/3^i)

Now with i=log_3

=>3^log_3 of n*T(n/3^log_3 of n)

=>n*T(1)

=> $\Theta$(n)


START WITH T(n)=1

⌊x⌋ = ```
{
```x

