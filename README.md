## coloring-graphs
repository to house coloring graphs code

### what
this library provides support to construct graphs and their coloring graphs.
a coloring graph is a metagraph representing all the valid colorings of a graph.
each vertex of a coloring graph represents a coloring of the base graph.

in this project, we represent a coloring as an integer, which, when converted to
base k (for a k-coloring), represents the vertex-wise colors [0,k).

the library is a WIP, and is being written using Python and C/C++.
for documentation, feel free to take a look inside `lib/` and read the docstrings.
for examples, see the files in `test/`.
for questions, reach out.

### how
1. installation:

    clone the repository
    - ssh:
    `git clone git@github.com:aalok-sathe/coloring-graphs`
    - https:
    `git clone https://github.com/aalok-sathe/coloring-graphs`
    
    go into the repository
    `cd coloring-graphs`
    
    install the prerequisites
    - using the make utility:
    `make install`
    
    - manually:
        - with sudo privileges:
        `sudo python3 -m pip install -U -r requirements.txt`
        - without privileges:
        `python3 -m pip install --user -U -r requirements.txt`
    
    
2. quickstart:

    - run a test suite!
    `make test`
    
    - try the sandbox file (`test/sandbox.py`) to see how plotting works
        - `python3 test/sandbox.py 3`
        - `python3 test/sandbox.py 3 test/input/g1.in`
    
    
### help

full documentation coming soon
