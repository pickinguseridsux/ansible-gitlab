A simple proof of concept project used to show how Ansible works with gitlab to patch, update, and configuration manage systems.  

Complete the following on your hosts:
1. Deploy private key

Complete the following on your gitlab instance:
1. Register your runner
2. Create your $SSH_PRIVATE_KEY variables in your project

Right now we use a Ubuntu runner with the before_script sections, but another container capable of running installing / running ansible may be used.
