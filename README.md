# Feugo Bot Setup Guide

## Prerequisites

Before setting up the bot, ensure you have the following installed:

- Node js ( v 12 and higher )

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Itz-Npg/Feugo-Bot-Revamped-Version-.git
   cd Feugo-Bot-Revamped-Version--bot
   ```

2. **Install the required Python packages:**

   ```sh
    npm install
   ```

3. **Set up the environment variables:**

   Create a `config.yml` file in the

secrets

directory with the following content:

```env
# @format

BOT:
  OWNERS: ["1212431696381612132","940959891005243442"]
  ADMINS: ["1212431696381612132","940959891005243442"]



LINKS:
  SUPPORT: "https://discord.gg/nexhq"
  MONGO_URI: "mongodb+srv://agrawalritik:Agrawalritik@cluster0.282ny.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0/"
  VOTING: "https://top.gg/bot/1272058924547178581"

SPOTIFY:
  ID: "e7c9c292bbc24745b33743348e560d96"
  SECRET: "4726d6d6eba34cfe889c26844fcabc97"

MANAGER:
  OWNERS: ["1212431696381612132", "940959891005243442"]
  TOKEN: ""

NEX:
  PREFIX: "%"
  EMOJIS: "black"
  COLOR: "548fc1"
  SHARDS: auto
  PER_CLUSTER: 1
  TOKEN: ""
  VOTEURI: "https://top.gg/bot/1272058924547178581/vote"
  TOPGGAUTH: ""

# JINGLE:
#   PREFIX: "?"
#   EMOJIS: "black"
#   COLOR: "#555555"
#   SHARDS: "auto"
#   PER_CLUSTER: 2
#   TOKEN: ""
#   TOPGGAUTH: ""
#   VOTEURI: ""
  
# KYOKO:
#   PREFIX: "&"
#   EMOJIS: "black"
#   COLOR: "#548fc1"
#   SHARDS: "auto"
#   PER_CLUSTER: 2
#   TOKEN: ""
#   TOPGGAUTH: ""

WEBHOOKS:
  ERROR: "https://discord.com/api/webhooks/1286695127150104696/vPTOuOfNRlMiauDY7duWFo0o1JeXeVsRWVw13pbjRes74bIxAgZSyCAqDG_-tn21CW9s"
  STATIC: "https://discord.com/api/webhooks/1286695213745569874/_FmFIl88xAGlbv-8SprmQpfseBZ7P7stZE1QINEqt5agu4wvM63IeMCCssM0dXNUHZeY"
  PLAYER: "https://discord.com/api/webhooks/1286695355223900293/HUf-9vZqH4Gj_67Pq_6mDvhme5gt4MQ0lFMAMC-VMZKfCo4IMFin9MGNO82TAwcHSIAu"
  SERVER: "https://discord.com/api/webhooks/1286695421909143674/uGoc1Z5o2cdh7g5_3BGHypBA2zVuNLmG1B4D4voOW2w_3laQJDl2g3qFjXB0wa3D2FeO"
  COMMAND: "https://discord.com/api/webhooks/1286695492671115316/uysPkZPhyLWjKHw1dkrkgVzjo9FpO9crTkDyaIbBDkw6QgUV8I0BVN6VTUnubu0T_DN_"
```

## Running the Bot

1. **Start the bot:**

   ```sh
   node launcher.js
     ```

2. **Verify the bot is running:**

   Check the bot's status in your Discord server. It should be online and responsive to commands.


## Support

For support, join our [Discord server](https://discord.gg/ZVJrep3YJm) or contact us via [email](mailto:npgearly@gmail.com).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## As this bot is discontinued you can use but make sure to give credit to Kyxen and Zyren bot team if found using without credit legal action will be taken

Thank you for using Zyren Bot!
