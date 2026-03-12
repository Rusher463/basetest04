# basetest04
ready 
0
..
code
1
8
#ca
((
name: Greeting
on: [push] # Runs every time you push code
jobs:
  say-hello:
runs-on: ubuntu-latest
    steps:
- name: Run a one-line script
        run: echo "Hello, GitHub Actions is working!"
