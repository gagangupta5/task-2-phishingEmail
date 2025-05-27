# task-2-phishingEmail-analysis

# Today, I am analyzing this Email
Support<support@msupdate.net>
to me
Microsoft account
Your password changed
Your password for the Microsoft account ethan@hooksecurity.co was changed.

If this was you, then you can safely ignore this email.

Security info used:
Country/region: United States
Platform: iOS
Browser: Safari
IP address: 77.196.86.10

If this wasnt you, your account has been compromised. Please follow these steps:
1. Reset your password.
2. Review your security info.
3. Learn how to make your account more secure.
You can also opt out or change where you receive security notifications.

Thanks,
The Microsoft account team

# Examine this Email for Indicators
1. Check Microsoft original Emails:
> microsoft.support@gmail.com
> microsoft.account123@yahoo.com
In this Email, sender's Email support@msupdate.net

2. Analyzing Email Header:
I used online email header analyzer and check header file of this Email. I found this error:
> Dkim Signature Error:
No DKIM-Signature header found - more info
There must be at least one aligned DKIM-Signature for the message to be considered aligned.

3. I looked for urgent or threatening language in the Email body and I found:
>  Phrases that create urgency:
“Your account has been compromised.”
“Please follow these steps…”
“If this wasn’t you…”
“Reset your password.”

>  Threatening language:
“Your account has been compromised.”
“If you don’t act, your account might be at risk.”

# CONCLUSION:
DO NOT trust this email — these results strongly suggest it’s phishing, spoofed, or fraudulent.

# TOOLS USED
> hooksecurity.co
> mxtoolbox.com
