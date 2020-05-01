# Simple Poll

Create a simple poll using emoji reactions to count replies.

## To Use

1. Copy the [Block Kit Builder URL][url] into your browser to open the Block Kit Builder with the example code.
2. Make any changes to the content in the panel on the right side of the page.
3. Click **Send to Slack** to post into a specific channel.

## Preview

![][screenshot]

## Customization Options

To change the name of the person creating the poll, update the URL to by your Slack direct message link, and provide your name.

```json
<https://netsuite-gbu.slack.com/archives/DE6QNFF60|RyMo>
```

To change the content of a poll item, including the emoji reaction, change the `"text"` line. The emoji should come first, then your heading in bold, and finally an option subheader after the `\n` (to remove the subheader, remove everything between the `\n` and the final `"`).

```json
"text": ":one: *A really cool thing*\nThe best option if you like fun."
```

To add an additional poll item, copy the `section` code snippet and paste it before the last `divider`.

```json
{
    "type": "section",
    "text": {
        "type": "mrkdwn",
        "text": ":four: *A fourth option*\nMake sure it's before the divider."
    }
},
```

[url]: https://api.slack.com/tools/block-kit-builder?mode=message&blocks=%5B%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22*What%20would%20you%20like%20to%20do%3F*%20Poll%20by%20%3Chttps%3A%2F%2Fnetsuite-gbu.slack.com%2Farchives%2FDE6QNFF60%7CRyMo%3E%5CnReact%20with%20an%20emoji%20to%20give%20your%20vote.%22%7D%7D%2C%7B%22type%22%3A%22divider%22%7D%2C%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22%3Aone%3A%20*This%20option%20is%20really%20cool*%5CnIt%27s%20the%20best%20option%20if%20you%20like%20to%20have%20fun.%22%7D%7D%2C%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22%3Atwo%3A%20*This%20option%20is%20best%20for%20groups*%5CnI%20hope%20you%20like%20your%20teammates.%22%7D%7D%2C%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22%3Athree%3A%20*This%20option%20is%20stupid*%5CnSeriously%20-%20you%27re%20wasting%20your%20time.%22%7D%7D%2C%7B%22type%22%3A%22divider%22%7D%5D

[screenshot]: simple-poll.png?raw=true "Screenshot"