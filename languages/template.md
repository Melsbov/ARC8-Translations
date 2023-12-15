### Under here you can find the default file of the language in ARC8. If you wanna translate, copy over the file and make it in your language.

```json
{
  "noPerms": "You do not have the permissions to execute this command.",
  "commands": {
    "botinfo": {
      "infoEmbed": {
        "title": "Bot Information",
        "fields": {
          "supportServer": "Support Server",
          "botOwners": "Bot Owners",
          "website": "Website",
          "botJoinDate": "Bot Join Date",
          "inviteMe": "Invite Me",
          "totalGuilds": "Total Guilds",
          "botVersion": "Bot Version",
          "botPing": "Bot Ping",
          "botUptime": "Bot Uptime"
        }
      }
    },
    "rps": {
      "messages": {
        "message1": "I had",
        "message2": "You had",
        "tie": "We both chose"
      },
      "titles": {
        "win": "You Win!",
        "lose": "I win!",
        "tie": "It's a tie!"
      },
      "error": "Something went wrong."
    },
    "userinfo": {
      "infoEmbed": {
        "title": "'s info",
        "fields": {
          "userID": "ID",
          "userNickname": "Nickname",
          "userAccountCreated": "Account Created",
          "userJoinDate": "User Join Date",
          "userRoles": "Roles"
        }
      },
      "noRoles": "No roles",
      "noNickname": "No nickname found"
    },
    "setup": {
      "alreadyInUse": "is already used for another game.",
      "settingUpConfig": "Setting up the default configuration... Try again later.",
      "subCommands": {
        "messages": {
          "alreadySetMessage": "{game} channel is already set to {channel}, nothing changed.",
          "setupMessage": "{game} channel is set to {channel}"
        },
        "counting": {
          "embed": {
            "title": "Successfully set up Counting!",
            "description": "The next number is {number}",
            "fields": [
              {
                "name": "Warning",
                "value": "I don't have the permission to delete a message in this channel."
              }
            ],
            "footer": {
              "text": "PS: The previous counting number will be used (unless you kicked the bot)!"
            }
          }
        },
        "guesstheword": {
          "setupMessage": "Guess the word channel is set to {channel}",
          "embed": {
            "title": "Successfully set up Guess the Word!",
            "description": "Send \\`welcome\\` to start the game!",
            "fields": [
              {
                "name": "Warning",
                "value": "I don't have the permission to send messages in this channel."
              }
            ],
            "footer": "PS: The previous guess will be used (unless you kicked the bot)!"
          }
        },
        "guessthenumber": {
          "setupMessage": "Guess the number channel is set to {channel}",
          "embed": {
            "title": "Successfully set up Guess The Number!",
            "description": "Send \\`1\\` to start the game!",
            "fields": [
              {
                "name": "Warning",
                "value": "I don't have the permission to send messages in this channel."
              }
            ]
          }
        }
      }
    },
    "disable": {
      "messages": {
        "noSetup": "The game could not be disabled, because it has never been set up.",
        "success": "Successfully disabled the {game} game!"
      }
    },
    "bug": {
      "errorEmbed": {
        "title": "Error",
        "description": "This command can only be used in the support server.",
        "fields": [
          {
            "name": "Support Server",
            "value": "[Click here](https://discord.gg/sAjef42GCP) to join the support server!"
          }
        ]
      },
      "bugReportEmbed": {
        "title": "Bug Report",
        "fields": {
          "serverName": "Server Name",
          "serverId": "Server ID",
          "user": "User",
          "userId": "User ID",
          "time": {
            "name": "Time",
            "timeZone": "Europe/Amsterdam"
          },
          "bug": "Bug"
        }
      },
      "succesMessage": "Thank you for your bug report! We will look into it as soon as possible."
    },
    "help": {
      "helpEmbed": {
        "title": "Help - Menu",
        "description": "Use the dropdown to see all of the commands.\n\nFound a bug? Use the command `/bug [your bug]`!"
      },
      "selectMenu": {
        "placeholder": "Select a help category",
        "options": [
          {
            "label": "Fun",
            "description": "Get the fun commands of the bot.",
            "emoji": "😄",
            "value": "fun-commands"
          },
          {
            "label": "Setup",
            "description": "Get the setup commands of the bot.",
            "emoji": "\uD83D\uDEE0️",
            "value": "setup-commands"
          },
          {
            "label": "Utils",
            "description": "Get the util commands of the bot.",
            "emoji": "\uD83E\uDE9B",
            "value": "util-commands"
          }
        ]
      }
    },
    "invite": {
      "inviteEmbed": {
        "title": "Invite Me \uD83D\uDC4B",
        "description": "I'm a mini-game discord bot.",
        "fields": [
          {
            "name": "Link",
            "value": "[Click here](https://arc8.fun/invite) to invite me!"
          }
        ]
      }
    },
    "suggest": {
      "errorEmbed": {
        "title": "Error",
        "description": "This command can only be used in the support server.",
        "fields": [
          {
            "name": "Support Server",
            "value": "[Click here](https://discord.gg/sAjef42GCP) to join the support server!"
          }
        ]
      },
      "suggestionEmbed": {
        "title": "Suggestion",
        "fields": {
          "user": "User",
          "suggestion": "❗ Suggestion"
        }
      },
      "successMessage": "Thank you for your suggestion! It is publicly visible in the suggestions channel in our support discord."
    },
    "support": {
      "supportEmbed": {
        "title": "Join the support server! \uD83D\uDC4B",
        "description": "Do you need help? Click the link below!",
        "fields": [
          {
            "name": "Support Server",
            "value": "https://discord.gg/BHGmsSkuBH"
          }
        ]
      }
    },
    "vote": {
      "voteEmbed": {
        "title": "Vote for our bot! \uD83D\uDC4B",
        "description": "Vote via the links below!",
        "fields": [
          {
            "name": "Links",
            "value": "[Vote](https://arc8.fun) Top.gg\n[Vote](https://discordbotlist.com/bots/arc8) DiscordBotList"
          }
        ]
      }
    }
  },
  "events": {
    "message": {
      "counting": {
        "countingCreate": {
          "incorrectEmbed": {
            "title": "Incorrect! ❌",
            "description": "That was incorrect!\nYou have to start all over again, the next number is 1."
          },
          "countTwiceEmbed": {
            "title": "You already guessed this number! ❌",
            "description": "You can not count twice in a row!\nYou have to start all over again, the next number is 1."
          }
        },
        "countingDelete": {
          "message": "{author} deleted their count of {count}. The next number is {nextCount}."
        },
        "countingUpdate": {
          "message": "{author} updated their message. The next number is {nextCount}."
        }
      },
      "checkGTN": {
        "correctEmbed": {
          "title": "You guessed the number correctly! ✅",
          "description": "A new number has been chosen between 1 and 500."
        },
        "numberLowerMessage": "The number is always 500 and lower."
      },
      "checkGTW": {
        "correctEmbed": {
          "title": "Your guess was correct. ✅",
          "description": "The new word is: {word}"
        },
        "wrongEmbed": {
          "title": "Your guess was wrong. ❌",
          "description": "Try again!\n`The word did not change.`"
        }
      },
      "checkPing": {
        "embed": {
          "title": "Hi! \uD83D\uDC4B",
          "description": "I'm a mini-game discord bot.",
          "fields": [
            {
              "name": "Invite me",
              "value": "[Click here](https://arc8.fun/invite) to invite me!"
            }
          ]
        }
      }
    }
  }
}
```