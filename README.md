# AvatarCheck Bot

AvatarCheck is a Discord bot that allows you to easily **verify** users in your server by checking their Roblox profile for a unique verification code. Once verified, the bot will automatically assign the **Verified** role to the user.

---

## Features

- **Roblox Account Verification**: Users can verify their Roblox account by adding a unique code to their Roblox profile's About Me section.
- **Automatic Role Assignment**: Once the user is verified, they will be assigned the **Verified** role in your server.
- **Prevents Reuse of Codes**: The bot ensures that codes cannot be reused by checking if the code has been used before.

---

## How It Works

1. **User Verification**:
   - Users in your server type `!verify <RobloxUsername>` in any text channel where the bot has permission.
   - The bot will generate a unique verification code and ask the user to place it in their **About Me** section of their Roblox profile.

2. **Confirmation**:
   - After updating their Roblox profile with the verification code, users type `!confirm` to confirm.
   - The bot will then check the profile description for the verification code. If the code matches, the user is given the **Verified** role.

---

## Prerequisites

- **Verified Role**: Ensure that your Discord server has a **Verified** role. This role will be assigned to users once they are verified.

---

## How to Add the Bot to Your Server

1. **Invite the Bot**: Click the link below to add AvatarCheck to your Discord server:
   - [Invite AvatarCheck](YOUR_BOT_INVITE_LINK)

2. **Create the Verified Role**: Ensure your server has a role named **Verified**. This is the role the bot will assign to users once they are verified.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

