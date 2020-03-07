---
description: this is the embed applied on the rules page.
---

# Rules embed

## Magic Bot - Embed Generator link

~~~~[**Embeds**](https://discord.club/embedg/) **help in making the discord text more structured and let you add a lot of info in one message.**

{% hint style="info" %}
 the embed functionality requires a web hook \(more on web hooks [here](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks)\)

You can either generate a new web hook or use the existing one on the server settings -&gt; Web hooks section
{% endhint %}

The documentation on the embed bot is [here ](https://docs.discord.club/embedg/reference/field-reference).. Please note the mentions section as it can be confusing.Welcome Message

the code below needs to be posted on [https://discord.club/embedg/](https://discord.club/embedg/)

```
{
    "content": "   Welcome to NYC GAY BROS\n=======================",
    "embed": {
        "description": "**We** are a community of gay men from diverse backgrounds and communities coming together in NYC. \n\nWe operate the Reddit sub [r/nycgaybros](https://www.reddit.com/r/nycgaybros/) and this discord server aiming to create a safe, open space \n**so we can freely express who we are.**  We are straight friendly too\n\n\n"
    }
}
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world with the next message.:

{% code title="hello.sh" %}
```bash
{
    "embed": {
        "title": "Now The important Stuff",
        "description": "```if you are a new user, you may have limited access to the Discord Server, Until we can verify and give you the access.```\n\nPlease read our rules below and head to the [Intro Channel](<#678543912708866080>)  and introduce yourself so we can get to know you and give you the relevant access.. \nWe are excited to have you here\n",
        "fields": [
            {
                "name": "Introductions",
                "value": "<#678543912708866080>",
                "inline": false
            }
        ]
    }
}
```
{% endcode %}

```bash

```



