# StreetScienceCommunity

Find all the information about our community and projects at
[streetscience.community](https://streetscience.community).

Our dedicated Galaxy server to perform all kind of data analysis can be accessed
at https://streetscience.usegalaxy.eu. 

**Bring science to the public!**

[![Gitter](https://badges.gitter.im/usegalaxy-eu/streetscience.svg)](https://gitter.im/usegalaxy-eu/streetscience?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 

## Welcome!

First and foremost, Welcome! 🎉 Willkommen! 🎊 Bienvenue! 🎈🎈🎈

This document (the README file) is a hub to give you some information about the
project. Jump straight to one of the sections below, or just scroll down to find
out more.

## What are we doing?

We are working with teachers, educators and citizens to educate the public about
open science and particularly with sequencing, data-analysis, molecular biology,
their benefits and implications.

## Who are we?

We think that knowledge transfer from different domains is crucial for this
project hence Street Science Community consists of people with different
expertise and skills. Computational- and molecular biology researchers as well
as Bioinformaticians and we are all dealing with life-science problems on a
daily basis, but from different angles.

## What do we need?

**You!** In whatever way you can help.

We need expertise in fundraising, science, education, communication, interaction
with the public. We'd love your feedback along the way, and of course.

## Get involved

If you think you can help in any of the areas listed above (and we bet you can)
or in any of the many areas that we haven't yet thought of (and here we're sure
you can) then please check out [our contributors' guidelines](CONTRIBUTING.md)
and our [roadmap](roadmap.md).

Please note that it's very important to us that we maintain a positive and
supportive environment for everyone who wants to participate. When you join us
we ask that you follow our [code of conduct](CODE_OF_CONDUCT.md) in all
interactions both on and offline.

## How can I generate the website locally?

You need a `ruby` environment (version >= 2.4). Either you have it installed and
you know how to [Bundler](https://bundler.io/) and
[Jekyll](https://jekyllrb.com/) or you use
(mini-)[conda](https://conda.io/docs/index.html), a package management system
that can install all these tools for you. You can install it by following the
instructions on this page: https://conda.io/docs/user-guide/install/index.html

In the sequel, we assume you use miniconda.

1. Open a terminal
2. Clone this GitHub repository:

   ```
   git clone https://github.com/StreetScienceCommunity/StreetScienceCommunity.git
   ```

3. Navigate to the `StreetScienceCommunity/` folder with `cd`
4. Set up the conda environment:

   ```
   make create-env
   ```

5. Install the project's dependencies:

   ```
   make install
   ```

6. Start the website:

   ```
   make serve
   ```

7. Open the website in your favorite browser at:
   [http://127.0.0.1:4000/](http://127.0.0.1:4000/)
