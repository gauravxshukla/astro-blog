---
layout: '../layouts/Post.astro'
title: 'SSR, SSG, ISR: What the heck are these?'
image: /images/web-design
publishedAt: 2023-11-11
category: 'Frontend'
---

In the vast expanse of the web, three enchanting wizards, SSR, SSG, and ISR, become the backbone of our digital experiences. Let's understand the magic behind Server-Side Rendering (SSR), Static Site Generation (SSG), and Incremental Static Regeneration (ISR).

Imagine a magical realm where web pages come to life in different ways. SSR is a skilled artist who paints a masterpiece on demand. Whenever a visitor asks for a webpage, SSR dynamically crafts it on the server, delivering the latest content but with a touch of delay.

Enter SSG, a prolific storyteller who prepares tales in advance. Instead of creating pages on the spot, SSG pre-builds them during a special event, like crafting storybooks before a grand storytelling session. This approach ensures instant page delivery, especially suitable for websites with predominantly static content.

As our narrative unfolds, we encounter ISR, the magical updater. Imagine a library of storybooks – with ISR, you don't need to rewrite the entire book when a chapter changes. It refreshes only the necessary parts, updating the content efficiently without the need for a complete rebuild.


#### Server-Side Rendering (SSR):

Delving into SSR reveals its dynamic nature. When a user requests a page, SSR creates it on the server, ensuring the latest content but introducing a slight delay. This approach is ideal for scenarios where real-time data is crucial.

#### Static Site Generation (SSG):

SSG takes a different route by pre-building pages during the build time. This means that pages are ready in advance, offering instant delivery and reducing server load. It's particularly effective for websites with content that doesn't change frequently.

#### Incremental Static Regeneration (ISR):

ISR combines the strengths of both SSR and SSG. It pre-builds pages for quick delivery but updates only the necessary parts when changes occur. This allows for dynamic content without the need for a full rebuild, striking a balance between speed and up-to-date information.

### Conclusion:

Now that we know the secrets of SSR, SSG, and ISR, when should you use each enchanting spell? 
SSR is perfect for scenarios requiring real-time data, where the slight delay is acceptable. 
SSG shines in static content landscapes, offering instantaneous page delivery. ISR, with its efficient updates, is the choice when you need both speed and dynamic content, striking a harmonious balance between the two.

![image](/images/ssr-ssg-isr-comparison.png)
