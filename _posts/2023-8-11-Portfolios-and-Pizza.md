---
layout: post
title: Portfolios and Pizza...
---

As I continue to work on building out my portfolio, I am revisiting many of my old projects to try and piece them back together into a shareable format. I started working with Unity 3 a bit over a decade ago, and the rapid changes in technology have rendered many of my older projects obsolete. 

All of my old web games built with the Unity Web Player are no longer supported at all, and if I want them to be playable again, I need to migrate and rebuild them with the "new" HTML5 based WebGL build. However, so many things have changed in the Unity Editor over that course of time, that sometimes just bringing my projects into a newer supported version of the engine breaks nearly everything about them. Unity reworked materials with their new render pipelines after Unity 5, so everything from before then needs complete rebuilds of all materials and shaders. Then there's minor tweaks with other systems like physics, various libraries, and coding practices to contend with as well. (Also, my own programming has improved significantly since many of my earlier projects, so I also find myself needing to improve some of the hackier mistakes I made on older projects).

As an example of one [project](https://github.com/aconnolly2/HomeIsWhereThePizzasAt) that needed updating, I just updated and re-released [Home Is Where the Pizza's At](https://ghotifrye.itch.io/home-is-where-the-pizzas-at). First, some background on the game: It was developed in Unity 2019 for the 2019 Global Game Jam. The theme had been "*What Home Means To You*," and after a brief brainstorming session with my super-talented cousin [Mel](www.etsy.com/shop/MeliciousArts) we settled on "Pizza." Lightly inspired by the mechanics of Overcooked (but deeply simplified for the 48 hour challenge), we built a pizza restaurant simulator with some tragic backstory. We were able to complete the game on time without having to work too unreasonable of hours, and it was generally [well-liked](https://globalgamejam.org/2019/games/home-where-pizzas).

![Home Is Where the Pizza's At](https://lh3.googleusercontent.com/pw/AIL4fc8k8tUlNxGXoNpF-rUFBW_35Ep7LOTGh5p9vc7-VpQG3YPKFat90FU0boYFf45kgCEqQWP0Aa72Vg_tfZ1-KdhoEpNuYt1MgOV1mWnmmjNfKczAGLK1TjRfwjT1FEt-BfF3tWQm1y0XwnsfuuyrtAxuqXDDpIUOlV0OAbF70h7tv6nVSvCtH2QMfq6m40Ka9wdpjNOgpCzQ0piQWzqnfZOoEPbXeEJbOeprIEoF1S1O-b4g7N6hK4yHCHn9_UGj7F8gXHh-DUFfyxdW9iyGsI_cahyedi4tJ5ld6boNcH6o_EsPPT2lp5a8Ya0CKwf2728scgYPdNPn5aSf3abi57dUMGAqz3_swTbERTsUddqmNmuPNeXjeDA53LYYuXVd1qw12F6W5zs0lZG1ovcfOqO5nvfhpHP9kXVgUsf7uJCSSP-ezpXda5XmbmFuoxd5NIMWBohNhQylBdu_uqaJiexNtsGaaXzU4jj5fnLX31IGYEwktOU_XvRRkiblR-L8zAxXtj1Ex3fTBoQjVnn8sF9eu60qnfIVbvRGrmzdQM3LRcZiElw0V8yDvF1Elm6I6p4zFLMfK9r_w8Gp-bIuAPMBUo8cu7Fh3G5030kAtQG6XOlxrBpBtahRSTqWkUEAbQIG4r1TrIC1b-gHl--RJgI9URWYhSnctpiVH_8xyraxFDwe5Yb1QdA6hMU64qec0fTuLuXLkph3JQtqtrTqv_FaIw_P2c238OaVnipzl1Q-lpT7kzd1JG5G09lpdC3wNj4nmitxki2x8aU6bo6Iji_W2eZ17RUlTKe2iC_DB_YUJrsZWP5A4Gx1KlUTI_co-19LmoLwTHTIWIqQVLl-zZdmQYU9MbJrRURtU4s-8qf_FFFMH0mGbvy82ajN6Glgt8A-haT0SLQx-XNEkefb1OkKrkyEfcW4Xe4jNPLC715ZW2CYu4IviT0xeY_NtTSgtBcElxpL8iaru73kSAMF9evj701qhn2ovO8u2q6uI33WqaQphKD6UA=w563-h445-no?authuser=0)

*Home Is Where the Pizza's At* was only 4 years old (*ok, that does seem like a bit now that I write it down...*), but despite that relatively short amount of time, something had changed in the WebGL player and most of the collisions/input were no longer working. I distinctly remembered them working at the time when we released it, so I wasn't quite sure what had happened, so I needed to rebuild it and see if I could fix the issues. I brought it into the latest version of Unity that I've been working with lately (2022.3), and started working through the issues.

![Pizza Screenshot](https://lh3.googleusercontent.com/pw/AIL4fc8DZn4vM3Z2kXyNlXdNU6WehGwczrWvHgg50PIBw0ayYd6D6QMtw5vYvWuNF4iitOsiEuFHkkTtp_aCFW2omr123VJ4Z4XqRRIDSLxRqUOdJeoMEho1YEexKVFtMwxQvApRM4MSfYLy8-Gcnly--QaJGE9nkzvjTb7tBcsMX7k3N-Fj2osNqrNZc-NVya-o-bQng5Fa37K1z4KsHAVwV0g-2v5O3mrLsADylyWcX8DiNA8wZEtoi9SBS4moGcJa-3H3JQnWaHuu95skwDtWjd3a-ZvbHaXfEdewwXIiXggghrqK1_Fx7_GEsj_91sLeQfIpe00KQsTcBy77qbHd5IHs2j_BTzTvEhJuJAZV2nUrDj6YLne1pt6ehybd5NB5t6xhPp_QBKTuwq4VKTJK8zzIEV-he3VNbbLqDELhYrqjGfeeXOdnfRF4tDcf6lImFxdvz-6ZNTkE86elkdAPfNKxAIoZnDNZEEd-9LZbiUoZ0VR8WH86qvb8OoOdWLy5v_9kIPEIvVT4s5P1UbIlIYVrU9W3N6p7bv--7BImmYNirKCb04s87Wbp_MM2FN7664kV_TsMo5lGF3nfEyAe_FjTRrJTyIjCWCvjzMqYYxzYPNS_hxWt2RTgjDfCiGH1jL8EfnHHbElyz0tjQ76KyAYsQdWqOHuU1DUDWmIlfuQbzlnIMPgxY3jRwXedabu3kMHt6JU7HJ0NkL6cq8Z6ymegJHAbXz5U9n-8A-eGyx1wLTaZ8p1GICNOWyB_5l5iYmYTXFjxfVurPx8mA5JOSHWBaB5e8KLSjJVxThcoXYeZwznrXR8W3DlyktEapvrAAioIHf8muhsfiujyr-mHzmke_oaVn0MP8YFmhf2lkuq10UejD4JwgNdLkfaOgoD2xWD7j2GYKGomFe5Fs7h9OUfbiInzc-1iSzYvDSKAWAc6YlI_ErDXYRLBjPUKJZCO_4OJtYcYXVj6bP2fqgnz4_M74uLqPkiEb6YWyxmPXdyzfMiwrAzEtw=w1356-h762-no?authuser=0)

Thankfully there weren't too many with this project, but something had definitely changed with the physics. All of the customers entering the shop were incredibly slow, and my inputs for collisions were only sometimes firing. The first problem was a fairly easy fix. I just tweaked the movement speed until I settled on something that worked with the new system, and ended up moving it from 3 to 15, which seemed about the speed I remembered. (They were already being normalized by `Time.deltaTime`, so it wasn't a framerate issue. I'm just really not sure what happened there). The second problem was a bit more challenging, so I had to come up with a more creative solution.

The original collision methods used the `OnTriggerStay2D()` event, and then checked `Input.GetButtonDown("Jump")` (SpaceBar) to run the `CheckCollision()` function, which would handle all the various object interactions in the game. Something like this:

```C#
OnTriggerStay2D(Collider2D collision)
{
    // If SpaceBar is pressed
    if (Input.GetButtonDown("Jump"))
    {
        CheckCollision(collision);
    }
}
```

This had worked in the old system, but now it was firing intermittently (and mostly not at all). My suspicion is some sort of mismatch between the physics system running on FixedUpdate, and the Input system being frame independent. My best guess is that `OnTriggerStay2D()` was getting called at very specific intervals, and those didn't always line up with the frame that the spacebar went down. My first thought was to just change `GetButtonDown()` to `GetButton()`, which calls every frame that the SpaceBar is down. This fixed most of the issues, except when placing a pizza on the counter, which would create a sort of loop and rapidly pick up and drop the pizza on the counter. Not ideal.

Realizing that there was some sort of framerate mismatch, I decided I just needed to decouple the two methods from each other. I created a new Collider2D variable that I could cache the latest collision in, moved the Input check to `Update()`, and just stored the collider into my new class variable (I also needed to clear the variable in `OnTriggerExit2D()`, and add a null check in the input event to prevent potential errors). The results looked something like the following:

```C#
Collider2D currentTarget;

void Update() 
{
    // If SpaceBar is pressed, and we have a target
    if (Input.GetButtonDown("Jump") && currentTarget != null)
    {
        CheckCollision(currentTarget);
    }
}

void OnTriggerStay2D(Collider2D collision)
{
    currentTarget = collision;
}

void OnTriggerEnter2D(Collider2D collision)
{
    currentTarget = collision;
}

private void OnTriggerExit2D(Collider2D collision)
{
    // If the collider we left was our current target, clear that target
    if (collision == currentTarget)
    {
        currentTarget = null;
    }
}
```

I tested it out and it seemed to be working well. Everything is spaced out reasonably well in the game, so it's rare that the player will intersect more than one collider at a time, and if they do, it should just pick one of them (whatever one had `OnTriggerStay2D()` called last). The game was working again as I had remembered it, and I was able to publish it back up on my [itch.io page](https://ghotifrye.itch.io). There were definitely some gameplay mechanics that I thought could use a revisit if the game were to be developed further, but I was just looking to restore it to its original state for now. If I had the time and interest though, I would have added expiry to cooked pizzas (so you can't just backlog a bunch on the counter and deliver stale pizzas to customers without a rating ding), and I would have adjusted the customer spawn rate, perhaps adding surges and lulls, and a scaling difficulty over time (similar to what I implemented in my most recent jam game, [Potato Panic](https://ghotifrye.itch.io/potato-panic)).

Anyway, that's a brief review of some of the work that needed to be done to update and restore one of my old Unity projects. The game is back up and available now at [https://ghotifrye.itch.io/home-is-where-the-pizzas-at](https://ghotifrye.itch.io/home-is-where-the-pizzas-at) (just in case I haven't linked it enough times). If you have the time, give it a try and leave a comment. I'd love to hear what you think about it.

![Credits Pic: August & Mel](https://lh3.googleusercontent.com/pw/AIL4fc90NqeuuK4zAIQPBwDEyZK6rNL642EMiykc8dNCbsPtj2XK0AzYfMgMv4WFTalY3oQgy5TPGodByQJHK_8lBYBT05QyidxpcTzGw9J3sUzypuqufvfN37f9R0sJtoyTgfuiqXq27p7w5IHQfiR4bqsQML3vVNIsD8CdsiCNKst8PANy_o4VB17bOehUv2wCMDziBmfKuqjgAIgTdFWsMkNYVNw-vmos2tsY3lf9F05esMzLL7eBX3jFzBZDoAdAQ4Q4RjpihLx-DuBVO8DFWy02V08J4Iv5lruADHF9t9inYkV3HrN6q7gx65ojCH4Gln2AsvwYl1m5ADel-W9GDNXk_kjVkOLwdNUxt15yS8w0Flleqcb4Lt1wssmIC0Lv475GyPVOdsP0sQBwg_b1jPnHDo2sPhlI-zRt8Wq8Nb6rXgoH-_79c2q0iINMX397ccdD3-q4gae3vuh6wPqVGTb37v9yZbzPQio1lstXyABx-L1E0mFKuiNxqJFptqdgz7pUt24TqHwUMggLAnamtGrf8hYaxbGIB7fWX3XJsNoEI2ojZaYYeEkGmGADx_rVaITgghWi52V0P2bBsxJUnXv0E00o2BeEA54x0YUUNN_oov1OK3QxKfUmhR6OfQhQFzgeJn2OuRsDzXjNL7LK0yAhvXpO5paTiXDlg2xpj3-dKM_XbNszWSlZFr0PZ0Vo2osV0aBuGgS1mNGmfKjN_2b_RW02nKcR6qnYqeuJ4gnEkN1ITHU0tG62e7ll8AhjrrO051I59KRhi1q-EpliCxhJoDqVE4HivIA5IINpHsDr06wGd6Ke0vKJf869lufoc7_CJyi4Hr12lu3R9FDl_knAV0AyVTsblI3nmWu2TTDHahsL09HgLHNpnygJHS3vYU_aamQKUXVaknrs5jfoWhGJcrtIgMDa9OY7Lw3A8mUbxdlMxsxwLLrhq7KDQ48ZBLV2zgptXxdycbROkElyaDx8NgIwfeI14P3tvTy-BY2e6xZMuicrdw=s600-no?authuser=0)