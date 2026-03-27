---
title: Home
layout: home
nav_order: 1
---

{% include Header.html %}
<br>
![](assets/images/Assembled 1.jpg)

# Revolutionary Active Control for Electric Control Line Flying!
{: .text-center }

## What It Is
Climb_and_Dive is an open-source, do-it-yourself project that lets you build an advanced timer for electric-powered control line model aircraft. The Climb_and_Dive timer isn't just a simple switch - it's an intelligent flight control system that **actively monitors and responds** to your aircraft's flight conditions in real-time. This compact timer combines a low-cost microcontroller development board with a custom add-on circuit board to deliver professional features in a simple, user-friendly package.

## Unique Capabilities
The Climb_and_Dive timer stands out as both an **active timer** and a **governing timer** in one device. What makes it truly innovative is its **wireless programming capability** through Bluetooth and your smartphone. This eliminates the hassle of opening hatches, dealing with connectors, or using separate programming boxes.

The program code includes **built-in safety features** that provide an additional layer of protection for your power system, helping prevent damage if something unexpected occurs during operation.

Since it's open source, you have complete freedom to customize the functionality or add new features to suit your specific needs.

## Simple Assembly
The timer comes as a DIY kit that requires minimal assembly—just soldering some header pins. The kit includes two main components:

- **Seeed Studio Xiao NRF52840 development board** (the main microcontroller)
- **Custom backpack circuit board** (contains the accelerometer and RPM signal conditioning circuitry)

The backpack design streamlines wiring and makes assembly fast and straightforward.

## Easy Programming and Updates
Programming the microcontroller is incredibly simple—just drag and drop a few files on your computer. The microcontroller comes pre-programmed and tested, so you can start using it immediately.

As new features are released, you can easily [update your timer's code](docs/Software#software-installation) using the same simple drag-and-drop process, ensuring your device stays current with the latest improvements and capabilities.
<br> <br>

<span class="fs-6">
[Click Here to order a **Climb_and_Dive** kit on **Lectronz**](https://lectronz.com/products/climb_and_dive){: .btn .btn-green}
</span>

## Extensive List of Features ##

- Dimensions: 27mm x 18mm x 9mm.  Weight: 5g.  Ideal for mounting on the side of a profile fuselage.

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
