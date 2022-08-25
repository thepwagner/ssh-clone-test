
1. Create a script to mock the unit tests
2. Genenerate a new SSH key: ssh-keygen -f test_key
3. Copy the public key of our test to a deployment key: https://github.com/thepwagner/ssh-clone-test/settings/keys
4. (Optional): use a local SSH agent to verify the key actually works

5. Wrap the test script up as an actions workflow
6. Upload the private key as an Actions secret: https://github.com/thepwagner/ssh-clone-test/settings/secrets/actions
7. It works! Can we repeat the pattern using an ssh-agent?
8. We can! But it's a little gross.
