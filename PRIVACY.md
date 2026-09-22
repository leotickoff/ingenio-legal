# Privacy Policy

**Last updated: 22 September 2026**

This policy covers the Meta app **"ingenio"** (app id `1969327907116002`) and the two
tools that run under it:

- **Ingenio**, which prepares and publishes content on Instagram accounts owned by the
  operator (`@ingenio.patents`);
- **@revisitthis**, a reminder bot: when someone mentions `@revisitthis` in a comment
  with a time ("@revisitthis in 3 days"), the bot confirms in that comment thread and,
  when the time comes, replies again in the same thread so the person is notified.

Both tools are operated by one private individual. They are not a company product,
they have no user accounts, and they sell nothing.

**Operator (data controller):** Leonardo Cigolini
**Contact:** ingenio623+revisitthis@gmail.com

---

## 1. Ingenio — publishing on the operator's own accounts

Through Meta's official APIs, Ingenio accesses only Instagram professional accounts
owned by the operator:

- the account's own profile information (id, username, account type);
- the account's own published media and their metrics (views, reach, likes, comment
  counts, saves, shares);
- comments left on the account's own posts;
- the ability to publish content to those accounts.

It does not access other people's accounts, private messages, follower lists, or
content it has not published itself.

## 2. @revisitthis — the reminder bot

This is the part that involves **people other than the operator**, so it is described
in full.

### When the bot receives your data

Only when **you choose to mention `@revisitthis` in a public comment**. The bot does
not read comment threads on its own, does not follow accounts, does not scan posts,
and never contacts anyone who has not mentioned it first. The mention is the request.

Meta delivers that mention to the bot's server as a webhook notification.

### What the bot stores

For each mention, and only until the reminder is delivered:

| Stored | Why |
|---|---|
| the comment id and the post/reel id | to reply in the right thread |
| the text of your comment | to read the requested time from it |
| the language it was written in | to reply in the same language |
| a time zone or city named in the comment | to compute the right moment |
| the computed due date, the status, and the id of the bot's own replies | to deliver once and only once |

**The bot does not store your username, your profile, your follower list, or any
content you have not written in that mention.** Its replies never contain an
`@username`: Instagram already notifies you as the author of the comment being
replied to.

No profiling. No advertising. No sale or sharing of data with third parties. No
automated decisions with legal effects. The data is never used to train any model.

### How long it is kept

The text of your comment, the language it was written in, and any place or time zone
named in it are deleted **as soon as the reminder is closed** — whether it was
delivered, cancelled, or failed.

What remains is identifiers and dates: the comment id, the post id, the ids of the
bot's own replies, and the due date. These are kept for **30 days**, for one reason
only: if Meta delivers the same notification again, the bot must recognise it as
already handled and not publish a second reply. After 30 days the record is deleted
entirely. The clean-up runs every six hours.

### How to cancel

**Delete your comment.** That is the whole cancellation mechanism — there is no
command to learn. Once the comment is gone, Meta no longer allows the bot to read it
or reply to it, the bot's confirmation disappears along with it, and the pending
reminder is marked cancelled and deleted on the normal schedule.

## 3. Where the data is processed

On a virtual private server rented from Hetzner Online GmbH (Germany) and hosted in
its **Helsinki data centre, in Finland** — that is, inside the European Union. The
server is administered solely by the operator. Credentials are stored in files
readable only by the server's administrator account and are never written to logs.

Storage and processing by the bot therefore take place in the EU. The data reaches the
bot from Meta, and the bot's replies are sent back to Meta; Meta's own processing is
governed by Meta's privacy policy, not by this one.

## 4. Legal basis

For @revisitthis, the processing is necessary to perform the service **you yourself
requested** by writing the mention (Art. 6(1)(b) GDPR). Without the comment text and
the thread ids, the reminder you asked for cannot be delivered.

For Ingenio, the processing concerns the operator's own accounts and content.

## 5. Your rights

You may ask for access to your data, its correction or its erasure, and you may object
to the processing. Write to ingenio623+revisitthis@gmail.com; requests are answered within 30 days.

The fastest erasure is the one you control yourself: deleting your comment removes the
bot's ability to act on it, and the stored record is deleted as described above.

You also have the right to lodge a complaint with a supervisory authority — in Italy,
the Garante per la protezione dei dati personali.

## 6. Data deletion requests

To request deletion of any data held about you, write to ingenio623+revisitthis@gmail.com with the account that
wrote the comment and, if you have it, a link to the comment. Data is deleted and the
deletion confirmed by reply.

## 7. Children

Neither tool is directed at children, and neither knowingly stores data about them.

## 8. Changes

Changes are published on this page with a new "last updated" date.
