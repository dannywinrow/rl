# Foundations of Reinforcement Learning with Applications in Finance

I am working my way through the [book](https://stanford.edu/~ashlearn/RLForFinanceBook/book.pdf) Foundations of Reinforcement Learning with Applications in Finance by ashwin.rao@stanford.edu

I hope it will give me an understanding of Reinforcement Learning to broaden my horizons and inspire ideas in my work.  I am also interested in the applications in finance and in particular I found this book while searching for efficient order book transactions.

Chapter 2 focuses on abstraction in general in programming and in particular in Python.  Much of the workarounds of that chapter are not required if we instead program in Julia and as I'm most familiar with that language then I will use Julia for this.  So far the only limitations I've found are:
- Julia doesn't natively define interfaces, I have chosen to follow the Graphs.jl [interface](https://github.com/JuliaGraphs/Graphs.jl/blob/master/src/interface.jl) and provide an informal interface with error handling where the functions are not defined.
- Python has iterator functions (using yield to return results) which Julia doesn't, however, Julia supports iterators through its interface and so I'm sure there are workarounds, if not better simpler approaches.

## Chapter 3 - Markov Processes

The first programming application is to define a Process