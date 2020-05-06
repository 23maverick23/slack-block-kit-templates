# Calendar Invite

Create a calendar event invite with linked iCal file.

## To Use

1. Copy the [Block Kit Builder URL][url] into your browser to open the Block Kit Builder with the example code.
2. Make any changes to the content in the panel on the right side of the page.
3. If you need to generate an iCal file, you can use this link: [ical generator][ical]
3. Click **Send to Slack** to post into a specific channel.

## Preview

![][screenshot]

[ical]: https://ical.marudot.com/

[url]: https://api.slack.com/tools/block-kit-builder?mode=message&blocks=%5B%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22You%27ve%20been%20invited%20to%20add%20this%20event%20to%20your%20calendar.%22%7D%2C%22accessory%22%3A%7B%22type%22%3A%22button%22%2C%22style%22%3A%22primary%22%2C%22text%22%3A%7B%22type%22%3A%22plain_text%22%2C%22text%22%3A%22Add%20to%20Outlook%22%7D%2C%22url%22%3A%22https%3A%2F%2Fwww.someurl.com%2Finvite.ics%22%2C%22value%22%3A%22add_to_outlook%22%7D%7D%2C%7B%22type%22%3A%22divider%22%7D%2C%7B%22type%22%3A%22section%22%2C%22text%22%3A%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22*Leading%20Practice%20Task%20Force*%5CnSession%201%5CnThursday%2C%2014%20May%202%3A00-3%3A00pm%20ET%22%7D%2C%22accessory%22%3A%7B%22type%22%3A%22image%22%2C%22image_url%22%3A%22https%3A%2F%2Fapi.slack.com%2Fimg%2Fblocks%2Fbkb_template_images%2Fnotifications.png%22%2C%22alt_text%22%3A%22calendar%20thumbnail%22%7D%7D%2C%7B%22type%22%3A%22context%22%2C%22elements%22%3A%5B%7B%22type%22%3A%22image%22%2C%22image_url%22%3A%22https%3A%2F%2Fapi.slack.com%2Fimg%2Fblocks%2Fbkb_template_images%2FnotificationsWarningIcon.png%22%2C%22alt_text%22%3A%22notifications%20warning%20icon%22%7D%2C%7B%22type%22%3A%22mrkdwn%22%2C%22text%22%3A%22You%20must%20click%20*Add%20to%20Outlook*%20above%20to%20add%20this%20to%20your%20calendar!%22%7D%5D%7D%2C%7B%22type%22%3A%22divider%22%7D%5D

[screenshot]: calendar-invite.png?raw=true "Screenshot"