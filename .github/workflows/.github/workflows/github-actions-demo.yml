name: GitHub Actions Demo
on:
  push:
    branches: [ main ]
jobs:
  explore-github-actions:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v4
    - run: echo "The job is running on a ${{ runner.os }} server!"
    - run: ls -la
