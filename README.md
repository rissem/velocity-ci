velocity-cli
============

# Installation
`npm install -g velocity-cli`

#Run
Inside your project type `velocity`

#How it works
1. The velocity-cli spawns a meteor process and connects to it using DDP.
2. PhantomJS connects to the meteor process to trigger client side tests.
3. Test results received via DDP are printed at the console.
4. This process exits with the appropriate exit status code.
