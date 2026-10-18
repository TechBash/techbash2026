# Keeping Secrets Out of Your Pipeline

Commit your code, push a button, and everything is deployed – the Holy Grail of
DevOps. Nobody has to type any commands or passwords to push your app live,
everything lives in source control and it all just works.

Wait a second! My passwords are in source code? How did they get in there? How
can I stop it from happening again? And how can I keep credentials out of source
code and still make them available to my DevOps pipeline?

We’ll talk about using the open-source TruffleHog tool to find sensitive
information in our source code repositories. And how to catch credentials before
they are exposed. Finally, we’ll look at HashiCorp Vault, another open-source
tool designed specifically to securely store and retrieve secrets from the
pipeline without making them available to everyone.

## Tools

- [TruffleHog](https://github.com/trufflesecurity/trufflehog)
- [How To Rotate](https://howtorotate.com/)
- [pre-commit](https://pre-commit.com/)
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/)
- [Canary Tokens](https://canarytokens.org/)
- [GitGuardian ggcanary](https://github.com/GitGuardian/ggcanary)
- [SpaceSiren](https://github.com/spacesiren/spacesiren)

## Sample Apps

- [OWASP WrongSecrets](https://github.com/OWASP/wrongsecrets)
- [lotr](https://github.com/OtherDevOpsGene/lotr)
