
# GSOC 2021 CNCF Buildpacks Journey


### Personal Info

**First Name:** Halil Ibrahim

**Last Name:** Ceylan

**GSOC Link:** https://summerofcode.withgoogle.com/dashboard/project/4873238770876416/overview/
### Special Thanks
I can't thank my mentor Natalie enough for giving the most explanatory answers to even the simplest questions during this program. Throughout this program, she has been with me in all kinds of problems inside and outside of GSOC. Apart from my mentor, I would like to thank all the Buildpacks supporters who helped me on this journey, especially Anthony, Javier, Yael, who are part of Buildpacks.

### Introduce
Hi everyone, I am Halil, 3rd year computer engineering student at Mugla Sitki Kocman University. This summer I experienced a very exciting and learnful program with GSoC.

 
I will share some information about what I did and couldn't finish on time. This information may be helpful for other students who want to continue or use or extend my project. Within the scope of GSOC, I had the opportunity to contribute to many different aspects of the Buildpacks project.


During the GSOC, I had the opportunity to contribute to the following PR's first hand:

- **buildpacks/rfcs** - [Prepare Phase Draft RFC](https://github.com/haliliceylan/rfcs/pull/1) [UNCOMPLETED]

"Buildpacks" are a kind of framework for preparing a container environment for your apps. "Lifecycle" is the program responsible for executing buildpacks in the build time environment. In this issue, we covered the new "prepare phase". But we decided to change course upon realizing that the "prepare phase" had too much uncertainty and complexity to be a good summer project. So this issue is **uncompleted**. But you can reach useful information in draft PR.

- **buildpacks/rfcs** - [Project TOML Conveter RFC](https://github.com/buildpacks/rfcs/pull/182)

In this issue, The idea is to ship a binary with the lifecycle that would be responsible for translating project.toml from the schema defined in the project descriptor extension spec into something that the lifecycle knows the platform can understand i.e., a schema defined in the platform spec. We opened this issue to discuss this issue with other developers and contributors, this issue is still ongoing.

- **buildpacks/lifecycle** - [Adds acceptance tests for builder](https://github.com/buildpacks/lifecycle/pull/648)

In this issue, I developed Go Acceptance Test for the Builder lifecycle. Everything is ok, only some tests are failing with windows. Most of them are completed.

- **buildpacks/pack** - [Pack loses the names of buildpacks](https://github.com/buildpacks/pack/pull/1253)

Some pack commands do not print the names of component buildpacks. So I debug and fix the problem. After that, I changed some unit tests.

- **buildpacks/docs** - [buildpack create command is added to docs.](https://github.com/buildpacks/docs/pull/376)

I wrote documentation for a previously developed but undocumented feature in the Buildpack project.

- **buildpacks/katacoda-scenarios** - [make changes according to new pack cmd](https://github.com/buildpacks/katacoda-scenarios/pull/6)

Katacoda is a small tutorial tool based on documentation. Depending on the change I made above, I made the necessary additions to this tutorial.
