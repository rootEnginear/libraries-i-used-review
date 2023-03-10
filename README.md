# Libraries (that I have used) Review

In my journey as a web dev I have been used tons of library, lots are really good, some aren't. I will, as the name said, review them and share what I have experienced from them — mind you that these are going to be highly subjective reviews (since I'm writing them based on what happened *to me*) and might work or later be working with you or in the newer version.

So, ready to cause some drama? Here we go 👇

<img src="https://user-images.githubusercontent.com/7850794/164965523-3eced4c4-6020-467e-acde-f11b7900ad62.png" alt="motion" width="100" height="100" decoding="async" loading="lazy" align="right" />

## Motion

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
