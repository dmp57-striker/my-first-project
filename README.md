# my-first-project
Trying github as a beginner
name: Hello World
on: [push]
jobs:
  say-hello:
    runs-on: ubuntu-latest
    steps:
      - name: Run a one-line script
        run: echo "Hello World!"
