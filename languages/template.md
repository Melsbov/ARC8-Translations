### Under here you can find the default file of the language in ARC8. If you wanna translate, copy over the file and make it in your language.

```json
{
  "noPerms": "Nie masz permisji aby użyć tej komendy.",
  "commands": {
    "botinfo": {
      "infoEmbed": {
        "title": "Informacje o Bocie",
        "fields": {
          "supportServer": "Wesprzyj Serwer",
          "botOwners": "Właściciele Bota",
          "website": "Strona",
          "botJoinDate": "Data dołączenia Bota",
          "inviteMe": "Zaproś mnie",
          "totalGuilds": "Total Guilds",
          "botVersion": "Wersja Bota",
          "botPing": "Spinguj Bota",
          "botUptime": "Czas działania Bota"
        }
      }
    },
    "rps": {
      "messages": {
        "message1": "Miałem",
        "message2": "Ty miałeś",
        "tie": "Oboje wybraliśmy"
      },
      "titles": {
        "win": "Wygrywasz!",
        "lose": "Ja wygrywam!",
        "tie": "Remis!"
      },
      "error": "Coś poszło nie tak."
    },
    "userinfo": {
      "infoEmbed": {
        "title": "informacje",
        "fields": {
          "userID": "ID",
          "userNickname": "Nazwa",
          "userAccountCreated": "Konto założone",
          "userJoinDate": "Data dołączenia użytkownika",
          "userRoles": "Role"
        }
      },
      "noRoles": "Brak roli",
      "noNickname": "Nazwa nie znaleziona"
    },
    "setup": {
      "alreadyInUse": "jest już w użyciu przez inną grę",
      "settingUpConfig": "Ustawiam ustawienia domyślne... Spróbuj ponownie później.",
      "subCommands": {
        "messages": {
          "alreadySetMessage": "{game} gra jest już przypisana do kanału {channel}, nic się nie zmieniło.",
          "setupMessage": "{game} gra jest przypisana do kanału {channel}"
        },
        "counting": {
          "embed": {
            "title": "Pomyślnie ustawiono grę Counting!",
            "description": "Następny numer to {number}",
            "fields": [
              {
                "name": "Ostrzeżenie",
                "value": "Nie mam permisji aby usunąć tę wiadomość na tym kanale."
              }
            ],
            "footer": {
              "text": "PS: Będzie użyty poprzedni numer (no chyba że wyrzucisz Bota..)!"
            }
          }
        },
        "guesstheword": {
          "setupMessage": "kanał gry Guess the word jest przypisany do kanału {channel}",
          "embed": {
            "title": "Pomyślnie ustawiono grę Guess the Word!",
            "description": "Wyślij \\`welcome\\` aby rozpocząć grę!",
            "fields": [
              {
                "name": "Ostrzeżenie",
                "value": "Nie mam permisji aby wysyłać wiadomości na tym kanale."
              }
            ],
            "footer": "PS: Będzie użyte poprzednie zgadnięcie (no chyba że wyrzucisz Bota..)!"
          }
        },
        "guessthenumber": {
          "setupMessage": "kanał gry Guess the number jest przypisany do kanału {channel}",
          "embed": {
            "title": "Pomyślnie ustawiono grę Guess The Number!",
            "description": "Wyślij \\`1\\` aby rozpocząć grę!",
            "fields": [
              {
                "name": "Ostrzeżenie",
                "value": "Nie mam permisji aby wysyłać wiadomości na tym kanale."
              }
            ]
          }
        }
      }
    },
    "disable": {
      "messages": {
        "noSetup": "Gra nie mogła zostać wyłączona, ponieważ nigdy nie została ustawiona.",
        "success": "Pomyślnie wyłączono grę {game}!"
      }
    },
    "bug": {
      "errorEmbed": {
        "title": "Błąd",
        "description": "Ta komenda może zostać użyta tylko na serwerze wspierającym.",
        "fields": [
          {
            "name": "Serwer Wspierający",
            "value": "[Kliknij tutaj](https://discord.gg/sAjef42GCP) aby dołączyć do wspierającego serwera!"
          }
        ]
      },
      "bugReportEmbed": {
        "title": "Zgłoszenie Błędu/Bugu",
        "fields": {
          "serverName": "Nazwa Serwera",
          "serverId": "ID Serwera",
          "user": "Użytkownik",
          "userId": "ID Użytkownika",
          "time": {
            "name": "Czas",
            "timeZone": "Europa/Amsterdam"
          },
          "bug": "Bug"
        }
      },
      "succesMessage": "Dziękujemy za zgłoszenie błędu! Przyglądniemy się problemowi tak szybko jak to możliwe."
    },
    "help": {
      "helpEmbed": {
        "title": "Help - Menu",
        "description": "Skorzystaj z rozwijanego menu aby zobaczyć wszystkie komendy.\n\nZnalazłes błąd? Użyj komendy `/bug [opis błedu]`!"
      },
      "selectMenu": {
        "placeholder": "Wybierz kategorie pomocy",
        "options": [
          {
            "label": "Zabawa",
            "description": "Uzyskaj zabawowe komendy Bota.",
            "emoji": "😄",
            "value": "komendy-zabaw"
          },
          {
            "label": "Ustaw",
            "description": "Uzyskaj komendy konfiguracyjne Bota.",
            "emoji": "\uD83D\uDEE0️",
            "value": "komendy-konfiguracyjne"
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
        "title": "Zaproś mnie \uD83D\uDC4B",
        "description": "I'm a mini-game discord bot.",
        "fields": [
          {
            "name": "Link",
            "value": "[Kliknij tutaj](https://arc8.fun/invite) aby mnie zaprosić!"
          }
        ]
      }
    },
    "suggest": {
      "errorEmbed": {
        "title": "Błąd",
        "description": "This command can only be used in the support server.",
        "fields": [
          {
            "name": "Serwer Wspierający",
            "value": "[Click here](https://discord.gg/sAjef42GCP) aby dołączyć do wspierającego serwera!"
          }
        ]
      },
      "suggestionEmbed": {
        "title": "Sugestie",
        "fields": {
          "user": "Użytkownik",
          "suggestion": "❗ Sugestie"
        }
      },
      "successMessage": "Dziękujemy za Twoje sugestie! Są one upublicznione w kanale sugestie na naszym serwerze wspierającym discord."
    },
    "support": {
      "supportEmbed": {
        "title": "Dołącz do naszego serwera! \uD83D\uDC4B",
        "description": "Potrzebujesz pomocy? Wejdź w link poniżej!",
        "fields": [
          {
            "name": "Nasz Serwer",
            "value": "https://discord.gg/BHGmsSkuBH"
          }
        ]
      }
    },
    "vote": {
      "voteEmbed": {
        "title": "Zagłosuj na naszego bota! \uD83D\uDC4B",
        "description": "Zagłosuj poprzez poniższe linki!",
        "fields": [
          {
            "name": "Linki",
            "value": "[Głosuj](https://arc8.fun) Top.gg\n[Vote](https://discordbotlist.com/bots/arc8) DiscordBotList"
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
            "title": "Liczyć nie umiesz?❌",
            "description": "Źle!\nMusisz zacząć od początku, następny numer to 1."
          },
          "countTwiceEmbed": {
            "title": "Już zgadywałeś! ❌",
            "description": "Nie bądź zachłanny, nie możesz liczyć dwa razy z rzędu!\nMusisz zacząc od początku, następny numer to1."
          }
        },
        "countingDelete": {
          "message": "{author} usunął swoją wiadomość z numerem {count}. Następny numer to {nextCount}."
        },
        "countingUpdate": {
          "message": "{author} poprawił swoją wiadomość. Następny numer to {nextCount}."
        }
      },
      "checkGTN": {
        "correctEmbed": {
          "title": "Poprawnie zgadłeś numer! ✅",
          "description": "Nowy numer pomiędzy 1, a 500 został wylosowany."
        },
        "numberLowerMessage": "Liczby nie wykraczają ponad 500 ani nie schodzą poniżej 0."
      },
      "checkGTW": {
        "correctEmbed": {
          "title": "Twój strzał był poprawny. ✅",
          "description": "Nowe słowo to: {word}"
        },
        "wrongEmbed": {
          "title": "Twój strzał był niepoprawny. ❌",
          "description": "Spróbuj ponownie!\n`Słowo się nie zmieniło.`"
        }
      },
      "checkPing": {
        "embed": {
          "title": "Cześć! \uD83D\uDC4B",
          "description": "Jestem discordowym botem do mini-gier.",
          "fields": [
            {
              "name": "Zaproś mnie",
              "value": "[Kliknij tutaj](https://arc8.fun/invite) aby mnie zaprosić!"
            }
          ]
        }
      }
    }
  }
}
```
