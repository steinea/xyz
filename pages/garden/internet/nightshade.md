---
layout: page
category: wiki
subcategory: internet
title: Nightshade
publication: Nightshade
link: https://nightshade.cs.uchicago.edu/whatis.html
date: 2024-09-02
---

"Since their arrival, generative AI models and their trainers have demonstrated their ability to download any online content for model training. For content owners and creators, few tools can prevent their content from being fed into a generative AI model against their will. Opt-out lists have been disregarded by model trainers in the past, and can be easily ignored with zero consequences. They are unverifiable and unenforceable, and those who violate opt-out lists and do-not-scrape directives can not be identified with high confidence.

In an effort to address this power asymmetry, we have designed and implemented Nightshade, a tool that turns any image into a data sample that is unsuitable for model training. More precisely, Nightshade transforms images into "poison" samples, so that models training on them without consent will see their models learn unpredictable behaviors that deviate from expected norms, e.g. a prompt that asks for an image of a cow flying in space might instead get an image of a handbag floating in space.

Used responsibly, Nightshade can help deter model trainers who disregard copyrights, opt-out lists, and do-not-scrape/robots.txt directives. It does not rely on the kindness of model trainers, but instead associates a small incremental price on each piece of data scraped and trained without authorization. Nightshade's goal is not to break models, but to increase the cost of training on unlicensed data, such that licensing images from their creators becomes a viable alternative.

Nightshade works similarly as Glaze, but instead of a defense against style mimicry, it is designed as an offense tool to distort feature representations inside generative AI image models. Like Glaze, Nightshade is computed as a multi-objective optimization that minimizes visible changes to the original image. While human eyes see a shaded image that is largely unchanged from the original, the AI model sees a dramatically different composition in the image. For example, human eyes might see a shaded image of a cow in a green field largely unchanged, but an AI model might see a large leather purse lying in the grass. Trained on a sufficient number of shaded images that include a cow, a model will become increasingly convinced cows have nice brown leathery handles and smooth side pockets with a zipper, and perhaps a lovely brand logo.

As with Glaze, Nightshade effects are robust to normal changes one might apply to an image. You can crop it, resample it, compress it, smooth out pixels, or add noise, and the effects of the poison will remain. You can take screenshots, or even photos of an image displayed on a monitor, and the shade effects remain. Again, this is because it is not a watermark or hidden message (steganography), and it is not brittle."
