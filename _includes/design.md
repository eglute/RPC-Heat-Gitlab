- This template uses GitLab salt-formulas to configure the server. One GitLab
  instance will be deployed, configured with a Postfix server.
- For access to GitLab server, a floating ip will be assigned to the
  salt-master. Additionally, GitLab will also be on a separete network so that
applications could access your GitLab server without being on the same
network.
- Any changes to the GitLab configuration can be done using Salt pillars on
  the Salt master.
