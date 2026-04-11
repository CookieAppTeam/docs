# Moderation

## Setup
Use `/mod settings` to configure moderation settings for your server.

- Set up a **log channel** to keep track of moderation actions.
- Configure **automated moderation** to automatically take action against spam.

## Moderate Users
Use `/mod user` to moderate a specific user.

![Userinfo](https://cdn.cookieapp.me/docs/mod/user.png){ width="400" }
/// caption
View user information and perform moderation actions.
///

## User Commands
You can right-click on a user to perform quick moderation actions.

- `Right-click > Apps > Cookie`

## Other Commands
- Use `/clear` to bulk delete messages in a channel.
- Use `/delete_post` to delete a forum post. If you have logging configured, 
  a transcript of the deleted post will be saved in the log channel.

## Automatic Punishments
With `/mod settings`, you can set up automatic punishments for a specific number of violations.

For systems like Anti-Spam, you can then set the punishment type:

- **Direct Punishments**: Users will immediately receive the configured punishment on their first offense.
- **Violation**: Users receive a violation for each offense and are punished when they reach the specified number of violations.

![Userinfo](https://cdn.cookieapp.me/docs/mod/antispam.png){ width="400" }
/// caption
Choose violations or direct punishments for automatic moderation actions.
///
