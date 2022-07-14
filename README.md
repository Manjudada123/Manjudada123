/start 
BJ's 👇
var keyboard = [
    [{
        text: "Send Phone Number",
        request_contact: true
    }]
]
Api.sendMessage({
    text: message,
    parse_mode: "html",
    reply_markup: {
        keyboard: keyboard,
        resize_keyboard: false // for big buttons
    }
})
