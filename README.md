# Stoplight CircleCI Orb

[pa11yci](https://circleci.com/orbs/registry/orb/nebulab/pa11yci)

## Description

This Orb can be used to run [Pa11y CI](https://github.com/pa11y/pa11y-ci) on your project to check
for accessibility issues.

The Orb can be run on your staging or production environment or, optionally, on dynamic preview
environments (such as those created by the  [feature-branch-preview][feature-branch-preview] Orb).

[feature-branch-preview]: https://github.com/nebulab/circleci-orbs-feature-branch-preview

## Usage

Add the following to your CircleCI configuration:

```yaml
version: 2.1

orbs:
  pa11yci: nebulab/pa11yci

workflows:
  cool-workflow:
    jobs:
      - pa11yci/run
```

Check the [Pa11y CI documentation](https://github.com/pa11y/pa11y-ci) for more information about how
to configure the tool. 

## Publishing

The [orb-tools Orb](https://github.com/CircleCI-Public/orb-tools-orb) is used for publishing
development and production versions of this Orb.

## Contributing

Bug reports and pull requests are welcome!

## License

circleci-orbs-pa11yci is copyright © 2019 [Nebulab](http://nebulab.it/). It is free software, and
may be redistributed under the terms specified in the [CircleCI Orbs License](https://circleci.com/orbs/registry/licensing).

## About

![Nebulab](http://nebulab.it/assets/images/public/logo.svg)

circleci-orbs-pa11yci is funded and maintained by the [Nebulab](http://nebulab.it/) team.

We firmly believe in the power of open-source. [Contact us](http://nebulab.it/contact-us/) if you
like our work and you need help with your project design or development.
