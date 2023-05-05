# Libraries (that I have used) Review

In my journey as a web dev I have been used tons of library, lots are really good, some aren't. I will, as the name said, review them and share what I have experienced from them — mind you that these are going to be highly subjective reviews (since I'm writing them based on what happened _to me_) and might work or later be working with you or in the newer version.

So, ready to cause some drama? Here we go 👇

[<img src="https://user-images.githubusercontent.com/7850794/164965523-3eced4c4-6020-467e-acde-f11b7900ad62.png" alt="motion" width="100" height="100" decoding="async" loading="lazy" align="right" />](https://motion.dev/)

## Motion

![NPM Downloads](https://img.shields.io/npm/dm/motion)
![NPM License](https://img.shields.io/npm/l/motion)
![GitHub Repo stars](https://img.shields.io/github/stars/motiondivision/motionone?style=social)

<details><summary>General Information</summary>

- **Install:** `yarn add motion`
- **Website:** <https://motion.dev/>
- **GitHub:** <https://github.com/motiondivision/motionone>
- **Project used:**
  - [Thai Parliament in a (coco)Nutshell](https://github.com/wevisdemo/parliament-in-a-nutshell)
  - [Law Watch](https://github.com/wevisdemo/law-watch)
  - [School Governance](https://github.com/ACT-Anti-Corruption-Thailand/school-governance)

</details>

- **Score:** 10/10 would use it on every project
- **Pros:**
  - Easy and modular, you need scroll detect? use `scroll`. Intersection Observer? `inView`.
- **Cons:**
  - Still have to look up docs what does what. `scroll` took function as first param and specify the element in option but `inView` took element as a first parameter. I respect for the design tho but like my brain still forget them time to time.
  - Timeline and animation can get very tedious with complex transformation + timing.
  - `inView` is bugging with threashold 1 and 0? might be just me. Also, the function, to return or not to return — that is the question. Still, respect them for the design tho.

[<img src="https://raw.githubusercontent.com/floating-ui/floating-ui/master/website/assets/logo.svg" alt="motion" width="100" height="100" decoding="async" loading="lazy" align="right" />](https://floating-ui.com/)

## Floating UI

![NPM Downloads](https://img.shields.io/npm/dm/@floating-ui/dom)
![NPM License](https://img.shields.io/npm/l/@floating-ui/dom)
![GitHub Repo stars](https://img.shields.io/github/stars/floating-ui/floating-ui?style=social)

<details><summary>General Information</summary>

- **Install:** `yarn add @floating-ui/dom`
- **Website:** <https://floating-ui.com/>
- **GitHub:** <https://github.com/floating-ui/floating-ui>
- **Project used:**
  - [Quantographer](https://github.com/rootEnginear/Quantographer)
  - [Thai Parliament in a (coco)Nutshell](https://github.com/wevisdemo/parliament-in-a-nutshell)
  - [Law Watch](https://github.com/wevisdemo/law-watch)
  - [TPC Course Planner](https://github.com/rootEnginear/tpc-course-planner)

</details>

- **Score:** 9/10 would use it on every project
- **Pros:**
  - Modular and super customizable, which can cover wide ranges of use like a popover, a menu, a dropdown, anything that required anchoring something to something.
- **Cons:**
  - Required you to open the tutorial every single time you want to use. Highly customizable, but also tedious to do a simple tooltip (which to be fair if you just want a simple tooltip, just use [Popper](https://popper.js.org/)).
