---
layout: post
title: Portfolios and Pizza...
---

As I continue to work on building out my portfolio, I am revisiting many of my old projects to try and piece them back together into a shareable format. I started working with Unity 3 a bit over a decade ago, and the rapid changes in technology have rendered many of my older projects obsolete. All of my old web games built with the Unity Web Player are no longer supported at all, and if I want them to be playable again, I need to migrate and rebuild them with the "new" HTML5 based WebGL build. However, so many things have changed in the Unity Editor over that course of time, that sometimes just bringing my projects into a newer supported version of the engine breaks nearly everything about them. Unity reworked materials with their new render pipelines after Unity 5, so everything from before then needs complete rebuilds of all materials and shaders. Then there's minor tweaks with other systems like physics, various libraries, and coding practices to contend with as well. (Also, my own programming has improved significantly since many of my earlier projects, so I also find myself needing to improve some of the hackier mistakes I made on older projects).

As an example of one [project](https://github.com/aconnolly2/HomeIsWhereThePizzasAt) that needed updating, I just updated and re-released [Home Is Where the Pizza's At](https://ghotifrye.itch.io/home-is-where-the-pizzas-at). First, some background on the game: It was developed in Unity 2019 for the 2019 Global Game Jam. The theme had been "*What Home Means To You*," and after a brief brainstorming session with my super-talented cousin [Mel](www.etsy.com/shop/MeliciousArts) we settled on "Pizza." Lightly inspired by the mechanics of Overcooked (but deeply simplified for the 48 hour challenge), we built a pizza restaurant simulator with some tragic backstory. We were able to complete the game on time without having to work too unreasonable of hours, and it was generally [well-liked](https://globalgamejam.org/2019/games/home-where-pizzas).

![Home Is Where the Pizza's At](https://lh3.googleusercontent.com/pw/AIL4fc88H2utwW1my4F-LZq_yFOstro7wxsxrJrLBbisvjuv5Os_zb5OJee9Sotx7KjMFVGnAIChk3dYkPGj3XoW54LWhwlpM1c0hjSTIxbhtdAltgN3mu28pBQP0NPi_TcDimI7yBXf8BZvfICanAwAwxNWBmZRy236POUiKxIUItRwHJZrMBo51gpa4CMpUQvGLTbHw3TjDfO_NnrPEZ7yB0HNBb2d8jBKos5J5tXYHg5lAMNN0y7JAb7Scb-RAbTp05ytdLvgcspGXUOclGuDATME-ygPWSro74suwDcm_uTOOW2Z1rRB04Sy5i6RrnV26cqBn090LUykuwP-s6Ir-kMvnTKMpn_IFbR0u2YSSB8KUSoj-3Pf7wk7hzKh6IeNhsLxfKRMD-lKpMILD_cwU7gUNN4izdA9jD2ofGNt1ujiCgGWVMW6ffpjqxRrc8aIKVwyq-WVCNjxZ_PjU0iYcRyTgbtCefGo5q_DT03CQQdqj1_PcbezWYjOoAwOwwyT6r5TF3qWfBxmLSAw8PLGFcpIpkcnDFiyoepLW_lSo1BiYfRJOWCV_LZbyZCMvCjbaUPV42h7ddhIIXZsNhp1TeofeKv46OYoAaqr3kMdDQMAzlNKMkAwI2icca62Q0ylrzAmKgDEIbI0apnxezZn8sUOfpTD0XuuSC0dGnoET_P-baiWjxPaTWoW3MkT5Rn3t0vbPfPMly1DAz-Fr5bJzUzsv5zHPxH2GW4rsBN5sdBvMPr7uSr3M2VpKg3y3cUmAwsHiTwdBb8kdbXfRnGepYVr8JErc_ipi7Nluiho0wZTsom5ndJvPjW8jQLq7tHtCSl_wFK3h9KjYXI3oubSsdDEELEQfzJCgx0SZFtzQ7yA5UxmWg9T-Kx45RuqW7w2BKskI8dur272O9nJ3pFb9gbJYNqpWQ41gqIxxBX506ZytPMLdTKPp7DHwgqSOQ=w630-h500-s-no?authuser=0)

*Home Is Where the Pizza's At* was only 4 years old (*ok, that does seem like a bit now that I write it down...*), but despite that relatively short amount of time, something had changed in the WebGL player and most of the collisions/input were no longer working. I distinctly remembered them working at the time when we released it, so I wasn't quite sure what had happened, so I needed to rebuild it and see if I could fix the issues. I brought it into the latest version of Unity that I've been working with lately (2022.3), and started working through the issues.

![Pizza Screenshot](https://lh3.googleusercontent.com/pw/AIL4fc-kcN9HOz9nBOH6UgqMNL5CR9TnLLhwxS9fF1mTkjU8Ymd3bRk8h5CvKPzmBrfcMiTZupH3IQ3HPR3Dlz5bq657ipOsytS3TteXsLgdvvx6K8SurDEtT5777_03iPXaszSETeRTo24aA0a_K_KCf7OBpSyyT1I7FYdIT8aQ7wGkpph1x-OA7nt45yySzXggasR72KJa0rpS2lJi3_zVuvDpUk1Q36_geimh4vkcz0iyu-n5j1FZaX-1jqZe2bh9hGiJ9jznbdbYP5DQSPrmS9ggeYUspJRLOGgs8sNgK1Kxs1cFuafkGXVXMQW7NnxETLV0FCtnE-ww-JXTPDVCyTvXiXKgCYPI_24VRllGieAEwjjOB45A4n5RO3a0XRXQ3eV0318s4f9MvV6ImBbjdwT-rEGBwmyROSkYEwxVP1AlKE0oGkElK9iAJUXFNGumYW5AxU3rn_6ZnypK5XZRnc612beqw0eNGL-JGvdD9fy0H3l9FSQLrcTHViAblQErzyOF_hG5tUKbqrK2NlHoYgMaZk9xopeKg8JA0LLpjACzg9FJPBZYV6BYoQ8mpWRyWC2Gq0ogBz_7LGGq8RO4S056mvdLc6da1vYLtLn0G3ohuvgCvFx9sEeJUH5wjgj6mrD7QD9DBLSKUDy_4LU0bZudy_rGuRIGKycFQxYleBmu87PaRkHMDJ6Ew7IxRjmrhCp9jrHG7ivPI5uqx91nFZZAdo_3GRx0gQLb_kwcZt58JQrp1Ry8AXMrWxALBTmmyHVR9QCBe3emwZ27Sqb1dArq40rHx_hXnykNoB11KSUUttPFE6h7NcUSCvy1DIfdvERXveoiaAtu-PPtMm_zRpLE7M_TJn_a0jwDuuApxvgN0QnsR_6urMXhelx-Ao2peuEXKgvUbZsahjQn1A46-y_Ga4gJXvySOODuT4Bk_gwJwY1836phgNK_MXOZSA=w1461-h823-s-no?authuser=0)

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

![Credits Pic: August & Mel](https://lh3.googleusercontent.com/pw/AIL4fc8d6dHQJw-Y_EipKxhIlE-vUdf2J6oiQNDBn4Xf-H5Q4TrNW7woxU_hWmVLqWq1rM-BaDr9Y28ccy9wCcCzYGxefwPiJ5S5VToEBsQxkbuIb0YZEUhmoSlG_ti_Yn7QEpEVuikxLfNvlAz1qvWTs64wi8LKs5mZHSlgBkxAcE9lwC-MoTwU7E_QRHFSlrsVvrKx-KHehJFx9TMurjUpZYbnBpdZFFriVF-ENDya2CF0oJgWgobQZibzK_V1jTPfn1vwJlQ6_tW-YI08OY4AOk2qTcyFjMhJ0oSY74a4UYe6SFOIZSWF8Htt71s3FEkpqs67y4LdLZFCyjJEogdpJ9ijd_ceITwulA3SVJu533JqZB6kkI2SSgE3gT4n5PIZKq0BVwl3evbTYvo3dHw5KU1rrLTW8LVR1pz_90zP9MYYt91USs4mtH2tHXGgHgFZ-cwYeMbm0hKWJ4dwXqJo0vlspwKNZ4nnwu7RTI6SPp8b2-nWxGUURslk7TskfT2KOuS9V3LWyXwdDaHOychUQMpKR91cCIrWb7TDQY_c9aY9--GnaZ7OKlv9ZXaU9RPZDJIbORsppMCGs5kAuHt2bEWQd2HZ-ssNS-ylcRhR8aV3lTiRMvPsSuuwp4upYLBclR9TVlq2dJOFVCaM4kYi9Fo1SYgIMpFa3GZex_419YEOXGNTbeMStIywc6HrB5z3fZcb0JmZEWTrxU9vTuDl2ndjMoLj2hMRye8KdYeXHd-ciu4z_-8H2KPw-JOcwgv_zcw23X1tpiZz-NToZ4QY6GuiEYX50eD_WfzJIf0XrSAwfnjSUuCI_pYZ8CqXXvjQf6sAbXtowluwCpILBfWwdid43ncGvVEr72PEvqB9Gw5bJLNVOE4SUI1alhY6L49OHCbBUdH1sNARoj618FokZtDZ5EXXuchYsntCl_0vCFH4JRn2HkDqSJGn7MLRiw=w600-h600-s-no?authuser=0)