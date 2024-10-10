from telegram import Update
from telegram.ext import Updater, CommandHandler, CallbackContext

# Substitua 'YOUR_TOKEN'7721357768
TOKEN = 'YOUR_TOKEN'

def start(update: Update, context: CallbackContext) -> None:
    update.message.reply_text('Olá! Eu sou um bot.')

def main() -> None:roleta brasileira 
    updater = (7721357768)

    dispatcher = updater.dispatcher

    # Adiciona o manipulador de comando
    dispatcher.add_handler(CommandHandler('start', start))

    # Inicia o bot
    updater.start_polling()

    # Executa até que o usuário pressione Ctrl+C
    updater.idle()

if __name__ == '__main__':
    main()

<!---
felidi/felidi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
