from telegram import*
from telegram.ext import*

bot=Bot("1895422998:AAESPSyoLpW85T7hOE8b7RUuL0mhONvJVqE")
#print(bot.get_me())
updater=Updater("1895422998:AAESPSyoLpW85T7hOE8b7RUuL0mhONvJVqE",use_context=True)
dispatcher=updater.dispatcher
def test_function(update:Update,context:CallbackContext):
    bot.send_message(
    chat_id=update.effective_chat.id,
        text="hello how are u?",
    )
start_value=CommandHandler('hi',test_function)
dispatcher.add_handler(start_value)



updater.start_polling()
