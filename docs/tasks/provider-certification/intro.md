---
sidebar_position: 1
---

# What is a Certified Provider?

As most CAPI providers are upstream projects maintained by the open community, there is no safe way to guarantee that any clusters provisioned with a given provider can be imported into Rancher via Turtles. However, we do implement a certification process for those providers that:
- Are actively tested as part of our E2E suites.
- These tests are kept up-to-date to validate recent versions of the provider.
- Satisfy the prerequisites in the certification process. 

## Certify your custom provider

Additionally, if you are a provider developer or simply want to use a different provider that is not listed as certified, you can [reuse](../../reference-guides/test-suite/intro.md) the existing Turtles E2E suite to get started with the certification status request or simply verify that Turtles is a viable solution for you to use Rancher and CAPI together. You can read about the certification process and requirements in the [Provider Certification Guide](./process.md).

#### Why would I want to validate my provider?

The number of CAPI providers keeps growing and the community is coming up with new projects for different infrastructure hosts. This openness helps enrich the CAPI ecosystem but makes it impossible to control and test all providers Turtles will work with across the whole CAPI project. Developers of Turtles will maintain a [list of certified providers](../../reference-guides/providers/certified.md) that are actively tested and validated by CI mechanisms but this list will be limited to key and well-known providers. That is why we encourage users of providers not listed to reuse Turtles' test suite and validate the integration between the provider and Turtles.

#### Can I use Turtles with an uncertified provider?

Turtles is a project that aims to be agnostic and integrate with the whole CAPI ecosystem and you are free to use it without validating any providers. Chances are you will probably find no issues with most upstream projects.

#### What is the difference between certified and supported?

As CAPI providers are projects maintained by the Kubernetes community, we cannot guarantee support for a given provider. This is why we opt for focusing on constant validation of [Certified Providers](../../reference-guides/providers/certified.md) and offer users the possibility of integrating with the existing test suite to verify their providers of choice.
