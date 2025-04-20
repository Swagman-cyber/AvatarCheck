# AvatarCheck Discord Bot

AvatarCheck is a Discord bot that allows server administrators to verify users by checking their Roblox profile. When a user enters a verification code in their Roblox "About Me", they can confirm their identity in Discord and be assigned a "Verified" role.

## How It Works

1. Users will type `!verify <username>` to begin the verification process.
2. The bot will provide a unique code that the user must paste into their Roblox "About Me" section.
3. Once the user has added the code to their Roblox profile, they will type `!confirm` in Discord to complete the verification.
4. If the bot confirms that the code matches the one in the user's profile, the bot will assign them the **Verified** role in Discord.

## Requirements

Before inviting AvatarCheck to your server, make sure you have the following:

- A **"Verified" role** in your Discord server.
- A **"Unverified" role** for users who haven't completed the verification process yet.
- Users must follow the verification steps to be assigned the "Verified" role.
  
> **Note:** The role names **must** be **exactly** "Verified" and "Unverified" (case-sensitive) for the bot to work properly.

## How to Add AvatarCheck to Your Server

1. **Invite the Bot**: [Click here to invite AvatarCheck](https://discord.com/oauth2/authorize?client_id=1363198207391432788&permissions=268503040&integration_type=0&scope=bot).
   - Make sure the bot has permissions to **Send Messages**, **Read Messages**, and **Manage Roles** to assign the "Verified" role.

2. **Create the Roles**:
   - Create a **"Verified"** role in your server for verified users.
   - Create an **"Unverified"** role for users who have not completed the verification process yet.
   
3. **Role Configuration**:
   - Make sure the bot has permission to assign the "Verified" role.
   - Users must be assigned the **"Unverified"** role by default when they join the server.

## Usage Instructions

1. Once AvatarCheck is invited to your server, users can start the verification process by typing the following command:

!verify <roblox_username>

2. The bot will reply with a unique verification code and instruct the user to add it to their Roblox profile "About Me" section.

3. After updating the Roblox profile, the user will type the following command:


4. If the code matches, the bot will assign the **"Verified"** role and remove the **"Unverified"** role.

