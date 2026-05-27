---
hide:
  - toc
---

# Changelog
Here you can find new features and improvements in each version of Cookie.

!!! info
    We fix bugs with every release, but they are not listed here. Join our 
    [Support Server](https://cookieapp.me/support) for more details about bug reports and fixes.


## 2026.5.0

### 📝 New Feature: [Applications](features/applications.md)
- Use `/application` to create job openings that users can apply for.

### 👥 New Feature: [Team Management](mod/team.md)
- Use `/team` to manage your server's team roles and their permissions.

### 🚬 New Feature: [User Reports](mod/reports.md)
- Users can now report other users for misbehavior in the server.
- Use `/mod settings` to configure user reports.

### ⚙️ New Feature: [Automations](features/automations.md)
- Use `/automations` to create custom automations for your server.
- Execute actions based on triggers such as user joins, reactions, and more.

### ✅ Verification
- You can now choose multiple verification roles.
- Added the option to enable verification for suspicious users only.
- You can now choose criteria for suspicious users, such as account or username.
- Added option to enable log messages and automatic roles for suspicious users.

### 📝 Logging
- New log events: `Channel Created`, `Channel Deleted`, `Channel Updated`.
- Clarified where log messages for mod actions (such as warns) are sent.

### 🎫 Ticket System
- You can now rename tickets channels by using the moderator tools inside a ticket.
- Ticket moderator statistics are now displayed inside of `/mod user` instead of `/ticket stats.`

### 📊 Stats
- With `/settings > Advanced`, you can now choose to show invalid voice minutes for `/stats`.


## 2026.4.1

### 🎨 New Design
- `/rank` now sends an image instead of an embed.
- New design for `/info`, `/profile` and many more messages.
- The **server banner** design has been adjusted to fit on mobile devices as well.

### ⚙️ Settings
- `/settings` is now more organized and easier to navigate.
- A cooldown has been added to the error log channel to prevent spam in case of multiple errors.
- You can now create more **ticket categories** without Cookie Premium.

### 🏷️ Server Tag Rewards
- Use `/settings` to reward users that use your **server tag** with a role!

### 🔊 TempVoice
- Cookie will create TempVoice channels in case of a permission error and display missing permissions.

### 🎲 Counting Game
- Cookie will now display the correct number when the message with the latest count is deleted.


## 2026.4.0

### 🚬 [Moderation](moderation.md)
Cookie now has a complete moderation system!

- Use `/mod settings` to configure logging, auto-moderation, and much more.
- Use `/mod user` to view user information and perform moderation actions.
- Right-click on a user and select `Apps > Cookie` to perform quick moderation actions.
- Added `/clear` and `/delete_post` commands for bulk deleting messages and forum posts.

## 2026.3.1

### 🎫 Ticket System
- New design and structure for `/ticket settings`.
- `/ticket setup` was removed in favor of `/ticket settings`.
- Improved ticket limit settings.

### ✏️ New Message Design
- New design for `/give`, `/orders`, `/birthday`, `/stats` and `/level settings`.
- Many messages have been updated to use Discord's new component system.

### 💎 Premium
- `/premium api` was merged into `/premium info`.


## 2026.3.0

### 🔊 Voice Streak
- When using `/stats user`, you can now view your longest voice session in the selected time period.

### ⚙️ Settings
- You can now use the user language (if available) instead of the server language to support multiple languages.

### 🎲 Games
- You can now play Tic-tac-toe against Cookie.
- New design for Tic-tac-toe, WordGuesser and Rock Paper Scissors.

### 🍪 Vote Reward
- You can earn a role on the Support Server by voting for Cookie on top.gg.


## 2026.2.2

### ✍🏼 Changelog
- This changelog has been added to the documentation.


## 2026.2.1

### 🎉 Giveaway
- Added a default value for the giveaway time.
- Improved `/giveaway manage` by adding a button to jump to the giveaway message.
- Ordered giveaways in `/giveaway manage` by their end time and show the end time in the giveaway selection.

### 🍪 Economy
- Added interest for `/safe` deposits with weekly payouts.
- Added a new design for `/safe`.
- Improved withdrawal and deposits for `/safe`.

### 🎲 Counting Game
- The counting game now supports number emojis, e.g., 1️⃣, 2️⃣ or 3️⃣.

### ✏️ Join Message
- Updated message when Cookie joins a new server to include a link to the documentation.


## 2026.2.0
This update makes Cookie's commands and settings **more organized**!

### 🎉 Giveaways
- You can now use `/giveaway manage` to view participants, redraw winners, or end giveaways.
- New design for giveaway messages.

### 🍪 Economy  
- Some random items can now be used with `/inventory`.
- Sell your items directly in the inventory, no longer with `/sell`.
- `/achievements` now shows the exact progress value.

### 📈 Level System  
- All level settings have been consolidated under `/level settings`.
- Settings for XP amount and XP cooldown have been added.
- You can now decide whether all voice minutes or only valid voice minutes are counted.
- Voice XP for individual members can now be adjusted manually.

### 🎫 Tickets  
- You can now manually adjust the **order** of ticket categories.
- You can now manage all ticket categories with `/ticket categories`.
- The ticket blacklist settings have been consolidated under `/ticket blacklist`.
- New design for ticket moderator settings with `/ticket moderators`.

### ✏️ Message Editor  
- With `/messages`, you can now move components between containers and the main message.
- You can now convert existing embeds from Cookie into the new Discord components (`Right-click > Apps > Edit Message`).

### ⚙️ Settings  
- With `/settings`, you can now access the settings of other systems.
- All **TempVoice** settings have been consolidated under `/tempvoice`.

### 🎲 Counting Game  
- The reaction to incorrect counting messages can now be disabled.
- Actions for incorrect counting messages can now be completely disabled.


## 2026.1.2

### 🎂 Birthday
- You can now set your **server timezone** in `/settings`.
- Birthday messages are sent at **midnight** in the selected timezone.

### 🎫 Ticket System
- You no longer need to set a **log channel** if you don't want to.
- The **category** for open and closed tickets can now be the same.
- The **settings design** has been improved.

### ✏️ Message Editor
- With `/messages`, even more ticket messages can now be customized.
- A note has been added to `/embed`, recommending the new message editor for better customization options.

### ✅ Reminder
- With `/reminder list`, you can now view completed reminders.
- The **design** of the reminder list has been improved.
- Reminders are now displayed invisibly when Cookie is not on the server.
- You can now create **more** reminders without Cookie Premium.

### ✨ Miscellaneous
- Giveaways can now be ended **early**.
- The settings design for welcome messages in `/welcome` has been improved.
- Polls have been removed.
- The default message color in `/settings` can now also be removed to support Discord's new component system.
- The Counting Game now pins an info message showing the active modes.


## 2026.1.1

### 💻 Cookie Documentation
- We've updated and completely redesigned Cookie's [documentation](https://docs.cookieapp.me) website.
- The documentation's [**code**](https://github.com/CookieAppTeam/docs) is now **public**.


## 2026.1.0

### ✏️ Customize Cookie Messages
📝 With `/messages`, you can now easily **personalize** Cookie's messages!

- Create custom **message designs**, e.g., for the ticket system.
- Edit messages **directly**, without tedious templates.


## 2025.12.1

### 🗓️ Year In Review 2025
- You can now view your personal 2025 year-in-review with `/year-in-review`.
- The year-in-review now includes channel names within the images.
- You'll now find a few Christmas items in the `/premium shop` for a limited time 🎄


## 2025.12.0

### ✏️ Message Editor
- With `/messages` you can now create and send any messages using the new Discord components.

### 🎲 New Game: Counting
- With `/game counting` you can let your server members count as high as possible in a channel.
- The game supports regular numbers, Roman numerals, mathematical expressions, and binary numbers.

### ❌ Level Reset
- You can now reset your server's level data with `/level settings`.

### 💻 Tickets
- Ticket categories can now be disabled without deleting them.
- In the ticket statistics, all tickets that a moderator had access to now count toward the average claim time.

### ⚙️ Miscellaneous
- With `/settings` you can now disable annoying reminders from members on your server.
- The `/help` command has been tidied up a bit.
- Auto-reactions can now be added in news channels as well.


## 2025.11.2

### 💰 Free Cookie Premium Trial

This week is **Black Friday** 🎉 You can now try **Cookie Premium** free for **30 days**.

- Use `/premium info` to start the free trial 💎
- You don't need a payment method.


## 2025.11.1

### 🍪 Economy
- All participants are now shown during **Cookie Parties**.
- The limit for `/give` and `/cookie_party` has been increased.
- For high **daily streaks**, you now earn milestones and bonus cookies every 50 days.
- You'll now receive more cookies as a gift on your **birthday**.

### 🎫 Tickets
- With `/ticket category edit`, you can now set a **custom notice text** for each ticket category, 
which is displayed before a ticket is opened.


## 2025.11.0

### 📈 Leaderboard
- With `/leaderboard`, you can now see **your own** placement, even if you're not at the top!
- You can now access your server's leaderboard directly from the server dashboard.
- From server statistics and leaderboards, you can now jump straight to global statistics.

### 💻 Dashboard
- You can now manage voice level roles and combined level roles directly in the dashboard.
- Error messages in the ticket settings are now clearer.
- A button has been added to refresh Discord data such as roles and channels.


## 2025.10.1

### ✏️ Custom Bot
- With `/custom_bot`, you can now customize Cookie's **name**, **avatar**, 
and **profile description** and **banner** to make it unique for your server.

### 🖼️ Server Banner
- The banner settings have a brand-new look and are now all available under `/banner`.

### 🐞 Bug Reports
- Easily report any issues with Cookie using `/bug`.

### 📝 What's New?
- Commands like `/help` now show you the latest Cookie updates.


## 2025.10.0

### 🎉 Giveaways
- Creators and sponsors now receive a DM when the giveaway ends.

### ⚙️ Settings
- In `/settings`, the default embed color and the error log channel can now be set.
