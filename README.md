# basetest04
ready
code
1
8
#ca

name: Greeting
on: [push] # Runs every time you push code
jobs:
  say-hello:
runs-on: ubuntu-latest
    steps:
- name: Run a one-line script
        run: echo "Hello, GitHub Actions is working!"
### How to Run
1. Clone the repo: `git clone https://github.com/user/repo.git`
2. Install dependencies: `npm install`
3. Start: `npm start`
