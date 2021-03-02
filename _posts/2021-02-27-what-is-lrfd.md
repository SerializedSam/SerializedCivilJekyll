---
layout: post
title:  "Understanding LRFD"
date:   2021-02-27 17:04:01
categories: post
tags: [calculations, fundamentals]
description: An overview of the history, meaning, and use of LRFD in structural engineering. 
---

{% newthought 'LRFD is a fundamental part' %} of modern structural design. Understanding what LRFD is, and why it was developed, can help you to have a deeper and more intuitive understanding of every part of the design process. 

In this article, I'm going to move from the basic definition of LRFD into the statistical underpinnings of the methodlogy. 

LRFD stands for **L**oad and **R**esistance **F**actored **D**esign. So let's get started by examining **load** and **resistance!**

# Load and Resistance 

**Load** is probably the most self-explanatory part. When we're designing a structural element, we are going to apply some **load** to it - like the self weight of a beam, or the concrete slab, office furntiure, and people who will be walking around above a beam. 

**Resistance** literally means "the ability not to be affected by something, especially adversely". In the world of structural engineering, when we talk about the **resistance** of an element, we mean its ability to stand up to the load we're going to apply. 

A quick visualization: imagine we have a paperweight we want to place on our desk. Also on our desk we have a house of cards, and a lucky brick. 

The paperweight is our **load**. We can easily imagine the house of cards collapsing under the paperweight; it has inadequate **resistance**. The brick will easily support the paperweight; it has adequate **resistance**. 

Mathmatically, we put the **load** over the **resitance** and call this ratio the utilization. 

A utilizattion less than one (u<1) means the element has capacity to support the load. A utilization greater than 1 (u>1) means the element's capacity is less than the load applied, and we will see some type of failure. 

We can look at the utilizations from our paperweight example like this: 

$$ 	{paperweight \over brick} < 1 < {paperweight \over house-of-cards} $$ 

Now that we have a handle on **loads** and **resistance**, let's take a look at **factors.**

# Factored Design

Now we can talk about the **factors** in LRFD. 

The **factors** used in LRFD are applied to both the **loads** and the **resistance**. 

We apply **factors** to account for the fact that we don't *precisely* know the **loads** that will be applied or the **resistance** our element will have. 

For example, our paperweight may weigh a bit less than it is supposed too, or a bit more.

To account for the variability in the **loads**, we apply a **factor** to adjust them. We use a factor that produces a worse *effect* on the structure. This can mean increasing the **loads**, or decreasing them. For example, we might increase a snow load, because more snow on the beam will be worse. But we might actually decrease the dead load when we're looking at wind load, since the dead load will help resist the uplfit caused by the wind. 

Just as the paperweight may be heaveir or lighter than the design weight, our spaghetti noodle may be a bit thicker than normal, or a bit thinner. Our brick may be very solid, or it might have a chipped corner. 

To account for the variaiblity in the **resitance**, we apply a **factor** to adjust the resistane of a given element. The **resistance factor** is *always* less than one (ɸ<1), because we always want to use a **resistance** on the lower side of what the element will have. 

