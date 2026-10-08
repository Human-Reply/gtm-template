# Human Reply for Google Tag Manager

Live chat for your website, answered from Telegram. This tag adds the Human Reply chat bubble to every page it fires on. Visitors write in the bubble, your team gets each chat as a topic in your Telegram group, and the replies land back on the site live.

## Add it to your site

1. Set up your team at [humanreply.app/start](https://humanreply.app/start). Choose **Other** and type your site's address.
2. The last step gives you one line to paste. Copy the site key from it: the part after `data-site=`, like `rl_7hK2mQ9xW4`.
3. In Google Tag Manager, open **Tags › New › Tag Configuration** and pick **Human Reply Live Chat**.
4. Paste the site key.
5. Under **Triggering**, choose **All Pages**, then save the tag.
6. **Submit** and publish the container.
7. Open your site once. The setup page turns green when the bubble loads.

## What it loads

One small script from humanreply.app, which loads the chat bubble. Nothing else runs on your page.

If your site has a cookie banner that holds every tag back until the visitor agrees, it holds the bubble back too. The bubble is a functional tag: it's how visitors reach you.

## More

- Privacy: [humanreply.app/privacy](https://humanreply.app/privacy)
- Support: [hello@send.humanreply.app](mailto:hello@send.humanreply.app)
