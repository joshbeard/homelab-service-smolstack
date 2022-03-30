# Smol Stack Deployment

This is a deployment of services for [Gemini](https://gemini.circumlunar.space/)
[Gopher](https://en.wikipedia.org/wiki/Gopher_(protocol)),
and [Finger](https://en.wikipedia.org/wiki/Finger_%28protocol%29) to provide a "smol Internet" stack.

It's an Ansible playbook for deploying this to my homelab.

I've written about this some at <https://joshbeard.me/posts/2022/03/28/smol-stack.html> and on Gemini at <gemini://jbeard.co/server.gmi>.

* Gemini is served by [Agate](https://github.com/mbrubeck/agate/) ([My Ansible role](https://github.com/joshbeard/ansible-role-agate))
* Gopher is served by [Gophernicus](http://gophernicus.org/) ([My Ansible role](https://github.com/joshbeard/ansible-role-gophernicus))
* Finger is provided by [Finger2020](https://github.com/michael-lazar/finger2020) ([My Ansible role](https://github.com/joshbeard/ansible-role-finger2020))
