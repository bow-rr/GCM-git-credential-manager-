# GCM-git-credential-manager-
git-credential-manager solution on stackoverflow

Set GCM on Linux distributions so that to 'git push' from local repo to remote repo on GitHub?
This is official link :
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls 
but FAILED to install it correctly.

This stack overflow thread covers it, you will need to create a personal access token and then configure git CLI via terminal 
https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed-please-use-a-personal

You can also alternatively authenticate via SSH: https://docs.github.com/en/authentication/connecting-to-github-with-ssh

Or use the gh (cli/cli) project to manage your authentication: https://cli.github.com/manual/gh_auth_setup-git
