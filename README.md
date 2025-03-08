# Complete Guide to Securing Your X Account

This is a comprehensive, step-by-step guide with concrete actions to secure your X (formerly Twitter) account. Following these recommendations will significantly reduce the risk of unauthorized access.

## 1. Use a Secure Email Provider and an Alias

1. **Create a secure email account** if you don't already have one:
   - [Proton Mail](https://proton.me/mail) - End-to-end encrypted by default
   - [Tuta](https://tuta.com/) - Another secure email option

2. **Secure your email account first**:
   - Enable 2FA on your email provider (this is critical as email is the "master key" to all your accounts)
   - Use a unique, strong passphrase for your email account
   - Keep your email recovery options up to date

3. **Set up an email alias service**:
   - [SimpleLogin](https://simplelogin.io/) - Open source email aliasing
   - [Addy.io](https://addy.io/) - Formerly AnonAddy, provides unlimited aliases
   
4. **Create a dedicated alias for X**:
   - Example: `x-account@youralias.com`
   - This prevents your primary email from being exposed in data breaches
   - Allows you to easily identify if X is sharing your email with third parties

## 2. Set Up a Strong, Unique Passphrase with a Password Manager

1. **Download and install** a reputable password manager:
   - [Bitwarden](https://bitwarden.com/) - Open source, free tier available
   - [Proton Pass](https://proton.me/pass) - From the makers of Proton Mail
   
2. **Generate a secure passphrase** for your X account:
   - Use your password manager's generator set to "passphrase" mode
   - Aim for at least 4-5 random words with spaces or separators
   - Example: `Happily-Amplifier-Commodore-Resize9` (but longer and randomly generated)
   - Test your passphrase strength at [Bitwarden's Password Strength Testing Tool](https://bitwarden.com/password-strength/)
   
3. **Save the new passphrase** in your password manager, ensuring you never have to memorize or reuse it.

4. **When to change your passphrase**:
   - Only change your passphrase if:
     - You suspect your account has been compromised
     - X notifies you of suspicious activity
     - There's a data breach involving X
   - Modern security guidance no longer recommends regular passphrase rotation without reason, as it often leads to weaker passwords

## 3. Enable Two-Factor Authentication (2FA)

### a. Use a Hardware Security Key (Recommended Primary Method)

1. **Purchase a hardware security key**:
   - [YubiKey](https://www.yubico.com/) - Industry standard ($45-$85)
   - [Google Titan Security Keys](https://store.google.com/product/titan_security_key) - Google's FIDO-certified security keys
   - [Nitrokey](https://www.nitrokey.com/) - Open source alternative
   
2. **Enable 2FA** on X:
   - Go to **Settings and Support** → **Settings and privacy** → **Security and account access** → **Security**
   - Select **Two-factor authentication** → **Security Key**
   - Follow the instructions to register your security key
   
3. **Purchase a backup security key** if possible:
   - Store in a secure location like a home safe
   - Register both keys with your X account

### b. Use an Authenticator App (Backup Method)

As a secondary/backup method:

1. **Install a secure authenticator app**:
   - [Ente Auth](https://ente.io/auth/) - End-to-end encrypted backup
   - [Aegis](https://getaegis.app/) (Android only) - Open source
   
2. **Enable authenticator app** as backup 2FA:
   - In the same **Two-factor authentication** settings, select **Authentication app**
   - Scan the provided QR code using your authenticator app
   - Enter the 6-digit code to confirm
   
3. **Important: Disable SMS 2FA**:
   - In the 2FA settings, disable SMS-based 2FA if possible
   - SMS is vulnerable to SIM swapping attacks and should be avoided

## 4. Securely Store Backup Codes

1. **Generate backup codes** from the 2FA settings page
   
2. **Store digital copies** in multiple secure locations:
   - In your password manager's secure notes
   - On an end-to-end encrypted cloud service:
     - [Proton Drive](https://proton.me/drive)
     - [Cryptomator](https://cryptomator.org/) with your preferred cloud storage
   
3. **Create physical backup**:
   - Print backup codes
   - Store in a secure location (home safe, safety deposit box)
   - Consider writing them in a non-obvious format (mixed with other numbers/characters)

## 5. Minimize Personal Information (Especially Phone Numbers)

1. **Avoid adding your phone number** to your X account if possible:
   - X often prompts for a phone number but rarely requires it for basic functionality
   - If you must provide a phone number temporarily (for verification), consider removing it afterward
   
2. **When a phone number is required**:
   - Some features like account verification, advertising, or recovering a flagged account may require a phone number
   - Consider using a disposable phone number service like [SMSPool](https://smspool.net/) for one-time verification 
   - If using your real number, secure it with a carrier PIN to protect against SIM-swap attacks
   - Remove the number after verification if possible
   
3. **Remove existing phone number**:
   - Go to **Settings and privacy** → **Your account** → **Account information**
   - Select **Phone** and delete your number if it's not required for your use case
   
4. **Minimize other personal information**:
   - Only provide information that's absolutely necessary
   - Consider whether you need your real name, location, or birth date visible

## 6. Review and Remove Unnecessary Permissions

1. **Audit connected apps**:
   - Go to **Settings and privacy** → **Security and account access** → **Apps and sessions**
   - Review all third-party apps with access
   - Revoke access for any apps you:
     - Don't recognize
     - No longer use
     - Don't absolutely need
   
2. **Review active sessions**:
   - In the same area, go to **Sessions**
   - Review all devices currently logged in
   - Log out of any old, unfamiliar, or unused devices
   - Consider logging out of all sessions after completing this security setup

## 7. Lock Down Your Privacy and Visibility

1. **Review privacy settings**:
   - Go to **Privacy and safety**
   
2. **Control discoverability**:
   - Under **Discoverability and contacts**
   - Disable "Let others find you by your email"
   - Disable "Let others find you by your phone"
   
3. **Control direct messages**:
   - Under **Direct messages**
   - Consider disabling "Allow message requests from everyone"
   
4. **Consider protecting your account**:
   - Under **Audience and tagging**
   - Enable "Protect your Posts" if you want a private account

## 8. Use a Secure Browser

1. **Consider using Brave browser** for X:
   - [Brave Browser](https://brave.com/) includes built-in protection against malicious links
   - Its Safe Browsing feature provides some level of protection even if you click suspicious links
   - Blocks trackers by default
   
2. **Browser hygiene practices**:
   - Keep your browser updated at all times
   - Disable unnecessary extensions (especially those with broad permissions)
   - Avoid using browser-built-in password managers (use your dedicated manager instead)
   

## 9. Establish Ongoing Security Practices

1. **Create a security maintenance schedule**:
   - **Weekly**: Review active sessions
   - **Monthly**: Verify 2FA is working properly
   - **Quarterly**: Full audit of connected apps and privacy settings
   
2. **Keep all software updated**:
   - Enable automatic updates for the X app
   - Regularly update your browser, operating system, and all security tools
   - Update your password manager and authenticator apps when new versions are released
   
3. **Monitor for suspicious activity**:
   - Enable notifications for account logins
   - Pay attention to emails about new logins or password resets
   
4. **Avoid phishing attacks**:
   - Never click links in suspicious emails or DMs claiming to be from X
   - Always access X directly through the app or by typing the URL
   - Verify that you're on the official domain (`twitter.com` or `x.com`) before logging in
   
5. **Use secure networks**:
   - Avoid logging in on public Wi-Fi without a trusted VPN:
     - [Mullvad](https://mullvad.net/)
     - [Proton VPN](https://protonvpn.com/)
   - Always log out completely when using public computers

## 10. What to Do If Your Account Is Compromised

1. **Act immediately** from a secure device:
   - Use a different, trusted device than the one you normally use
   - Use Brave or another secure browser in private mode
   
2. **Change your passphrase immediately**:
   - Generate a new, strong passphrase using your password manager
   - Make sure it's completely different from the previous one
   
3. **Check for unauthorized apps** in your connected apps section:
   - Remove ALL suspicious or unfamiliar applications
   - Consider removing all apps and re-adding only essential ones
   
4. **Revoke all sessions** to force logout on all devices:
   - This ensures the attacker is removed from your account
   
5. **Check for changed settings** that might allow account recovery:
   - Verify email address hasn't been changed
   - Check if additional recovery methods have been added
   - Review privacy settings that might have been altered
   
6. **Update your 2FA methods**:
   - Re-register your security keys
   - Set up a new authenticator app instance if needed
   - Generate new backup codes
   
7. **Contact X Support** for additional help:
   - [X Support Forms](https://help.x.com/en/forms)
   - Report the compromise even if you regain control
   
8. **Monitor for unusual activity** for several weeks after the incident


## Final Checklist

1. ✅ Secure your **email account** with 2FA
2. ✅ Set up **SimpleLogin** or **Addy.io** for email aliasing
3. ✅ Use **Bitwarden** or **Proton Pass** to generate and store a strong passphrase
4. ✅ Add a **YubiKey**, **Google Titan**, or other hardware security key for primary 2FA
5. ✅ Set up **Ente Auth** as backup authentication
6. ✅ **Disable SMS 2FA** to prevent SIM swap attacks
7. ✅ Store **backup codes** in encrypted storage and physical backup
8. ✅ **Minimize personal information** (avoid adding phone number if possible)
9. ✅ Remove **unnecessary app access** and log out of unused sessions
10. ✅ Use **Brave browser** for additional protection
11. ✅ Lock down **privacy settings** according to your preferences
12. ✅ Set **calendar reminders** for regular security maintenance

---

## Contributing

Contributions to improve this guide are welcome. Please submit issues or pull requests to the repository.

## Disclaimer

This guide represents best practices at the time of writing but security recommendations may change over time. Always stay informed about the latest security practices. The author is not responsible for any security breaches that may occur even when following these guidelines.
