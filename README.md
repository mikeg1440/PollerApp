# PollerApp
A simple polling Single Page App created with Ruby on Rails back end API and a JavaScript front end.  Users can goto the site and submit a poll response as well as view the results of each poll.  Users also have the ability to create their own polls if they wish.

## Getting Started

You will need to clone the front end repo and the backend repo for this application.  The [Front End is here](https://github.com/mikeg1440/PollAppFrontend) and the [Back End is here](https://github.com/mikeg1440/PollAppBackend).  Once you clone the both repos you can start have to [set up Postgresql](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04) if you have not done so already.  After that you just need to create the database and run migrations like this 
```
rails db:create 
rails db:migrate 
```
After running migrations you can run the local rails server with `rails s` and lastly you will need to run a server for the front end as well, you can do this with any simple server like node live-server `npm live-server` or python3 `python3 -m http.server`.  Thats all for the initial setup and can start using the app by navigating to the address the front end is running on (should be displayed in terminal after running npm or python3 server).

### Prerequisites
  - Ruby on Rails 
  - Postgresql 
  - Node live-server or python's simple server 
  
## Contributing

I love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## I Develop with Github
I use github to host code, to track issues and feature requests, as well as accept pull requests.

Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://guides.github.com/introduction/flow/index.html)). We actively welcome your pull requests:

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Any contributions you make will be under the MIT Software License
In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can.
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## Authors

* **Michael Gaudreau** - *Initial work* - [Repo](https://github.com/)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License


Copyright (c) 2020 Michael Gaudreau

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

